import random
print('''
Compatibility Calculator
Member 1 : "Name1"
Member 2 : "Name2"
And Let the Program do the rest!
''')
name1=input('Enter the Name1 : ')
name2=input('Enter the Name2 : ')
compatibility=random.randint(1,100)
print(f'The compatibility between {Name1} and {Name2} is {compatibility}')
```
"""
# compatibility_calculator.py

import random
import time
import sys

def print_intro():
    print("=" * 50)
    print("💖 Welcome to the Ultimate Compatibility Calculator 💖")
    print("=" * 50)
    print("Enter two names, and let the magic happen!\n")

def get_name(prompt):
    while True:
        name = input(prompt).strip()
        if name:
            return name.title()
        else:
            print("⚠️ Please enter a valid name.")

def loading_bar():
    print("\nCalculating compatibility", end="")
    for _ in range(5):
        time.sleep(0.5)
        print(".", end="")
        sys.stdout.flush()
    print("\n")

def show_result(name1, name2, score):
    print("=" * 50)
    print(f"💘 Compatibility between {name1} and {name2}: {score}%")
    if score > 90:
        print("🌟 You two are a perfect match!")
    elif score > 70:
        print("😊 There's strong chemistry between you.")
    elif score > 50:
        print("😄 There's potential! Keep building that bond.")
    elif score > 30:
        print("😅 You might face a few bumps, but who knows?")
    else:
        print("💔 Hmm... maybe better as friends?")
    print("=" * 50)

def main():
    print_intro()
    name1 = get_name("🔤 Enter Name 1: ")
    name2 = get_name("🔤 Enter Name 2: ")
    loading_bar()
    score = random.randint(1, 100)
    show_result(name1, name2, score)

if __name__ == "__main__":
    main()
"""
