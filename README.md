﻿jquery.downSelect-基于jquery的select插件
===================================
1、引用
----------------------------------- 
在head中引用jquery.downSelect.css.js和jquery.downSelect.css.css
2、使用
----------------------------------- 
与其它使用jquery的方法一样：$(ele).creatTips(parms)，参数说明如下：
### parms说明：<br>
    post: "bottomRight" , 		//位置(暂时不支持) 四个角  topLeft,topRight,bottomLeft,bottomRight
    gurl: "#" ,           		//跳转链接,非空是gword也不能为空
    gword: "",			   		//加链接文字，只有在添加了广告链接时有效果
    status: "info" ,    		//状态，succeed,error,info,warm
    close: 0 ,             		//自动关闭时间，为0时不自动关闭，单位为秒
    anitime:"500" ,				//关闭动画时间
    title:"提示" ,				//tips标题
    content:"操作成功" ,		//消息标题
    detail:"你的操作已成功" ,	//消息详情
    height:200,					//消息框高
    width:360,					//消息框宽
    remark:"",					//备注信息
    cbtype:"",					//触发回调的方式，auto、click、all、空,空不调用
    cbfun:function(idx){}		//回调,参数为当前的消息索引

### 演示地址
[点击查看](http://wslover.byethost11.com/others/tips/)
