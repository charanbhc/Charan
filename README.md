f=open('myfile.txt','r')
c=0
while True:
    l=f.readline()
    c=c+1
    if l=='':
        break
    
print('number of lines in the file =',c)
