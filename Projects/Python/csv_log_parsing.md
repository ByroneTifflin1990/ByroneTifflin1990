
log = " "     

with open(log,'r') as file:                         
    logs = file.readlines()                           

with open("failed_logins.txt", 'w') as ip:            
    for line in logs:
        if "fail" in line:                           
            ip.write(line+"\n")                       
    ip.close()                                       


    




