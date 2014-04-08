Oracle SQL Cheatsheet
==============
##Account Expiration

Set password expiration to unlimited
```
ALTER PROFILE DEFAULT LIMIT PASSWORD_LIFE_TIME UNLIMITED
```
Change user's password
```
alter user *user_name* IDENTIFIED by *password*;
```
Set a user's profile to default
```
alter user *user_name* profile default;
```

##Privileges

Enable user to create views
```
GRANT CREATE ANY VIEW to *user_name*;
```
    
