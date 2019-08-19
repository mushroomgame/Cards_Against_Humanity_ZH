# 反人类卡牌游戏 卡组文本

## 简介

反人类卡牌游戏是风靡欧美的知名卡牌游戏，详见https://en.wikipedia.org/wiki/Cards_Against_Humanity

蘑菇游戏工作室曾经制作过本游戏的中国版本，可是年久失修，卡组无法契合现今的中国网络环境（石锤过气小马），性能也亟待提升，在本repo征集新的反人类卡组

## 模板

- blackcards

文件名：数字ID + `.json`

内容：
```json
{
    "id": 0,
    "text": "在课堂上{blank}的话那么学校生活就结束了",
    "blanks": 1
}
```

- whitecards

文件名：数字ID + `.json`

内容：
```json
{
    "id": 0,
    "text": "脱粪"
}
```

- Commit

Comment: `[add/modify/delete/info]` + 数字ID / 内容

- Pull Request

PR名：`[添加/修改/删除/其他]` + 数字ID / 内容

描述：描述原因，或者出处，或者其他想告诉我们的

## 提交

1. 发送PR提交

- 你可以 `fork` 一份本代码到你的Github账户，使用 `Pull Request` 进行提交

    详尽的 `Git` 教程：https://www.runoob.com/git/git-tutorial.html

- 或者你可以 `fork` 后在网页端修改，然后使用 `Pull Request`

2. 发送issue提交

    页面上方有 `Issues` 标签，打开后新建issue，有模板可以照着填

    如果有卡组与时代脱轨或其他原因也可以提交issue

    如果这个都不会的话建议不要提交哦亲

## 那么什么时候会出呢？

~~绝赞跳票中~~ +Github问小白(wheatup)，有小姨子在线发牌