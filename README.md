jquery.downSelect-基于jquery的select插件
===================================
1、说明
-----------------------------------
基于jquery的下拉插件，支持单选多选，支持text模式和label模式显示，支持搜索，下拉样式支持两种样式。
2、引用
----------------------------------- 
```
在 head 中引用 jquery.downSelect.css.js 和 jquery.downSelect.css.css 
```
3、使用
----------------------------------- 
```
$('.selectEl').downSelect(options)
```
### options说明：
```
        data:  [{ 
                        "selected":false,
                        "name":"你好",
                        "id":"sel0"
                }, .... ],                             //  下拉框的数据
        limitCount: 2000,                              //  数据限制
        multipleMode: 'label',                         //  选择框内展示的模式  'label'或‘text’
        clear: true,                                   //  是否显示 clear
        radioMode: true,                               // 下拉的模式
        choice: function(xxxx, event) {                // 选择的回调  
          console.log(xxxx, this);
        },
        del: function(){                               //  删除时候的回调
              console.log('删除了');
        }
```

### 演示地址
[点击查看](http://wshome.bid/main/jquery.downSelect/)
