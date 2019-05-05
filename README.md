# loadingview
> 网络请求正在加载框

## 文档
首先，把这个仓库下载/克隆到你的小程序目录，比如`/components/loadingview/`    
然后，在首页`index.json`配置文件中，引入该组件：
``` json
{
  "usingComponents": {
    "v-loadingview": "/components/loadingView/index"
  }
}
```
最后，在首页`index.wxml`文件中，调用该组件即可：
``` wxml
<v-loadingview/>
```

## 方法
你可以传递两个参数进行自定义操作：

### 1. bind:onCancel=自己page里写的方法名字
``` wxml
<v-loadingview bind:onCancel="onCancelFilm"/>
```

