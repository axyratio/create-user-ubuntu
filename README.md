# create-user-ubuntu
## install wsl ubuntu

## open your ubuntu
```
ubuntu
```

if ubuntu is not avalible, install ubu.

```
wsl --install
```

then restart, Enter The UNIX username and UNIX password.


## add user more
```
adduser user
usermod -a -G sudo user
su - user
```

## del user
```
deluser user
```

## common command
```
cd /path/path
ls # check list in folder
mkdir <you directorie> #make directorie
cat yourfile #read file
echo "your text" > folder #create file wtih text
touch file # create file
mv dir/file dir/file #move
cp dir/file dir/file #copy
```

## symbol in command
```
t* is all file "t..."
? is any one charector
?? is any two charector
```
