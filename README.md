# hello-world
just test github
public boolean checkFile(MultipartFile file, String path, String fileName)
    {
        long size = file.getSize() / 1048576;
        
        if (size > 30)
        {
            log.info("file is too large");
            return false;
        }
        if (file.isEmpty())
        {
            log.info("file is empty");
            return false;
        }
        boolean isExcel = isExcel2007(fileName);
        if (!isExcel)
        {
            log.info("not the 2007 version of the excel file.filename:{}" + fileName);
            return false;
        }
        boolean isValid = isValidFileName(fileName);
        if (!isValid)
        {
            log.info("not a legal filename or filename is empty.filename:{}" + fileName);
            return false;
        }
        File newfile = new File(path + File.separator + fileName);
        if (newfile.exists())
        {
            log.info("file is already exist." + fileName);
            return false;
        }
        return true;
    }
