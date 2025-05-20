def full_pyramid(n):
     for i in range(1, n + 1):
         for j in range(n - i):
             print(" ", end="")
         for k in range(1, 2*i):
             print("*", end="")
         print()
full_pyramid(5)
print("\n")

def inverted_full_pyramid(n):
    for i in range(n, 0,-1):
        for j in range(n - i):
            print(" ", end="")
        for k in range(2*i - 1):
            print("*", end="")
        print()
inverted_full_pyramid(5)
print("\n")

def half_pyramid(n):
    for i in range(1,n+1):
        for j in range(1,i + 1):
            print("*", end="")
        print("")
half_pyramid(5)
print("\n")

def rhalf_pyramid(n):
    for i in range(1,n+1):
        print(("*"*i).rjust(n))
    print("")
rhalf_pyramid(5)
print("\n")

def lhalf_pyramid(n):
    for i in range(1,n+1):
        print(("*"*i).ljust(n))
    print("")
lhalf_pyramid(5)
print("\n")

def L_shape(h,w):
    for i in range(h):
        if i==h-1:
            print("* "*w)
        else:
            print("* ")
L_shape(4,4)
print("\n")