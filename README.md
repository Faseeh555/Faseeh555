import time

def surprise_girlfriend():
    message = "I love you more than words can express, [Laraib] ❤️"
    for char in message:
        print(char, end='', flush=True)
        time.sleep(0.1)  # Adjust the sleep duration for the desired speed
    print("\n")

if __name__ == "__main__":
    surprise_girlfriend()
