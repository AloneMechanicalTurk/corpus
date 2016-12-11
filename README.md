# toshitai corpus
This Repository is corpus data of "[佐倉としたい大西](https://www.onsen.ag/program/toshitai/)"

## FORMAT
### FILE
- One file is one broadcast
- File format is UTF-8
- Line feed code is CRLF or LF (CRLF is better)

### BODY
- Write it in one line until the change of speaker or topic
- A line consists of a speaker and a word
- Speakers and words are separated by Tab (```\t```)

### Notes on notation
- Alphanumeric characters are single-byte characters
- Japanese and symbols are double-byte characters
- "長音符" is marked with ```ー```
- "拗音" should be used
- Use ellipses with double-byte characters ```…```

### Example
```
大西沙織	いぇーい！始まったぜーい！
佐倉綾音	はい, 始まりました
大西沙織	どうしたのテンション？
佐倉綾音	いや… さわんないで貰っていいですか？
```

## Status
||status|user|
|:--:|:--:|:--:|
|[01](data/01.txt)|WIP|[koike](https://github.com/koike)|

## CONTRIBUTE
PRs accepted

## LICENSE
[MIT LICENSE](LICENSE)
