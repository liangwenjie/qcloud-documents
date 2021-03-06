## 1. 接口描述
域名:monitor.api.qcloud.com
接口名:UnbindAlarmRuleReceivers

为告警规则解绑接收组

## 2. 输入参数
| 参数名称 | 必选  | 类型 | 描述 |来源|
|---------|---------|---------|---------|---------|
| Action | 是 | String | 操作接口名|系统规定参数，此处取值：UnbindAlarmRuleReceivers|
| alarmRuleId | 是 | String | 告警规则ID|调用<a href="/doc/api/255/查询告警规则" title="查询告警规则">查询告警规则</a>(DescribeAlarmRuleList)接口查询|


## 3. 输出参数
| 参数名称 | 类型 | 描述 |
|---------|---------|---------|
| code | Int | 错误码, 0: 成功, 其他值: 失败|
| message | String | 错误信息|


## 4. 示例
输入
```
https://monitor.api.qcloud.com/v2/index.php?Action= UnbindAlarmRuleReceivers
&alarmRuleId=policy-f3h1bxvcsb&COMMON_PARAMS
```
输出
```
{
    "code":"0",
    "message":"",
}
```

