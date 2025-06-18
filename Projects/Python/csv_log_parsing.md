#CSV parsing script that imports csv files and exports all failed login attempts                                                  

log = " "     # Variable to store log file path (Drop you file inbetween the " ")



with open(log,'r') as file:                         
    logs = file.readlines()                           # Imports the file into readable lines for accurate parsing ("r" signifies that we are only reading the file at this point)                  


with open("failed_logins.txt", 'w') as ip:            # Opens a blank txt doc for us to write to. note the "w" changes the operation to write
    for line in logs:
        if "fail" in line:                            # Iterates through the file line by line searching for our key phrase " fail"  
            ip.write(line+"\n")                       # Writes each line that matches search criteria to the generated file - in this case it's" failed_logins.txt"  
    ip.close()                                        # Closes and generates the new log file populated with our search criteria


    



# Purpose of this script is to filter out failed login attempts for further analysis
