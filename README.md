# loa-logger-cn
***
## 命运方舟国服dps插件
~~目前只是一个提案，提出提案的目的是希望有更多的人能加入开发~~


项目已经进入初步开发，目前在等待最后一块拼图完成

因为一些原因，直接适配外服插件到国服暂时没有办法

### 前排提示
* 截止目前的美服/韩服插件，以及未来的国服插件都是使用npcap进行抓包，并且分析网络包的产物，理论上不会注入游戏程序，这样能够避免绝大多数情况下的非法软件审查。
* 目前来说，抓包形式的插件因为非侵入式，常规情况下不会直接导致封号问题出现。
* 如果插件被认定为禁止使用的外部程序,tp仍然有能力封禁使用的玩家账号


已知解密数据包需要xor.bin/oodle.bin/opcodes

10.17更新

opcode影响数据包的具体格式，现在工作重新回到opcodes的提取

10.21更新

kr服策划已经注意到kr的dps插件，并且一定程度上修改了数据包（加密/修改数据结构），在本次更新稳定前暂时停止目前的开发流程，可能会尝试一下解密kr的新数据

提取进度
| 进度 | oodle.bin | xor.bin | opcodes |
|----------|----------|----------|----------|
| 提取 | √ | √ | progressing |
| 验证 ||||

插件制作Future
| 进度 | [meter-core-cn](https://github.com/SuYueQiuLiang/meter-core-cn) | meter |
|----------|----------|----------|
| 进度 | 0% | 0% |
