# less-template
less模板，固定样式模块化，变量，动画，过度，等

### 了解更多less，请移步 [less中文网](http://lesscss.cn/)

### 目录结构
```
    ┌─ fonts                          // icon文件
    │      ├─ icomoon.eot                 
    │      ├─ icomoon.svg                
    │      ├─ icomoon.ttf             
    │      └─ icomoon.woff            
    ├─ images                         // 图片
    ├─ layout                         // 布局与业务
    │      ├─ pages                   // 业务页面文件夹
    │      ├─ flex.less               // flex弹性布局
    │      └─ responsive.less         // 移动端兼容性
    ├─ less                           // 全局
    │   ├─ common.less                // 全局样式
    │   ├─ iconfont.less              // icon样式
    │   └─ variables.less             // 全局变量
    ├─ widgets                        // 组件
    │   └─ transition                 // 过度
    └─ app-base.less                  // 整合less，项目引用这个即可
```
在项目中为了方便维护，多人协作，样式命名要有一套规范，并且按组件，业务来编写。
这里只是提供了一个初始模板，具体的更多写法，还需要根据自己的具体项目需求进行编写，不懂请移步 [less中文网](http://lesscss.cn/)
