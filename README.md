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

