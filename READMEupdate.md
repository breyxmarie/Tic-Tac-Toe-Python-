
'''
print(" --- --- ---")
print("| 1 | 2 | 3 | ")
print(" --- --- ---")
print("| 4 | 5 | 6 | ")
print(" --- --- ---")
print("| 7 | 8 | 9 | ")
print(" --- --- ---")'''



def play1():
    global a, b, c, d, e, f, g, h, i
    t = True
    while t is True:
        pone = input("Player One: ")
        if pone == '1':
            if board[0][0] == '0':
                a = board[0][0] = 'X'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, a, False
            else:
                print("please try again")
                t is True
        elif pone == '2':
            if board[0][1] == '0':
                b = board[0][1] = 'X'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, b, False
            else:
                print("please try again")
                t is True
        elif pone == '3':
            if board[0][2] == '0':
                c = board[0][2] = 'X'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, c, False
            else:
                print("please try again")
                t is True
        elif pone == '4':
            if board[1][0] == '0':
                d = board[1][0] = 'X'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, d, False
            else:
                print("please try again")
                t is True
        elif pone == '5':
            if board[1][1] == '0':
                e = board[1][1] = 'X'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, e, False
            else:
                print("please try again")
                t is True
        elif pone == '6':
            if board[1][2] == '0':
                f = board[1][2] = 'X'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, f, False
            else:
                print("please try again")
                t is True
        elif pone == '7':
            if board[2][0] == '0':
                g = board[2][0] = 'X'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, g, False
            else:
                print("please try again")
                t is True
        elif pone == '8':
            if board[2][1] == '0':
                h = board[2][1] = 'X'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, h, False
            else:
                print("please try again")
                t is True
        elif pone == '9':
            if board[2][2] == '0':
                i = board[2][2] = 'X'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, i, False
            else:
                print("please try again")
                t is True
        else:
            print("Please Enter a Valid Character")
            t is True


def play2():
    global a,b,c,d,e,f,g,h,i
    t = True
    while t is True:
        ptwo = input("Player Two: ")
        if ptwo == '1':
            if board[0][0] == '0':
                a = board[0][0] = 'O'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, a, False
            else:
                print("please try again")
                t is True
        elif ptwo == '2':
            if board[0][1] == '0':
                b = board[0][1] = 'O'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, b, False
            else:
                print("please try again")
                t is True
        elif ptwo == '3':
            if board[0][2] == '0':
                c = board[0][2] = 'O'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, c, False
            else:
                print("please try again")
                t is True
        elif ptwo == '4':
            if board[1][0] == '0':
                d = board[1][0] = 'O'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, d, False
            else:
                print("please try again")
                t is True
        elif ptwo == '5':
            if board[1][1] == '0':
                e = board[1][1] = 'O'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, e, False
            else:
                print("please try again")
                t is True
        elif ptwo == '6':
            if board[1][2] == '0':
                f = board[1][2] = 'O'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, f, False
            else:
                print("please try again")
                t is True
        elif ptwo == '7':
            if board[2][0] == '0':
                g = board[2][0] = 'O'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, g, False
            else:
                print("please try again")
                t is True
        elif ptwo == '8':
            if board[2][1] == '0':
                h = board[2][1] = 'O'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, h, False
            else:
                print("please try again")
                t is True
        elif ptwo == '9':
            if board[2][2] == '0':
                i = board[2][2] = 'O'
                print(" --- --- ---")
                print("| " + a + " | " + b + " | " + c + " | ")
                print(" --- --- ---")
                print("| " + d + " | " + e + " | " + f + " | ")
                print(" --- --- ---")
                print("| " + g + " | " + h + " | " + i + " | ")
                print(" --- --- ---")
                return board, i, False
            else:
                print("please try again")
                t is True
        else:
            print("Please Enter a Valid Character")
            t is True

def checkforwin(board):
    let = ['X', 'O', 'T']
    global p
    global win
    for p in let:
        if p == board[0][0] == board[0][1] == board[0][2]: #--- horizontal
            win += 1
            return p, win
        elif p == board[1][0] == board[1][1] == board[1][2]: #---
            win += 1
            return p, win
        elif p == board[2][0] == board[2][1] == board[2][2]: #---
            win += 1
            return p, win
        elif p == board[0][0] == board[1][0] == board[2][0]: #|
            win += 1
            return p, win
        elif p == board[0][1] == board[1][1] == board[2][1]:# |
            win += 1
            return p, win
        elif p == board[0][2] == board[1][2] == board[2][2]:#   |
            win += 1
            return p, win
        elif p == board[0][0] == board[1][1] == board[2][2]: #\
            win += 1
            return p, win
        elif p == board[0][2] == board[1][1] == board[2][0]: #/win += 1
            win += 1
            return p, win


def whowon():
    #p = checkforwin(board)
    global p, p1s, p2s
    if p == 'X':
        print("Player 1 won!!")
        p1s += 1
        print("Player 1: " + str(p1s) + "\n" + "Player 2: " + str(p2s))
        return win == 1, p1s
    elif p == 'O':
        print("Player 2 won!!")
        p2s+= 1
        return win == 1, p2s
    else:
        print("It's a tie")

'''
def gameplay():

    while '0' in board and win is True:
        play1()
        whowon()
        if win is False:
            break
        if '0' in board:
            play2()
            whowon()
        else:
            break
    print("No more moves left!!")
    whowon()
    print(board)'''

if _name_ == "_main_":
    import numpy as np


    a = '1'
    b = '2'
    c = '3'
    d = '4'
    e = '5'
    f = '6'
    g = '7'
    h = '8'
    i = '9'
    print(" --- --- ---")
    print("| " + a + " | " + b + " | " + c + " | ")
    print(" --- --- ---")
    print("| " + d + " | " + e + " | " + f + " | ")
    print(" --- --- ---")
    print("| " + g + " | " + h + " | " + i + " | ")
    print(" --- --- ---")

    board = np.array([['0', '0', '0'],
                      ['0', '0', '0'],
                      ['0', '0', '0']])
    win = 0
    p1s = 0
    p2s = 0
    playagain = 0
    while playagain == 0:
        while '0' in board and win == 0:
            play1()
            checkforwin(board)
            if '0' in board and win == 0:
                play2()
                checkforwin(board)
            elif '0' not in board:
                print("No more moves left!!")
                whowon()
            else:
                checkforwin(board)
                whowon()

        user = input("Do You Want To Play Again?").lower()
        if user == "yes":
            playagain = 0
        else:
            playagain = 1
