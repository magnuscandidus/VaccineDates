# VaccineDates
# cook your dish here
t=int(input())
while t:
    d,l,r=map(int,input().split())
    if(l<=d<=r):
        print("Take second dose now")
    elif(d<=l):
        print("Too Early")
    else:
        print("Too Late")
    t-=1
