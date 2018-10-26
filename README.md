# hello-world
just test github
 public List<BncLineUser> queryAllRegion()
    {
        List<BncLineUser> list = mapper.queryAllRegion();
        
        List<BncLineUser> allRegiontList = mapper.queryAllRegionList();
        

        for (BncLineUser bncHeadquarterUser : allRegiontList)
        {
            for (BncLineUser bncUser : list)
            {
                if(bncHeadquarterUser.getRegionCode().equalsIgnoreCase(bncUser.getRegionCode())){
                    bncHeadquarterUser.setPersonNum(bncUser.getPersonNum());
                }
            } 
        }
        return allRegiontList;

    }
