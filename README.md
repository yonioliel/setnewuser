# setnewuser
This script PowerShell is to Create a New User in  ActiveDireactory.

# show where to create the New User
dsadd user "cn=name of the user,ou=ou,dc=domain,dc=co,dc=il" 

# Give a Name for the User
 -fn firstname -ln lestname -upn name@domain
 
 # Disable or On the User Account
 -disabled no
 
 # Give a Password for the Account
 -pwd "password for the account"
 
 # If the user need to Chanege the Password in the first time connect
 -mustchpwd no
 
# If the Account need to Expires Time
-acctexpires never

# If the Password need to Expires
-pwdneverexpires no
