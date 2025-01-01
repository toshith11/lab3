# lab3
def compute_product_or_sum(a,b):
    product=a*b
    if product<=1000:
        return product
    else:
        return a+b
a=int(input("Enter the value of a:"))
b=int(input("Enter the value of b:"))
result=compute_product_or_sum(a,b)
print("The result is:",result)
