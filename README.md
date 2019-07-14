# vue-router
```
1、在index.html文件中，增加 ",minimun-scale=1.0,maximun-scale=1.0,user-scalable=no"，要求移动端设备，用户通过手指放大和缩小为无效，始终为 1:1 ；
2、增加一个 reset.css 文件，放到 assets文件夹下面的styles文件夹中，重置样式表，在不同的手机浏览中，样式不统一，reset.css用于保证所有浏览器中默认显示效果都为一致；
3、增加 border.css，解决移动端多倍屏的一个1像素边框问题；
4、解决移动端点击事件延迟300ms的问题，在项目依赖中安装fastclick包
   在项目目录下执行命令：npm install fastclick --save
```


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
"# vue-qunar" 
