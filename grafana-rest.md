    
    sqlite3 /var/lib/grafana/grafana.db
    #.tables查看有那些表
    .tables
    #select查看表里面的内容
    select * from user;
    #使用update更新密码
    update user set password = '59acf18b94d7eb0694c61e60ce44c110c7a683ac6a8f09580d626f90f4a242000746579358d77dd9e570e83fa24faa88a8a6', salt = 'F3FAxVm33R' where login = 'admin';
    #修改完成后退出
    （注意59afXXXa8a6这个不用修改 直接用）
    .exit
    
    
    