# Summary

## 前序
* [简介](README.md)
* [注意事项](Preorder/attention.md)

## 方法和接口说明
* [DING](Ding/README.md)
    * [DING API开放](Ding/Ding_Api_Open.md)
* [轨迹服务](TrackService/README.md)
    * [外部服务查询用户轨迹](TrackService/GBS_TQ_QUTBI.md)
    * [查询用户轨迹](TrackService/GBS_TQ_QUT.md)
    * [外部服务停止轨迹上报](TrackService/GBS_T_StopTCBI.md)
    * [外部服务开启轨迹采集](TrackService/GBS_T_StartTCBI.md)
    * [isv或外部服务生成轨迹id](TrackService/GBS_T_GTIBI.md)
    * [接收轨迹数据](TrackService/GBS_T_RTD.md)
    * [停止轨迹上报](TrackService/GBS_T_STC.md)
    * [轨迹id生成](TrackService/GBS_T_GTI.md)
    * [获取轨迹推送失败消息](TrackService/BIP_R_FT.md)
    * [应用注销轨迹推送](TrackService/BIP_R_C.md)
    * [获取轨迹推送注册](TrackService/BIP_R_GE.md)
    * [应用更新轨迹推送事件数据](TrackService/BIP_R_UE.md)
    * [轨迹推送注册](TrackService/BIP_R_RA.md)
* [消息](Message/README.md)
    * [发送IM消息](Message/Im_Chat_Isv_SendMsg.md)
    * [创建群聊会话](Message/Im_Chat_Isv_CreatGroupChat.md)
* [业务事件回调](EventCallBack/README.md)
    * [移除失败回调](EventCallBack/Remove_CB_Failed.md)
    * [重试失败回调](EventCallBack/Retry_CB_Failed.md)
    * [查询回调失败信息](EventCallBack/Query_CB_Failed.md)
    * [删除事件回调的定义信息](EventCallBack/Delete_E_CB_Define.md)
    * [更新事件回调的定义信息](EventCallBack/Update_E_CB_Define.md)
    * [查询定义的事件列表](EventCallBack/Query_CB_Define.md)
    * [注册消息回调](EventCallBack/Register_E_CB.md)
    * [注册消息回调(支持加密,签名)](EventCallBack/V2_Register_E_CB.md)
* [JSAPI鉴权](JSAPI/README.md)
    * [get_jsapi_token.json](JSAPI/Get_Jsapi_Token.md)
* [文件存储](FileStorage/README.md)
    * [媒体文件下载](FileStorage/MediaDownload.md)
* [日程](Schedule/README.md)
    * [取消日历事件](Schedule/CancelCalendar.md)
    * [创建日历事件](Schedule/CreateCalendar.md)
* [待办](Todo/README.md)
    * [取消实例接口](Todo/PackageCancel.md)
    * [关闭实例接口](Todo/PackageClose.md)
    * [取消待办接口](Todo/TaskCancel.md)
    * [完成待办接口](Todo/TaskFinish.md)
    * [创建待办接口V2](Todo/TaskCreate.md)
