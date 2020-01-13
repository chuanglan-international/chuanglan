# chuanglan international

253 international SMS API for cloud communication

## Interface specification

Notes on SMS access：
1. API account and password parameters shall be provided by us
2. If you need to push the status report, please provide the callback address to bind our operation personnel (the mass delivery interface does not support status push at present).
3. Only HTTP POST request mode is supported
4. The encoding is unified using utf-8
5. The request header content-type must be set correctly according to the interface requirements, otherwise it may cause parameter passing errors
6. SMS content signature is not mandatory, some countries can be empty, please consult the operation personnel
7. The mobile phone number format is area code + real mobile phone number, for example, China area code is 86, example: 861888888888888

## 目录

 1. [message issued](englishAPI/messageIssued.md)
 1. [查询余额](docs/queryBalance.md)
 1. [回调状态](docs/callBack.md)
 1. [上行推送](docs/upwardPush.md)
 1. [短信群发（json）](docs/groupMessaging.md)
 1. [语音验证码](docs/voiceVerificationCode.md)
 1. [拉取上行短信明细](docs/pullDetail.md)
 1. [拉取状态报告](docs/pullCallback.md)
 1. [状态码](docs/statusCode.md)