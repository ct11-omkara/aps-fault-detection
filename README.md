# neurolab-mongo-python

![image](https://user-images.githubusercontent.com/57321948/196933065-4b16c235-f3b9-4391-9cfe-4affcec87c35.png)

### Step 1 - Install the requirements

```bash
pip install -r requirements.txt
```

### Step 2 - Run main.py file

```bash
python main.py
```


Git version

```bash
git --version
```

To download your dataset
```
wget https://raw.githubusercontent.com/avnyadav/sensor-fault-detection/main/aps_failure_training_set1.csv
```

This is changes made in neuro lab.

Git commands

If you are starting a project and you want to use git in your project

```
git init
```
Note: This is going to initialize git your source code

or

You can clone existing github repo
```
git clone <github_url>
```
Note: clone/download github repo in your system

Add your changes made in file to git staging area
```
git add <file_name>
```
Note: You can give file_name to add specific file or use "." to everything to staging area

Create commits
```
git commit -m "messege"
```

```
git push origin main
```
To push your changes forcefully
```
git push origin main -f
```
Note: origin--> contains url to your github repo
main--> is your branch name

To pull changes from github repo
```
git pull origin main
```
Note: origin--> contains url to your github repo
main--> is your branch name