- 王野/男/1995
- 工作年限：1年 
- 技术博客：http://nsxxs.com
- 手机：18315804678
- Email：w258765@gmail.com 
- QQ：3315510010
    
## 技能清单
(以下均熟练使用且有实际项目经验)
- Web开发：前端/PHP
- 前端框架：Vue/React
- Web框架：Laravel/ThinkPHP
- 并发与缓存：Swoole/Redis
- 数据库相关：MySQL/MongoDB
- 开发工具：Vim/Webstorm/PHPstorm
- 版本管理、文档和自动化部署工具：Svn/Git/Composer/Npm/Jspm



## 工作经历 


### 青岛艾玛科技公司--前端（ 2016年5月 ~ 2018年3月 ）


#### 1.海信广场WEB账务系统

此项目为TP5框架开发的海信广场内部员工管理所有账务系统的web管理系统(PC,H5)，该项目中我负责部长API开发，前端框架采用的探讨，还有经理对员工提交财报的订单API编写与接口文档编写。该web功能为四个不同role：物流，导购，经理，部长，并且四个role每个人身份不同功能不同，所以在此项目中我使用t5的cache缓存进行身份判定，与前端vue-router配合实现不同权限角色访问相同地址出现不同页面效果。并且使用AUTH进行权限管理。在与数据库查询中处理了大量关联字段，多角色多部门进行不同筛选，由上级到下级运用一对多与多对多关联并进行权限控制。最严重的是出现了代码冗余，编写了大量API，但是重复功能接口太多，让我学到了必须严格按照面向对象编程，杜绝重复造轮子。并且在前端框架中进行产品探讨在iview,vux,easyui选择了easy-table，最终实现了Excel的web可视化，并且可以将web文件完美导出为excel表格。 

#### 2.青岛车联车APP

此项目为汽车在线救助维修服务项目，我负责登录注册模块，救援模块api接口开发与数据库索引优化。由于该项目需要多车主即时通讯，在救援模块的位置模拟与车主直接消息中使用了swoole的websocket工具，用户之间通过uid为索引与聊天室表关联，消息一经发送直接根据推送给所有位于同一聊天频道的前端用户。并且将用户UID使用redis缓存存储到队列中，加快获取聊天室数据。
在此项目中由对swoole有了基本的掌握，即时通讯与处理高并发方面又有了新的进展，并且更快的找到解决方案。并且在数据库优化方面有了新的认识，比如用约束数据库查询结果进行规范返回，多表关联优化等。

#### 3.山楂爱车小程序

此项目为青岛山楂爱车公司的微信小程序，微信汽车配件服务商城项目，我负责了对接微信login与pay接口。还有order接口编写。框架采用tp5,并且经过探讨前端用MPVUE语言替代小程序母语。在对接微信api过程中，多次发生于微信api没有请求成功浪费时间在与前端交流中。最终封装了一个集登录，支付，下单等为一体的简单测试小程序接口,大大提高了效率。减少了前后端交流的成本。在订单支付中，关于下单后商品失效问题产生了意见分歧，但是考虑到技术难度与成本，最终选择了以库存为中心的生成订单方式而非倒计时方式。在编写完成了自身任务的小程序接口后，加入到了前端开发中，并且建议团队采用美团mpvue小程序框架。mpvue由将小程序语法集成到了vue，解决了对小程序语法的生疏问题，大大提高了开发效率。


#### 4.海购乐乐微信公众号商城

此项目为海购广场的微信公众号商城项目，我负责该项目接口二次开发与前端开发。该项目为二次开发，最初使用laravel框架，接口已经趋于完善，但是上个程序员编写习惯不利于二次开发，我在此项目中对以往代码进行了优化。使用面向对象的方法将公用的api统一，将不同的api进行分离。将原有的Jquery前端渲染方式改为Vue，经过探讨选择element-ui为基本框架进行开发，对实现商城收藏，添加购物车等功能的无刷新触发起到了重要作用。



      
### 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
      
