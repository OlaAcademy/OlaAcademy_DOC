# 个人主页
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /circle/getUserPostList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 |  所查询用户Id
 curUserId | 否 | 字符串 |  当前登录用户Id
 
###返回结果示例
```javascript
{
    "message": "成功",
    "result": {
        "id": 381,
        "name": "欧拉技术支持",
        "avator": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
        "sign": "123",
        "phone": "13581574730",
        "attendStatus": 1,
        "attendNum": 0,
        "followerNum": 1,
        "deployList": [
            {
                "assignUser": "381",
                "commentNumber": 1,
                "content": "指定回答",
                "courseId": 0,
                "id": 13635,
                "imageGids": "d07f5b10-f8e5-4232-95cc-a9a823e51f4e,",
                "isPublic": 0,
                "location": "",
                "praiseNumber": 1,
                "readNumber": 14,
                "subject": "",
                "title": "指定回答",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-30 16:43:38"
            },
            {
                "assignUser": "",
                "commentNumber": 14,
                "content": "测试你的时候才能更加考察你的时候我们就算了。我也好的",
                "courseId": 0,
                "id": 13628,
                "imageGids": "80f41589-9ccf-45a6-a0f4-84e5689ea7ec,f839fe3d-b361-46e3-aaeb-ad385ead6aab,24096950-71ed-4cd4-9f79-3e4b55678c7c,17b1e477-90dc-4e0e-b6c2-a374e46a18ef,95dd60b6-e66d-4046-a9bf-620b3a3b26f8,87713ef3-07be-42cd-ba61-b462c21eb2de",
                "isPublic": 1,
                "location": "",
                "praiseNumber": 5,
                "readNumber": 419,
                "subject": "",
                "title": "测试",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-25 12:38:11"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "测试",
                "courseId": 0,
                "id": 13616,
                "imageGids": "477d80a3-abc0-402d-92bf-ab9c530e22ba",
                "isPublic": 1,
                "location": "",
                "praiseNumber": 2,
                "readNumber": 132,
                "subject": "",
                "title": "测试",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-11 11:02:48"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "胜利油田临盘采油管理",
                "courseId": 0,
                "id": 13614,
                "imageGids": "2ff286b4-84e7-4dd7-911d-57fc95d27303",
                "isPublic": 0,
                "location": "",
                "praiseNumber": 1,
                "readNumber": 11,
                "subject": "",
                "title": "测试",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-11 10:47:47"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "测试结果表明的立场上",
                "courseId": 0,
                "id": 13613,
                "imageGids": "4c4deb5e-7059-45e7-afbe-1751ea5e05e9",
                "isPublic": 1,
                "location": "",
                "praiseNumber": 1,
                "readNumber": 35,
                "subject": "",
                "title": "测试",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-11 10:45:04"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "管理后台优化\n管理后台目前还存在易用性问题，下周根据产品组所提需求对管理后台功能进行优化完善管理后台优化\n管理后台目前还存在易用性问题，下周根据产品组所提需求对管理后台功能进行优化完善管理后台优化",
                "courseId": 0,
                "id": 13612,
                "imageGids": "",
                "isPublic": 1,
                "location": "",
                "praiseNumber": 1,
                "readNumber": 13,
                "subject": "",
                "title": "测试",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-11 10:42:55"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "测试",
                "courseId": 0,
                "id": 13611,
                "imageGids": "",
                "isPublic": 0,
                "location": "北京市海淀区",
                "praiseNumber": 1,
                "readNumber": 8,
                "subject": "",
                "title": "测试",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-02 11:30:48"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "测试",
                "courseId": 0,
                "id": 13610,
                "imageGids": "f396c545-dfc9-457a-bbbf-1e582f5a0452",
                "isPublic": 1,
                "location": "北京市西城区",
                "praiseNumber": 4,
                "readNumber": 142,
                "subject": "",
                "title": "测试",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-02 11:17:16"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "哈哈",
                "courseId": 0,
                "id": 13546,
                "imageGids": "728c4128-c9cb-4327-9027-c2c19e1c0d9c,",
                "isPublic": 1,
                "location": "北京市海淀区",
                "praiseNumber": 1,
                "readNumber": 1,
                "subject": "",
                "title": "哈哈",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-11-21 15:24:00"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "哈哈",
                "courseId": 0,
                "id": 13544,
                "imageGids": "3c85c92b-e366-4d14-a1eb-3f4a020838ee,",
                "isPublic": 1,
                "location": "北京市海淀区",
                "praiseNumber": 1,
                "readNumber": 1,
                "subject": "",
                "title": "哈哈",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-11-21 15:19:22"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "测试",
                "courseId": 0,
                "id": 13540,
                "imageGids": "35e37042-fafc-4362-8fcc-71cfffd500fc,",
                "isPublic": 1,
                "location": "北京市海淀区",
                "praiseNumber": 1,
                "readNumber": 1,
                "subject": "",
                "title": "测试",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-11-21 15:13:44"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "测试",
                "courseId": 0,
                "id": 13539,
                "imageGids": "5c326b2b-18fd-48f2-9f48-94fc904b1d58,",
                "isPublic": 1,
                "location": "北京市海淀区",
                "praiseNumber": 1,
                "readNumber": 1,
                "subject": "",
                "title": "测试",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-11-21 15:12:57"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "测试",
                "courseId": 0,
                "id": 13538,
                "imageGids": "f838b8d6-1d33-48bf-87b6-8aed6d237f5d,",
                "isPublic": 1,
                "location": "北京市海淀区",
                "praiseNumber": 1,
                "readNumber": 1,
                "subject": "",
                "title": "测试",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-11-21 15:11:43"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "考试怎样才能不紧张",
                "courseId": 0,
                "id": 4778,
                "imageGids": "",
                "isPublic": 1,
                "location": "北京市海淀区",
                "praiseNumber": 101,
                "readNumber": 49,
                "subject": "",
                "title": "考试怎样才能不紧张",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-09-06 11:57:17"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "路过咖啡厅，看见一个人在看视频学习，突然感觉好眼熟，仔细一看，原来是用欧拉联考学习",
                "courseId": 0,
                "id": 4233,
                "imageGids": "",
                "isPublic": 1,
                "location": "北京市朝阳区",
                "praiseNumber": 13,
                "readNumber": 18,
                "subject": "",
                "title": "路过咖啡厅，看见一个人在看视频学习，突然感觉好眼熟，仔细一看，原来是用欧拉联考学习",
                "type": 2,
                "userId": 381,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-09-01 18:35:02"
            }
        ],
        "replyList": [
            {
                "assignUser": "",
                "commentNumber": 6,
                "content": "123",
                "courseId": 0,
                "id": 13651,
                "imageGids": "",
                "isPublic": 1,
                "location": "",
                "praiseNumber": 1,
                "readNumber": 8,
                "subject": "数学",
                "title": "123",
                "type": 2,
                "userId": 754,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2017-02-13 16:48:11"
            },
            {
                "assignUser": "381",
                "commentNumber": 11,
                "content": "指定回答",
                "courseId": 0,
                "id": 13636,
                "imageGids": "5bbf52d3-b3e8-4a6f-838f-032262984e4b,",
                "isPublic": 1,
                "location": "",
                "praiseNumber": 1,
                "readNumber": 154,
                "subject": "",
                "title": "指定回答",
                "type": 2,
                "userId": 1292,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-30 16:47:23"
            },
            {
                "assignUser": "",
                "commentNumber": 6,
                "content": "请输入内容…",
                "courseId": 0,
                "id": 13621,
                "imageGids": "ff07e0f3-3a72-49ea-ba17-a104b568b41a,4db3903e-bdd9-48a1-8ddc-7342d8964df2",
                "isPublic": 1,
                "location": "",
                "praiseNumber": 1,
                "readNumber": 290,
                "subject": "",
                "title": "请输入标题",
                "type": 2,
                "userId": 1017,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-13 16:34:07"
            },
            {
                "assignUser": "381",
                "commentNumber": 16,
                "content": "昨天客场惨败给灰熊之后，勇士今天又奔赴明尼苏达，进行与森林狼的背靠背较量。本场比赛帕楚利亚继续休战，之前轮休的伊戈达拉和受伤的鲁尼复",
                "courseId": 0,
                "id": 13620,
                "imageGids": "",
                "isPublic": 1,
                "location": "",
                "praiseNumber": 0,
                "readNumber": 229,
                "subject": "",
                "title": "测试哦",
                "type": 2,
                "userId": 1292,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-12 17:24:50"
            },
            {
                "assignUser": "381",
                "commentNumber": 0,
                "content": "测试",
                "courseId": 0,
                "id": 13615,
                "imageGids": "",
                "isPublic": 0,
                "location": "",
                "praiseNumber": 1,
                "readNumber": 10,
                "subject": "",
                "title": "测试",
                "type": 2,
                "userId": 754,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-12-11 10:54:12"
            },
            {
                "assignUser": "381",
                "commentNumber": 0,
                "content": "原图",
                "courseId": 0,
                "id": 13609,
                "imageGids": "af60d0fb-3f43-4f32-b3ce-a3d6b890e365,",
                "isPublic": 0,
                "location": "北京市海淀区",
                "praiseNumber": 2,
                "readNumber": 43,
                "subject": "",
                "title": "原图",
                "type": 2,
                "userId": 1292,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-11-26 12:26:10"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "如何删除已下载的视频？",
                "courseId": 0,
                "id": 8623,
                "imageGids": "",
                "isPublic": 1,
                "location": "ZhengzhouXinzheng",
                "praiseNumber": 1,
                "readNumber": 82,
                "subject": "",
                "title": "如何删除已下载的视频？",
                "type": 2,
                "userId": 1967,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-10-03 22:33:58"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "欧拉版本已升级，解决IOS10适配、视频播放错误以及体验优化等功能，感谢小伙伴对我们的支持！",
                "courseId": 0,
                "id": 8074,
                "imageGids": "",
                "isPublic": 1,
                "location": "",
                "praiseNumber": 10,
                "readNumber": 110,
                "subject": "",
                "title": "欧拉版本已升级，解决IOS10适配、视频播放错误以及体验优化等功能，感谢小伙伴对我们的支持！",
                "type": 2,
                "userId": 517,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-09-29 23:55:22"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "下载失败的视频怎么删掉？",
                "courseId": 0,
                "id": 6796,
                "imageGids": "b18c6d16-8a21-4daa-81d8-7127ca1324a6",
                "isPublic": 1,
                "location": "",
                "praiseNumber": 1,
                "readNumber": 38,
                "subject": "",
                "title": "下载失败的视频怎么删掉？",
                "type": 2,
                "userId": 1777,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-09-20 20:25:14"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "为什么我是会员，还很多课程没办法看呢\n",
                "courseId": 0,
                "id": 6784,
                "imageGids": "",
                "isPublic": 1,
                "location": "厦门市集美区",
                "praiseNumber": 2,
                "readNumber": 48,
                "subject": "",
                "title": "为什么我是会员，还很多课程没办法看呢\n",
                "type": 2,
                "userId": 791,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-09-20 19:28:40"
            },
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "为什么一点我的下载那就闪退了呢？一直这样，不能下载视频",
                "courseId": 0,
                "id": 6779,
                "imageGids": "",
                "isPublic": 1,
                "location": "郑州市管城回族区",
                "praiseNumber": 3,
                "readNumber": 22,
                "subject": "",
                "title": "为什么一点我的下载那就闪退了呢？一直这样，不能下载视频",
                "type": 2,
                "userId": 1639,
                "videoId": 0,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "time": "2016-09-20 19:01:21"
            }
        ]
    },
    "apicode": 10000
}
