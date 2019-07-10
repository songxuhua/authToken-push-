苹果推送支持authToken方式和证书配置方式
1.authToken 方式AuthKey_9D85577L74.p8是authtoken,在appledeveloper里生成的p8文件,具体参见:https://www.jianshu.com/p/b700f0237b0e 和 https://www.jianshu.com/p/77e55126ca87

2.php证书配置方式详见https://www.jianshu.com/p/2a854abb7e38 ( 将你自己的p12证书拖入,/php_apns/php证书生成shell 文件夹下，执行compose.sh可生成ck.pem,将pem文件拖入/php_apns目录下)