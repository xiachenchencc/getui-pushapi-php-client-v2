## 已支持的API列表
以下是消息推送功能与推送API的对应关系

| API类别      |      功能       | 调用的API名称                                              |
|-----------|-----------------|-----------------------------------------------------------|
| 鉴权API | [鉴权](https://docs.getui.com/getui/server/rest_v2/token/#0)              | 初始化GTClient会自动鉴权                                  |
| 鉴权API | [删除鉴权](https://docs.getui.com/getui/server/rest_v2/token/#1)           | GTUserApi.closeAuth                                 |
| 推送API | [cid单推](https://docs.getui.com/getui/server/rest_v2/push/#1)            | GTUserApi.pushToSingleByCid                     |
| 推送API | [别名单推](https://docs.getui.com/getui/server/rest_v2/push/#2)            | GTUserApi.pushToSingleByAlias                   |
| 推送API | [cid批量单推](https://docs.getui.com/getui/server/rest_v2/push/#3)         | GTUserApi.pushBatchByCid                        |
| 推送API | [别名批量单推](https://docs.getui.com/getui/server/rest_v2/push/#4)         | GTUserApi.pushBatchByAlias                      |
| 推送API | [tolist创建消息](https://docs.getui.com/getui/server/rest_v2/push/#5)      | GTUserApi.createListMsg                             |
| 推送API | [cid批量推](https://docs.getui.com/getui/server/rest_v2/push/#6)           | GTUserApi.pushListByCid                         |                  
| 推送API | [别名批量推](https://docs.getui.com/getui/server/rest_v2/push/#7)           | GTUserApi.pushListByAlias                       |                    
| 推送API | [群推](https://docs.getui.com/getui/server/rest_v2/push/#8)                | GTUserApi.pushAll                               |                                
| 推送API | [条件筛选用户推送](https://docs.getui.com/getui/server/rest_v2/push/#9)      | GTUserApi.pushByTag                             |                               
| 推送API | [标签快速推送](https://docs.getui.com/getui/server/rest_v2/push/#10)        | GTUserApi.pushByFastCustomTag                    |                                
| 推送API | [停止任务](https://docs.getui.com/getui/server/rest_v2/push/#11)            | GTUserApi.stopPush                              |            
| 推送API | [查询定时任务](https://docs.getui.com/getui/server/rest_v2/push/#12)        | GTUserApi.queryScheduleTask                      |     
| 推送API | [删除定时任务](https://docs.getui.com/getui/server/rest_v2/push/#13)        | GTUserApi.deleteScheduleTask                     |
| 统计API | [获取推送结果](https://docs.getui.com/getui/server/rest_v2/report/#1)       | GTStatisticsApi.queryPushResultByTaskIds          |                                    
| 统计API | [任务组名查报表](https://docs.getui.com/getui/server/rest_v2/report/#2)      | GTStatisticsApi.queryPushResultByGroupName        |
| 统计API | [单日推送数据](https://docs.getui.com/getui/server/rest_v2/report/#3)       | GTStatisticsApi.queryPushResultByDate             |
| 统计API | [单日用户数据接口](https://docs.getui.com/getui/server/rest_v2/report/#4)    | GTStatisticsApi.queryUserDataByDate               |
| 统计API | [24小时在线用户数](https://docs.getui.com/getui/server/rest_v2/report/#5)    | GTStatisticsApi.queryOnlineUserData              |
| 用户API | [绑定别名](https://docs.getui.com/getui/server/rest_v2/user/#1)             | GTUserApi.bindAlias                             |
| 用户API | [根据cid查询别名](https://docs.getui.com/getui/server/rest_v2/user/#2)       | GTUserApi.queryAliasByCid                       |
| 用户API | [根据别名查询cid](https://docs.getui.com/getui/server/rest_v2/user/#3)       | GTUserApi.queryCidByAlias                       |
| 用户API | [批量解绑别名](https://docs.getui.com/getui/server/rest_v2/user/#4)          | GTUserApi.unbindAlias                      |
| 用户API | [解绑所有别名](https://docs.getui.com/getui/server/rest_v2/user/#5)          | GTUserApi.unbindAllAlias                        |
| 用户API | [一个用户绑定一批标签](https://docs.getui.com/getui/server/rest_v2/user/#6)    | GTUserApi.setTagForCid                         |
| 用户API | [一批用户绑定一个标签](https://docs.getui.com/getui/server/rest_v2/user/#7)    | GTUserApi.batchModifyTagForBatchCid                         |
| 用户API | [一批用户解绑一个标签](https://docs.getui.com/getui/server/rest_v2/user/#8)    | GTUserApi.unbindTag                       |
| 用户API | [查询标签](https://docs.getui.com/getui/server/rest_v2/user/#9)              | GTUserApi.queryUserTag                        |
| 用户API | [添加黑名单用户](https://docs.getui.com/getui/server/rest_v2/user/#10)        | GTUserApi.addBlackUser                         |
| 用户API | [移除黑名单用户](https://docs.getui.com/getui/server/rest_v2/user/#11)        | GTUserApi.removeBlackUser                      |
| 用户API | [查询用户状态](https://docs.getui.com/getui/server/rest_v2/user/#12)          | GTUserApi.queryUserStatus                     |
| 用户API | [设置角标(仅支持IOS)](https://docs.getui.com/getui/server/rest_v2/user/#13)   | GTUserApi.setBadge                             |
| 用户API | [查询用户总量](https://docs.getui.com/getui/server/rest_v2/user/#14)          | GTUserApi.queryUserCount                            |

## 其他链接
[个推开发者平台](https://docs.getui.com/)