* [工作通知消息](Notification/README.md)
    * [工作通知](Notification/WorkNotification.md)
    * [发送工作台红点](Notification/SendPortalNotification.md)
    * [清除工作台红点](Notification/ClearPortalNotification.md)
    * [查询工作台红点](Notification//QueryPortalNotification.md)
* [获取通讯录部门信息](AddressBookDeptInfo/README.md)
    * [移动组织](AddressBookDeptInfo/MoveGovOrganization.md)
    * [删除组织](AddressBookDeptInfo/DeleteGovOrganization.md)
    * [更新组织](AddressBookDeptInfo/UpdateGovOrganization.md)
    * [创建组织](AddressBookDeptInfo/CreateGovOrganization.md)
    * [根据组织Code列表查询详情](AddressBookDeptInfo/ListOrganizationsByCodes.md)
    * [根据组织查询组织汇报线](AddressBookDeptInfo/GetOrganizationLine.md)
    * [分页查询组织下的员工Code](AddressBookDeptInfo/PageOrganizationEmployeeCodes.md)
    * [根据组织code查询详情](AddressBookDeptInfo/GetOrganizationByCode.md)
    * [分页获取下一级组织Code列表](AddressBookDeptInfo/PageSubOrganizationCodes.md)
    * [获取租户根组织](AddressBookDeptInfo/GetRootOrganization.md)
    * [分页获取下一级行政区划列表](AddressBookDeptInfo/PageSubGovDivisions.md)
    * [根据行政区划查询行政区划线](AddressBookDeptInfo/GetDivisionLine.md)
    * [根据行政区划Code列表查询](AddressBookDeptInfo/ListDivisionsByCodes.md)
    * [分页获取下一级条线列表](AddressBookDeptInfo/PageSubGovBusinessStrips.md)
    * [根据条线查询条线线](AddressBookDeptInfo/GetGovBusinessStripLine.md)
    * [根据条线Code列表查询](AddressBookDeptInfo/ListGovBusinessStripsByCodes.md)
* [获取通讯录用户信息](AddressBookUserInfo/README.md)
    * [冻结和解冻账号](AddressBookUserInfo/UpdateGovAccountStatus.md)
    * [根据员工Code获取员工标签Code列表](AddressBookUserInfo/ListEmployeeTags.md)
    * [删除员工的任职](AddressBookUserInfo/DeleteGovEmployeePosition.md)
    * [更新员工的任职](AddressBookUserInfo/UpdateGovEmployeePosition.md)
    * [删除员工](AddressBookUserInfo//DeleteGovEmployee.md)
    * [失效员工](AddressBookUserInfo/DeactivateGovEmployee.md)
    * [修改员工](AddressBookUserInfo/UpdateGovEmployee.md)
    * [创建员工的任职](AddressBookUserInfo/CreateGovEmployeePosition.md)
    * [新增员工](AddressBookUserInfo/CreateGovEmployee.md)
    * [根据组织Code,员工Code列表,批量获取员工在该组织的任职](AddressBookUserInfo/ListOrgEmployeePositionsByCodes.md)
    * [根据员工Code列表查询详情](AddressBookUserInfo/ListEmployeesByCodes.md)
    * [根据员工Code获取员工的任职](AddressBookUserInfo/ListEmployeePositionsByEmployeeCode.md)
    * [根据员工Code查询详情](AddressBookUserInfo/GetEmployeeByCode.md)
    * [通过员工Code列表获取员工账号ID](AddressBookUserInfo/ListEmployeeAccountIds.md)
    * [批量根据accountId、tenantId、organizationCode查询这个账号是否在这个租户的这些组织内](AddressBookUserInfo/ListAccountOrgByIdAndCodes.md)
    * [人员返聘](AddressBookUserInfo/RehiredGovEmployee.md)
    * [根据组织code和批量员工Code获取员工的邮箱信息](AddressBookUserInfo/ListGovOrgEmployeeEmailByCodes.md)
    * [批量通过账号Id列表获取人员Code](AddressBookUserInfo/ListGovEmployeeCodesByAccountIds.md)
    * [查询映射关系通过数梦Id](AddressBookUserInfo/GetEmpCodeByDtUserId.md)
    * [查询映射关系通过钉钉id](AddressBookUserInfo/GetEmpCodeByDingUserId.md)
    * [根据手机号码获取人员编码](AddressBookUserInfo/GetByMobile.md)
* [企业内应用免登](NotLogin/README.md)
    * [根据authCode获取登录token](NotLogin/DingTalk_App_Token.md)
    * [根据authCode换取用户信息](NotLogin/DingTalk_App_User.md)
    * [获取应用access_token](NotLogin/Get_Token.md)

## 最后
* [致谢](TheEnd/ThanksFor.md)

