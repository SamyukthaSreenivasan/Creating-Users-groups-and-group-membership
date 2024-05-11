### EX NO 3

### AIM:
The aim is to create specific users, groups, and group memberships.

### PROCEDURE:
1.Create the 'admin' Group

2.Create User 'harry' and Add to 'admin' Group as Secondary Group

3.Create User 'natasha' and Add to 'admin' Group as Secondary Group

4.Create User 'sarah' without Shell Access and Not a Member of 'admin' Group

5.Set Passwords for Users.

### PROGRAM / COMMANDS:
```
Developed by: Samyuktha S
Register Number: 212222240089
```
```
sudo groupadd admin

sudo useradd -G admin harry

sudo useradd -G admin natasha

sudo useradd -s /sbin/nologin sarah

sudo passwd harry
sudo passwd natasha
sudo passwd sarah
```
### OUTPUT:
![image](https://github.com/SamyukthaSreenivasan/Creating-Users-groups-and-group-membership/assets/119475703/1b103154-5c80-4f34-af22-7b856c7401e6)

### RESULT:
Thus the program to create specific users,groups and group memberships is successfully implemented.
