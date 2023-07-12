# LaLiga
# cook your dish here
t = int(input())
for i in range(t):
    G = input()
    H = input()
    I = input()
    J = input()
    teams = [G, H, I, J]
    teams.sort()
    X, Y = map(str,teams[0].split())
    A, B = map(str,teams[1].split())
    C, D = map(str,teams[2].split())
    E, F = map(str,teams[3].split())
    if int(D) > int(F) and int(Y) > int(B):
        print("Barcelona")
    else:
        print("RealMadrid")
    
    # b e mr
