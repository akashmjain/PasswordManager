# PasswordManager
Simple Password Manager.
# Features
- To generate complex password 
- To store password and username pair for a particular website
- To Autofill whenever required the places where username and password is asked.

# Steps user might take
- generate a account in a application which will be local to user.
- password genereated during this step will be encrypted using sha256 encoding
- all the data related to the user will be stored at user's local machine(i.e. his device)
- if user forgets his password, password cannot be recoverd from our end.(since the password is hashed locally)


# Bonus feature we'll try to implement
- allow using fingerprint scanner to access appliacation for autofill.
- store password in password manager at the time of account creation or login of an new unknown account in a device.

