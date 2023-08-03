string1 = input()

revstring = ' ' 

if string1 == 'd' or 'done' or 'Done':
    pass

for rev in range(len(string1)-1,-1,-1):
    revstring += string1[rev]
    if len(revstring)  <= (len(string1)):
        continue
    print(revstring)
