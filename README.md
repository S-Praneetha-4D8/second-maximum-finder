lst=[1,99,12,55,64,33,21,43,87,17,98]
maxi=-100000
maxi2=0
for i in lst:
    if(i>maxi):
        maxi2=maxi
        maxi=i
    elif(i>maxi2 and i<maxi):
        maxi2=i
print('maximum is:',maxi2)
