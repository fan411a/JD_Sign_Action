1

## 介绍

1

*  自定义：.github/workflows/work.yaml 编辑

## 注意问题

> **问题一：[项目Fork后定时任务没有执行](https://github.com/ZHDeveloper/JD_Sign_Action/issues/3)**

> 
>  



## 使用用法
* 点击右上角 `Fork` 项目；
* `Settings` -> `Secrets` 中添加京东Cookie、Server酱SCKEY；
	- `JD_COOKIE`：账号1Cookie
	- `JD_DUAL_COOKIE`：账号2Cookie(选填)
	- `PUSH_KEY`：Server酱SCKEY
* 点击`Star`，任务会自动执行，运行进度和结果可以在`Actions`页面查看；
* 当任务运行完成时，会将运行结果和错误信息打包到`Artifacts`，可自行下载查看；
* 如果配置了Server酱，运行结果会推送到微信；


https://bean.m.jd.com/)；


## 获取Server酱SCKEY

* github 授权登录[Server酱](http://sc.ftqq.com/3.version)官网；
* 菜单栏`微信推送`扫描绑定微信；
* 菜单栏`发送消息`拷贝SCKEY；



## 效果截图

![WechatIMG3](./images/WechatIMG3.jpeg)

![WechatIMG4](./images/WechatIMG4.jpeg)


## 参考项目
* [NobyDa/Script/JD-DailyBonus](https://github.com/NobyDa/Script/blob/master/JD-DailyBonus/JD_DailyBonus.js)
* [ruicky/jd-sign-bot](https://github.com/ruicky/jd_sign_bot)
* [jerrykuku/luci-app-jd-dailybonus](https://github.com/jerrykuku/luci-app-jd-dailybonus)
