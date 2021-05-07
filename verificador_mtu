import os 

for i in range(500, 1500):
    a =  os.system(f'ping www.google.com -n 1 -f -l {i} > nul')
    if not a == 0:
        print(f'Verificação terminada. MTU: {i+28}')
        pause = input('')
        break
        
