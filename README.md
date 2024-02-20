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

then restart and input UNIX username, UNIX password.


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
echo "your text" > folder

```
