def average(list):
    r= 0
    for i in list:
        r+=i
    r= r/len(list)
    return(r)
print(average([1,2,3,4]))
