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
下载软件
https://github.com/shadowsocks/shadowsocks-windows/releases

2019年封VPN比较严重，很多VPN都无法使用，科学上网的方法就少了很多种，今天我给大家带来电脑免费翻墙的方法个人觉得比VPN好用还长期有效果，这个才是重点哦。
里面用到的地址：

强烈推荐不用注册，非常好用安全的VPN：https://youtu.be/-d50nqZVmkw

下载地址：https://github.com/shadowsocks/shadow...
节点地址：https://free-ss.site/
手机翻墙方法：https://youtu.be/Q3osbiq0llw  超级好用，强力推荐
免注册超好用的VPN：https://youtu.be/_slg8SKgG4s

强力推荐看个：https://youtu.be/8XYFdCKLuM8
