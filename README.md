feeling = input('1.Sad.\n2.Emotional.\n3.Tired.\n4.Bored.\n5.Thirsty\n')
match feeling:
    case '1':
        print('watch the Rush Hour')
    case '2':
        print('be pataint')
    case '3':
        print('take the rest')
    case '4':
        print('watch the avanger movie')
    case '5':
        print('take some water')
    case _:
        print('just write a number of your feeling')
