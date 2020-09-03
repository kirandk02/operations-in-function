# with parameter
print("with parameter")
def arithmetic(a,b):
    c=("a+b:",a+b,"a-b:",a-b,"a*b:",a*b,"a/b:",a/b,"a%b:",a%b,"a**b:",a**b,"a//b:",a//b)
    print(*c,sep="\n")
arithmetic(4,5) 

# without parameter
print("without parameter")
a=4
b=5
def arithmetic():
    c=("a+b:",a+b,"a-b:",a-b,"a*b:",a*b,"a/b:",a/b,"a%b:",a%b,"a**b:",a**b,"a//b:",a//b)
    print(*c,sep="\n")
arithmetic()    
