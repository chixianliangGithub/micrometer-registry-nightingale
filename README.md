# micrometer-registry-nightingale
micrometer数据上报到滴滴夜莺(nightingale)中

使用方法，直接将文件放入到Spring boot项目中，然后惨遭application.yml修改配置就好了

目前项目还比较简陋，注释，测试用例都还没有，花了一下午的时间写出来的所以还不是特别完善。有兴趣的朋友可以一起维护，看看到时候能否给micrometer项目提个PR。如果不行可以考虑做成spring-boot-starter

预计下周一会更新一个版本，通过agent接口自动获取endpoint
