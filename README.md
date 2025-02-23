# Bull-or-Bear
def solve():
    X, Y = map(int, input().split())
    
    if Y > X:
        print("PROFIT")
    elif Y < X:
        print("LOSS")
    else:
        print("NEUTRAL")

T = int(input())
for _ in range(T):
    solve()
