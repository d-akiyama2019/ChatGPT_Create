ChatGPTくんにタイピングゲームを作ってもらうには、
```
やあ！
pythonを使った簡単なタイピングゲームを作ってほしい！
```
と入力すると出てきた。

```py
import time

def typing_game():
    words = ["hello", "world", "python", "programming"]
    score = 0
    start_time = time.time()
    for word in words:
        print("Type the following word: ", word)
        user_input = input()
        if user_input == word:
            print("Correct!")
            score += 1
        else:
            print("Incorrect.")
    end_time = time.time()
    total_time = end_time - start_time
    print("Total Score: ", score)
    print("Total Time: ", total_time)

typing_game()

```

- pygameを使ってというと、GUIのゲームを作ってくれる！
- cursesを使ってというと、CUIのゲームを作ってくれる！
- 途中で止まるときは、続きをかいて！っていうと続きを書いてくれる！
- ゲームは
    - タイピングゲーム
    - ピンポンゲーム
    - シューティングゲーム
    - 数独
    - マインスイーパー
    - ピンボール
    - スネークゲーム
    - じゃんけんゲーム
    - ブロック崩し
