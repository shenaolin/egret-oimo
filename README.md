# egret-oimo

------

## 使用方法

1. 复制oimoPhysics文件夹到egret项目的libs文件夹下

2. 修改项目根目录下的egretProperties.json文件如下:
``` json
"modules": [
    ...
    {
      "name": "oimoPhysics",
      "path": "libs/oimoPhysics"
    }
]
```

3. 运行命令
```
egret build -e
```

4. 使用模块OIMO

## 参考文档
[添加egret第三方库](http://developer.egret.com/cn/github/egret-docs/extension/threes/instructions/index.html)
[oimo引擎项目](https://github.com/lo-th/Oimo.js)