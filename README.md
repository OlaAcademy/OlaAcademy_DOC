
### 欧拉学院

工作模块 | 工作项 | 端口编号 
------ | ------ | ------ | -------- | ------- | ------- 
用户 | | | | |
* | :one:用户登陆 | /user/[login](./interface/login.md) 
* | :one:登出 |  /user/[loginOut](./interface/loginOut.md) 
* | :one:用户注册 | /user/[reg](./interface/reg.md) 
* | :one:获取短信验证码 | /user/[getYzmByPhone](./interface/getYzmByPhone.md) 
* | :one:根据id修改用户信息 | /user/[update](./interface/update.md)
* | :one:根据id查询用户的信息 | /user/[queryUser](./interface/queryUser.md)
* | :one:修改密码 | /user/[modifypasswd](./interface/modifypasswd.md) 
* | :one:上传图片 | /user/[fileUpload](./interface/fileUpload.md)
首页 | | | | |
* | :one:首页列表 | /home/[getHomeList](./interface/getHomeList.md)
* | :one:资料列表 | /material/[getMaterialList](./interface/getMaterialList.md)
* | :one:更新浏览量 | /material/[updateMaterialCount](./interface/updateMaterialCount.md)
* | :one:解锁资料 | /exchange/[unlockMaterial](./interface/unlockMaterial.md) 
* | :one:机构及学校信息 | /organization/[getOrganizationInfo](./interface/getOrganizationInfo.md)
* | :one:报名 | /organization/[checkin](./interface/checkin.md)
直播 | | | | |
* | :one:直播 | /broadcast/[getBroadcastList](./interface/getBroadcastList.md)
消息 | | | | |
* | :one:友盟推送 | /message/[umeng_push](./interface/umeng_push.md)
*(老版本) | :one:未读消息数 | /message/[getUnreadCount](./interface/getUnreadCount.md)
* | :one:未读消息数 | /message/[getUnreadTotalCount](./interface/getUnreadTotalCount.md)
* | :one:评论消息列表 | /comment/[getCircleMessageList](./interface/getCircleMessageList.md) 
* | :one:点赞列表 | /circle/[getPraiseList](./interface/getPraiseList.md) 
* | :one:系统消息列表 | /message/[getMessageList](./interface/getMessageList.md) 
* | :one:系统消息标记为已读 | /message/[addMessageRecord](./interface/addMessageRecord.md)
考点 | | | | |
* | :one:课程列表 | /cour/[getCourList](./interface/ola_getCourList.md) 
* | :one:知识点对应的考点试题 | /cour/[getPoiSubList](./interface/ola_getPoiSubList.md)
* | :one:知识点详情 | /cour/[getPointDetail](./interface/getPointDetail.md) 
* | :one:提交测试题的答案 | /cour/[checkAnswer](./interface/checkAnswer.md) 
* | :one:获取试题答案 | /cour/[getSubjectAnswer](./interface/ola_getSubjectAnswer.md)
* | :one:获取试题提示 | /cour/[getSubjectAnswer](./interface/ola_getSubjectHint.md)
* | :one:知识点对应的视频 | /cour/[getVideoByPoi](./interface/ola_getVideoByPoi.md) 
作业 | | | | |
* | :one:创建群 | /homework/[createGroup](./interface/createGroup.md)
* | :one:老师创建的群列表 | /homework/[getTeacherGroupList](./interface/getTeacherGroupList.md) 
* | :one:学生群列表 | /homework/[getUserGroupList](./interface/getUserGroupList.md) 
* | :one:加入／退出群 | /homework/[attendGroup](./interface/attendGroup.md)
* | :one:群成员列表 | /homework/[queryGroupMember](./interface/queryGroupMember.md) 
* | :one:发布作业 | /homework/[deployHomework](./interface/deployHomework.md) 
* | :one:作业列表 | /homework/[getHomeworkList](./interface/getHomeworkList.md)
* | :one:作业完成情况 | /homework/[getHomeworkStatistics](./interface/getHomeworkStatistics.md) 
* | :one:题目列表 | /homework/[getSubjectList](./interface/getSubjectList.md) 
模考 | | | | |
* | :one:真题／模考列表 | /exam/[getExamList](./interface/ola_getExamList.md) 
* | :one:真题／模考对应的试题 | /exam/[getExamSubList](./interface/ola_getExamSubList.md) 
欧拉币兑换 | | | | |
* | :one:解锁题目 | /exchange/[unlockSubject](./interface/unlockSubject.md) 
视频 | | | | |
* | :one:首页banner | /cour/[getBannerList](./interface/getBannerList.md) 
* | :one:课程列表 | /cour/[getCourList](./interface/ola_getCourList.md) 
* | :one:获取课程视频 | /cour/[getVideoByPoi](./interface/ola_getVideoByPoi.md)
* | :one:收藏／取消收藏视频 | /collection/[collectionVideo](./interface/collectionVideo.md)
* | :one:机构列表 | /organization/[getAllOrganization](./interface/ola_getAllOrganization.md)
* | :one:获取整套视频或题库 | /goods/[getGoodsList](./interface/getGoodsList.md)
* | :one:获取整套视频下的视频列表 | /goods/[getVideoList](./interface/getVideoList.md)
* | :one:获取整套视频购买状态 | /goods/[getOrderStatus](./interface/getOrderStatus.md)
* 欧拉圈| | | | |
* | :one:(旧版本)视频观看历史列表 | /cour/[getHistoryList](./interface/ola_getHistoryList.md) 
* | :one:上传图片 | /SDpic/common/[picUpload](./interface/picUpload.md)
* | :one:欧拉圈发帖 | /circle/[addOlaCircle](./interface/addOlaCircle.md)
* | :one:欧拉圈列表 | /circle/[getCircleList](./interface/getCircleList.md)
* | :one:帖子详情 | /circle/[queryCircleDetail](./interface/queryCircleDetail.md)
* | :one:帖子点赞 | /circle/[praiseCirclePost](./interface/praiseCirclePost.md)
* | :one:添加评论 | /comment/[addComment](./interface/addComment.md)
* | :one:评论列表 | /comment/[getCommentList](./interface/getCommentList.md)
* | :one:个人页面 | /circle/[getUserPostList](./interface/getUserPostList.md)
* 好友关注| | | | |
* | :one:关注／取消关注 | /attention/[attendUser](./interface/attendUser.md)
* 每日签到 分享| | | | |
* | :one:获取今日签到状态 | /dailyact/[getCheckinStatus](./interface/getCheckinStatus.md) 
* | :one:签到 | /dailyact/[checkin](./interface/checkin.md) 
* | :one:分享 | /dailyact/[share](./interface/share.md) 
* | :one:欧拉币明细 | /coin/[getHistoryList](./interface/getHistoryList.md) 
* 我的| | | | |
* | :one:知识型谱(旧版) | /cour/[getStatisticsList](./interface/getStatisticsList.md)
* | :one:错题集列表 | /cour/[getWrongList](./interface/getWrongList.md)
* | :one:错题集 | /cour/[getWrongSubSet](./interface/getWrongSubSet.md) 
* | :one:更新错题集 | /cour/[updateWrongSet](./interface/updateWrongSet.md) 
* | :one:视频收藏列表 | /collection/[getCollectionByUserId](./interface/getCollectionByUserId.md) 
* | :one:购买视频列表 | /goods/[getBuyGoodsList](./interface/getBuyGoodsList.md) 
* 支付 | | | | |
* | :one:VIP价格 | /pay/[getVIPPrice](./interface/getVIPPrice.md) 
* | :one:微信支付信息 | /pay/[getWXPayReq](./interface/getWXPayReq.md) 
* | :one:支付宝支付信息 | /pay/[getAliOrderInfo](./interface/getAliOrderInfo.md)
