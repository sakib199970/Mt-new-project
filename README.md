my new project data science 
print ("***** WELCOME TO ATM MACHINE STIMULATOR *****\n")

Pin = input('Enter Your Pin: ')

print("Option you can Exercise are: \n" '1) Balance \n' '2) Withdraw \n' '3) Deposit \n' '4) Exit \n') 

Option = input('Select Your Transaction from the above option: ')
if Option == '2':
  input('Enter Amount: ')
  print('Insufficient Balance')
