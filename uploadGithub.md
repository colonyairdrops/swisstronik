```bash
git init
```
```bash
git add .
```
```bash
git remote remove origin
```
```bash
git commit -m "Initial commit"
```
- Create a repository in your github manually and copy the link of this repository
---
YOU NEED TO DO THE BELOW PROCESS ONLY ONE TIME, ALSO MAKE SURE TO SAVE THE GENERATED KEY SOMEWHERE ELSE
- Now visit [This Link](https://github.com/settings/tokens/new) (If it ask password, then provide password)
- In the `Note` section write anything
- In the `Select scopes` sections select `repo` section and then click on Generate token
- Copy that token, this token will be used as passoword during github files upload
---
```bash
git remote add origin https://YOUR_GITHUB_USERNAME:ACCESS_TOKEN@REPO_LINK_BEGIN_WITHOUT_HTTPS_AND_END_WITH_.git
```
- Example : `https://colonyairdrops:ghp_9MTyjsowoer1352kfwLgYv3Vow6U@github.com/colonyairdrops/simpleContract.git`
```bash
git branch -M main
```
```bash
git push -u origin main
```
- Done !!
- Make sure to change the readme file once pushed in your github repository
