n = input()
n = int(n)
count = 0
if(n>=100):
    count = count - 1
if(n>=10):
    count = count - 1
for i in range(0,10):
    
    if(n>=100):
        
        for c in range(0,10):
            if((c+2*i)*100+(c+i)*10+c <= n):
                if(c+2*i>9):
                    break
                count = count + 1
        if(i!=0):        
            for c in range(9,-1,-1):
                if((c-2*i)*100+(c-i)*10+c <= n):
                    if(c-2*i<1):
                        break
                    count = count + 1
        
    if(n>=10):
        
        for c in range(0,10):
            if((c+i)*10+c <=n):
                if(c+i>9):
                    break
                count = count + 1
                
        if(i!=0):
            for c in range(9,-1,-1):
                if((c-i)*10+c <=n):
                    if(c-i<1):
                        break
                    count = count + 1
                
if(n<9):
    count = count + n
else:
    count = count + 9
print(count)
