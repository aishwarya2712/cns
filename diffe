if __name__=='__main__':
    
    P=int(input("enter a prime number"))
    R=int(input("enter a primitive root"))
    print('The prime number is',P)
    print('the primitive root is',R)
   
    a=3
    b=4
    print("Private key of alice is",a)
    print("Private key of alice is",b)
    
    x=int(pow(R,a,P))
    y=int(pow(R,b,P))
    
   
    ka=int(pow(y,a,P))
    kb=int(pow(x,b,P))
    print('Secret key for Alice is',ka)
    print('secret key for bob is ',kb)
    
    
