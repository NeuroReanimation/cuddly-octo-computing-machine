import random

guessesTaken = 0

print('Введите ваше имя?')
myName = input()

number = random.randint(1, 20)
print(myName + ", Будет загадано число от 1 до 20")

for guessesTaken in range(6):
    print("Попробуйте отгадать. Введите число")
    guess = input()
    guess = int(guess)

    if guess < number:
        print("Ваше число слишком маленькое")

    if guess > number:
        print("Ваше число слишком большое")

    if guess == number:
        break

if guess == number:
    guessesTaken = str(guessesTaken + 1)
    print("Отлично, " + myName + "! Вы угадали за " + guessesTaken + " попыток")

if guess != number:
    number = str(number)
    print("Извините. Было загадано число " + number)
