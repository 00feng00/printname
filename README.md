### 目录说明

~~~
+-- demo.js              // 方法调用
+-- filtration.js        // 导出资源
+-- README.md            // 说明文档
~~~

#### 说明

- 这个项目是对npm publish发布的一个运用


#### 使用步骤

1、首先在自己的本地建立好对应的资源文件，比如这里的filtration与demo文件。
2、然后通过node测试自己的资源文件，确认可以正常运行。
3、把建立好的项目上传到GitHub托管。
4、接着我们可以发布到npm市场了（npm init、npm publish）。
5、现在我们可以到npm官网搜索查看刚刚上传的项目了。
6、执行npm install --dev filtration，新建一个testNpm.js文件，输入如下代码：
```
var testFiltration = require('filtration')

testFiltration.hello('aFeng')
```
7、最后node testNpm.js 就能看到输出hello aFeng 

#### 温馨提示
1、在npm发布，首先得先注册用户，注册方式有两种，一种是在官网注册，另外一种则是npm adduser。<br />
2、注册完成后，你需要在npm库Create a New Organization。<br />
3、恭喜你，获得了发布的许可了。<br />
