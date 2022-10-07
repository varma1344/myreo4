# myreo4

def myfunc(lis):
    if (len(lis)>0):
        le=len(lis)
        a=0
        for i in lis:
            a=a+i
        ans=a/le
        return round(ans,2)
    else:
        return 0
print(myfunc([1,11,7,8,-1,6,3]))
print(myfunc([1,11,17,28,-1,6]))