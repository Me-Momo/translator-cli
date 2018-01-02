
## About

💻 A translate tool in terminal, inspired from [translate-shell](https://github.com/soimort/translate-shell)

🤩 Advanced: specific-language: `zh_to_jp`/`jp_to_zh`


## Install

确保安装了`awk`运行环境
```sh
# 查看是否已经安装
$ which awk # /usr/bin/awk
# 如果没有，请安装
brew install awk
# sudo apt-get install gawk
# yum install gawk
```

```
npm i translator-cli -g
```

## Usage

```
$ trans --help | -h
```

### Translate one word

```
trans -t [tl] [word]
trans :[sl]+[tl] [word]
```

example

```
trans :zh+en hello
```
```
hello
/heˈlō,həˈlō/

你好
(Nǐ hǎo)

Definitions of hello
[ English -> 简体中文 ]

interjection
    你好!
        Hello!, Hi!, Hallo!
    喂!
        Hey!, Hello!

hello
    你好, 您好

hello
/heˈlō,həˈlō/

noun
    an utterance of “hello”; a greeting.
        - "she was getting polite nods and hellos from people"

exclamation
    used as a greeting or to begin a telephone conversation.
        - "hello there, Katie!"
    Synonyms: hi, howdy, hey, hiya, ciao, aloha

verb
    say or shout “hello”; greet someone.
        - "‘Hi Kirsten,’ he helloed , obviously calling me Kirsten on purpose."
```

### Text-To-Speak

```
trans -sp -t zh おいしい
```

```
おいしい
(Oishī)

味道不错
(Wèidào bùcuò)

Translations of おいしい
[ 日本語 -> 简体中文 ]

おいしい
    味道不错, 美味
```

Also supported `Translate a File`, `Translate a Web Page`

See more usages in [translate-shell](https://github.com/soimort/translate-shell)

### Specific Language: Japanese

```
jpTrans 美味しい
```

```
美味しい
(Oishī)

美味
(Měiwèi)

Translations of 美味しい
[ 日本語 -> 简体中文 ]

Synonyms
    adjective
        - 麗しい, 綺麗, 好ましい, 好い, 善い, ナイス, 可愛い, 快い, 良い

See also
    美, 味
```

## Thanks

  Thanks to [soimort](https://github.com/soimort)