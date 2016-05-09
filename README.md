# poo4_project
IG2I Project in JAVA EE

##Proxy is a sh*t

To work with git at IG2I do this :

1. Set up the proxy

```bash
git config --global http.proxy http://username:pwd@proxy.ig2i.fr:3128
```
*Replace username and pwd*

2. Check your config

```bash
git config --global --get http.proxy
```
3. If you want to unset the proxy config

```bash
git config --global --unset http.proxy
```

##Clone this repo

```bash
git clone https://github.com/pachr/poo4_project.git (with no SSH keys)
git clone git@github.com:pachr/poo4_project.git (If you have a public Key)
```

##Create a branch

**FROM MASTER BRANCH ONLY**

Check you local branch

```bash
$> git checkout master
$> git pull origin master
$> git checkout -b <branch_name>
```

##Commit your updates

```bash
$> git add <file_name>
$> git commit -m "<message>"
```

##Push a branch to the remote repository 

```bash
$> git push origin <branch_name>
```

##Create a pull request to merge on develop

1. With a command line

*ON YOUR BRANCH*

```bash
$> hub pull-request -b develop
```

2. With github GUI


##Contributors: 
- Lucien Fregosi 
- Paul-Alexandre Chretien 
- Mohammed Belkheiri
- Timothee Dzik 

