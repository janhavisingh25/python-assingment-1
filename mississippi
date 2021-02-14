import operator
s=input("ENTER A STRING:")

dic={}

def most_frequent(s):

    for i in s:
        if i in dic:
            dic[i] +=1
        else:
            dic[i] =1

    return dict(sorted(dic.items(), key=operator.itemgetter(1),reverse= True))
    

fre=most_frequent(s)
print(fre)
