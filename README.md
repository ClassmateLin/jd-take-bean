# jd_take_bean

## 简介

京东首页->领京豆

## 安装

[Release](https://github.com/ClassmateLin/jd-take-bean/releases)下载.

## 使用

多个cookie用&分隔, remark为可选, 用于备注账号。

- 方式一:

```bash
export JD_COOKIE="pt_pin=xxx;pt_key=xxx;remark=账号1;&pt_pin=sfafa;pt_key=sfafaf;";
export RUST_LOG=info;
```

```bash
./jd_take_bean
```

- 方式二:

创建.env文件, 在文件中写入:

```env
RUST_LOG=info;
JD_COOKIE="pt_pin=xxx;pt_key=xxx;&pt_pin=sfafa;pt_key=sfafaf;remark=xx的账号;";
```

```bash
./jd_take_bean
```



## 其他脚本

- [东东农场](https://github.com/ClassmateLin/jd-farm.git)

- [丘大叔签到](https://github.com/ClassmateLin/uncle-qiu-sign-in)

## 免责声明

本仓库发布的脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。

本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。

本人对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害。

间接使用脚本的任何用户在某些行为违反国家/地区法律或相关法规的情况下进行传播, 本人对于由此引起的任何隐私泄漏或其他后果概不负责。

请勿将本项目的任何内容用于商业或非法目的，否则后果自负。

如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，本人将在收到认证文件后删除相关内容。

以任何方式查看此项目的人或直接或间接使用本项目的使用者都应仔细阅读此声明, 本人保留随时更改或补充此免责声明的权利。

一旦使用/复制了本项目的任何内容，则视为您已接受此免责声明。

**您必须在下载后的24小时内从计算机或手机中完全删除以上内容。**

