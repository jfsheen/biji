 #1
Access-Control-Allow-Origin。HTTP响应头，指定服务器端允许进行跨域资源访问的来源域。可以用通配符*表示允许任何域的JavaScript访问资源，但是在响应一个携带身份信息(Credential)的HTTP请求时，Access-Control-Allow-Origin必需指定具体的域，不能用通配符。

#extjs
1. model.schema 设置id默认为'default', 如果不设置该属性，则所有model都使用该schema config，设置id为其他值后，只有extend该base的model使用该schema config，
2. 如果使用child session，则必须存在一个id为'default'的schema，session默认使用该default schema的设置



#git
git rm -r --cached .idea

#win7
修改win7用户密码：
1. ubuntu live 启动系统；
2. 修改c:\windows\system32\osk.exe为其他名字，修改c:\windows\system32\cmd.exe 为 osk.exe;
3. 启动win7，左下角"快速访问"处点*打开放大镜*->*软键盘*,出现cmd窗口，使用命令 net user USERNAME NEW_PASSWORD 修改用户密码！
