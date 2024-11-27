a = [[0,0,0,0,0],[0,0,0,0,0],[0,0,0,0,0],[0,0,0,0,0],[0,0,0,0,0]]


c = 2
for i in range(5):
    for j in range(5):   
         
        a[i][c] = 1 

        if ((c+j) >= 0) and ((c+j) < 5):      
            a[i][c+j] = 1
        
        #if ((c-j) >= 0) and ((c-j) < 5):     
        #    a[i][c-j] = 1   

        if (j == i):           
            break

        



for v in range(5):
    print(a[v])
