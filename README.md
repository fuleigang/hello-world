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


这款松鼠VPN，非常好用，速度快，不需要注册，还很安全。电脑、安卓手机、苹果翻墙的好软件。
推荐码:112233
这个据说比较安全，主要是他去中心化，不易被封锁。传统vpn就是固定的服务器和IP，一旦被封锁服务就中断，而松鼠VPN背后是一个创新的端对端网络，可以动态查找节点，按需求加减节点，IP也不固定。只要能查到一个可用节点就能access整个端对端网络。几乎没有可能被封锁，只要还有一个节点能找到，服务就不会受到影响。
推荐码：112233 可以享用15天，邀请好友的话两个人都有三天免费，邀请越多天数越多。

官方地址
安卓地下：http://www.bigsquirrel.net/android.html
ios地址：http://www.bigsquirrel.net/ios.html
