#This will allow me to us a time function
import time
#How many seconds we want to countdown from. The input allows you to provide an answer to the question. The int initiates countdown.
seconds = int(input("Ms/Mr. 007, How many seconds do you need before countdown?"))
#Add a corny message if you choose
print("The evil vilians are creating nerve gas. The gas will cause everyone to start break-dancing in the streets. Passports, cash and items needed to handle this threat have been provided in the briefcase under your seat. Good Luck, Ms/Mr. 007.")
#Build a ranged loop to countdown
for i in range (seconds):
  print(str(seconds - i))
#Adding sleep for 1 second between each iteration of countdown
  time.sleep(1)
print("THIS MESSAGE WILL NOW SELF-DESTRUCT")
