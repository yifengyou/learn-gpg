# gpg命令

```
gpg
相关命令：暂无相关命令
语法：gpg [选项] [文件名]
签名、检查、加密或解密
默认的操作依输入数据而定

指令：

 -s, --sign [文件名]        生成一份签名
     --clearsign [文件名]   生成一份明文签名
 -b, --detach-sign             生成一份分离的签名
 -e, --encrypt                 加密数据
 -c, --symmetric               仅使用对称加密
 -d, --decrypt                 解密数据(默认)
     --verify                  验证签名
     --list-keys               列出密钥
     --list-sigs               列出密钥和签名
     --check-sigs              列出并检查密钥签名
     --fingerprint             列出密钥和指纹
 -K, --list-secret-keys        列出私钥
     --gen-key                 生成一副新的密钥对
     --delete-keys             从公钥钥匙环里删除密钥
     --delete-secret-keys      从私钥钥匙环里删除密钥
     --sign-key                为某把密钥添加签名
     --lsign-key               为某把密钥添加本地签名
     --edit-key                编辑某把密钥或为其添加签名
     --gen-revoke              生成一份吊销证书
     --export                  导出密钥
     --send-keys               把密钥导出到某个公钥服务器上
     --recv-keys               从公钥服务器上导入密钥
     --search-keys             在公钥服务器上搜寻密钥
     --refresh-keys            从公钥服务器更新所有的本地密钥
     --import                  导入/合并密钥
     --card-status             打印卡状态
     --card-edit               更改卡上的数据
     --change-pin              更改卡的 PIN
     --update-trustdb          更新信任度数据库
     --print-md 算法 [文件]   
                               使用指定的散列算法打印报文散列值

选项：

 -a, --armor                   输出经 ASCII 封装
 -r, --recipient 某甲        为收件者“某甲”加密
 -u, --local-user              使用这个用户标识来签名或解密
 -z N                          设定压缩等级为 N (0 表示不压缩)
     --textmode                使用标准的文本模式
 -o, --output                  指定输出文件
 -v, --verbose                 详细模式
 -n, --dry-run                 不做任何改变
 -i, --interactive             覆盖前先询问
     --openpgp                 行为严格遵循 OpenPGP 定义
     --pgp2                    生成与 PGP 2.x 兼容的报文
```
