# who_wants_to-_be_a-_millionaire
A CLI implementation of the iconic quiz show! Answer trivia questions, climb the money land to win virtual millions. Built with Python for terminal-based fun!
questions=[
    ["Which planet is known as the Red Planet?", "Venus", "Mars", "Jupiter", "Saturn",1],
    ["Who painted the 'Mona Lisa'?", "Pablo Picasso", "Leonardo da Vinci", "Vincent van Gogh", "Michelangelo",2],
    ["What is the capital of Australia?", "Sydney", "Canberra", "Melbourne", "Perth",2],
    ["Which gas is most abundant in Earth's atmosphere?", "Oxygen", "Nitrogen", "Carbon dioxide", "Hydrogen",2],
    ["Who invented the telephone?", "Thomas Edison", "Alexander Graham Bell", "Nikola Tesla", "Albert Einstein",2],
    ["Which animal is the fastest on land?", "Lion", "Cheetah", "Horse", "Greyhound",2],
]

for question in questions:
    print(question[0])
    print(f"a. {question[1]}")
    print(f"b. {question[2]}")
    print(f"c. {question[3]}")
    print(f"d. {question[4]}")

    a = int(input("enter your ans: 1 for a, 2 for b, 3 for c, 4 for d: "))
    if question[5] == a:
        print("correct answer")
    else:
        print("better luck next time!!")
        break
