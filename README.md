# String-to-md5
import hashlib 

  
# input string 

str2hash = input("Enter your string Value :")

# then sending to md5() 

result = hashlib.md5(str2hash.encode()) 

#generating md5 code

print("The Output of the string data in md5 is :", end ="") 

print(result.hexdigest())
