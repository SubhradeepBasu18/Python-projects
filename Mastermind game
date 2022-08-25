import random
p = random.randrange(1000,10000)
n = int(p)
print("Guess the 4-digit number: ")
k = int(input())
x=1
c=0
d=0

if n==k:
    print("YOU GUESSED IT RIGHT AT FIRST TRY !!")
else :
    n=str(n)
    k=str(k)
    while x==1:
        
        for i in range(0,4):
            if n[i]==k[i]:
                print(n[i],end="")                
                
            elif n==k:
                print("CORRECT !!")
                break
            else:
                print("X",end="")
                
        print()
        if n==k:
            print("YOU GUESSED IT RIGHT  !!")
            break
        else:
            print("Guess again !!")
            t1 = str(input())
            k=t1
            #x+=1
            c+=1
    # print("IF WISH TO CONTINUE PRESS '1'")
    # x=int(input())        
print(f"IT TOOK {c+1}ATTEMPTS")
