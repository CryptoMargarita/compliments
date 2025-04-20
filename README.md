# compliments
# compliment_bot.py

import random

def say_compliment():
    compliments = [
        "You're doing great! 💪",
        "You're awesome! 🌟",
        "You're stronger than you think 💥",
        "You're enough. Always. ❤️",
        "You got this! 🔥"
    ]
    print(random.choice(compliments))

if __name__ == "__main__":
    say_compliment()
