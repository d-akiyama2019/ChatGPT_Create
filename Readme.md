```
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
