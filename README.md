# prime-no.s-in-an-interval
s = int (input("starting: "))
e = int (input("End: "))
print ("prime no.s in the range ", s, "to", e)  
for n in range(s, e ):
    f = 0          
    for m in range(2, n): 
        if (n % m == 0):             
            f = 1        
            break
    if (f == 0):          
            print (n)
