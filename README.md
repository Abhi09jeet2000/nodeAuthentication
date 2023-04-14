# nodeAuthentication

# Endpoints 
#Base Url - http://localhost:8080

#1. "Post-METHOD" : '/auth/register' -> for registering the user
#2. "Post-METHOD" : '/auth/login' -> for Signing in
#3. "Get-METHOD" : '/users' -> for getting all users ~{works only if user is authenticated}
#4. "Delete-METHOD" :  '/users/:id'-> for delete account ~{works only if user authenticated and is owner of that account }
#5. "Patch-METHOD" : '/users/:id'-> for updating details of account ~{works only if user authenticated and is owner of that account}

# Mongo Db Collection Example

<img width="1512" alt="Screenshot 2023-04-14 at 11 25 36 AM" src="https://user-images.githubusercontent.com/65527851/231953707-7be1b9cf-6050-4fdf-adcb-f014d4872b07.png">
