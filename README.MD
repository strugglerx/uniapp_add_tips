

# uniapp 添加我的小程序 懒人组件

提示添加我的小程序 懒人组件，使用环境为 `uni-app`。  
  

## 如何获取
github仓库: [https://github.com/strugglerx/uniapp_add_tips](https://github.com/strugglerx/uniapp_add_tips)  
  
## props
| 参数|描述|类型|默认值|
|--|--|--|--|
|tip|提示|string|	点击「添加小程序」，下次访问更便捷|
|duration|显示时间（单位s）|number|5|

## 如何使用
*.vue
```html
<add-tip :tip="tip" :duration="duration"/>
```
  
```javascript
	import addTip from "../../components/uni-add-tips/uni-add-tips"
	export default {
		data() {
			return {
                tip:"我是提示",
                duration:1
			}
		},
		components:{
			addTip
		}
	}
```
  
## 实际效果

![](https://github.com/strugglerx/uniapp_add_tips/blob/master/example.jpg?raw=true)



## 反馈问题
如在使用中发现bug或有优化的建议和意见，请发邮件 <str@li.cm> 或在 [gitHub](https://github.com/strugglerx/uniapp_add_tips) 上反馈。

vx:strongdreams
  
## 更新日志

2019.6.3 *v0.0.2*  返回主页修改为switchTab 

2019.6.1 *v0.0.1*  创建本插件  
  