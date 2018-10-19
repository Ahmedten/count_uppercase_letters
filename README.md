# count_uppercase_letters
def measure_udacity(p):
    s = 0
    for e in p:
        if e[0] == "U":
            e = 1
        else:
            e = 0
        s = s + e
    return s




print measure_udacity(['Dave','Sebastian','Katy'])
#>>> 0

print measure_udacity(['Umika','Umberto'])
#>>> 2


second project 
def find_element(p,a):
    i = 0
    for e in p:
        if e == a:
            return i
        i = i+1
    return -1
    
print find_element([1,2,3],3)
#>>> 2

print find_element(['alpha','beta'],'gamma')
#>>> -1
