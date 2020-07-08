# less-plugin-px2rem

Less plugin for convert px to rem units  
一个用于将px单位转换为rem单位的less插件

## install 安装

```
npm i -g less-plugin-px2rem
```

## usage 使用
```
lessc filename.less --px2rem
```
You can set the ratio of rpx to rem (default 100).  
你可以设置转换的比例（默认值为100）

```
lessc filename.less --px2rem=16
```
Use units 'PX' to no conversion.   
使用大写PX单位可不进行转换
```css
/* input */
.selector {
  width: 100px;
  height: 200PX;
}

/* output */
.selector {
  width: 1rem;
  height: 200PX;
}
```

## License
MIT