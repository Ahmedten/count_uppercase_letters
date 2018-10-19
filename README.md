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
