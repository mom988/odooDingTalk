# Odoo12系统集成钉钉  12.0-v2

> 本应用基于OdooERP12开发，支持社区版和企业版** 
> 
> -----------------------------------------------------------------------------
> **特别提示：禁止任何单位和个人二次修改后转售、再发版、用于商业用途，自用可随意修改！**
>
> **特别提示：禁止任何单位和个人二次修改后转售、再发版、用于商业用途，自用可随意修改！**
>
> **特别提示：禁止任何单位和个人二次修改后转售、再发版、用于商业用途，自用可随意修改！**
>
> -----------------------------------------------------------------------------
> 
> 在使用本模块前，请先将钉钉中你创建的E应用或微应用权限放开和配置出口ip，得到钉钉应用的 **AppKey**和 **AppSecret**， 至于钉钉后台中的配置请参照：>https://open-doc.dingtalk.com/microapp/bgb96b 
>
> 博客地址： https://sxfblog.com/index.php/archives/371.html
> 
> QQ群：1019231617 欢迎加入群交流、共同完善和拓展模块功能
>
> 请在测试环境中测试！！！

### 安装依赖：文件`requirements.txt`中

```ssh
pip3 install -r requirements.txt
```

#### 安装方式，在应用列表中(先刷新模块列表)，搜索`dingding_base`应用，安装即可，安装完成后记得给用户设置权限，否则界面上没有图标

### 如何安装钉钉审批
#### 1. 可通过钉钉设置项中直接选择需要的审批模块，比如出勤休假，勾选后点击保存即可
#### 2. 或直接在应用中搜索`dingding`, 按分类进行查找即可看到钉钉的所有模块，按需安装

**模块列表**

| 模块名            | 模块功能                                                 |
| ----------------- | ------------------------------------------------------ |
| dingding_attendance         | 钉钉考勤（自动安装）                            |
| dingding_attendance_ext     | 钉钉考勤拓展，支持钉钉考勤导入odoo原生出勤         |
| dingding_base               | 钉钉主模块，一般只需安装这个模块就好了             |
| dingding_hrm                | 钉钉智能人事模块（自动安装）                      |
| dingding_message            | 钉钉消息模块（自动安装）                         |
| oa_base                     | 钉钉审批基础模块（按需安装）                      |
| oa_leave_attendance         | 钉钉审批出勤休假模块                             |
| oa_personnel_admin          | 钉钉审批行政人事模块                             |
| oa_odoo_form                | 钉钉审批-odoo表单提交审批模块，支持采购询价单发送到钉钉审批 |
| oa_stock                    | 钉钉审批-库存模块（定制）                         |
| odoo_interface_api          | 开放第三方接口（供小程序、其他应用调用使用）         |
| odoo_performance_manage     | 绩效管理模块（可独立使用或配合钉钉使用、免费版）     |
| odoo_wage_manage            | 薪酬管理模块（可独立使用或配合钉钉使用、免费版）     |
| web_progress                | 第三方进度条模块（自动依赖模块）                   |
| ----------------- | ------------------------------------------------------ |


