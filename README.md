# Identity-Testing

This is a repository for troubleshooting an identity issue on github. 

## Instructions:

Make two directories:
```
mkdir folder1
mkdir folder2
```

Clone this repo down using HTTPS into one folder:
```
cd folder1
git clone https://github.com/khalidwilliams/Identity-Testing.git
cd Identity-Testing
```
Add a file and commit it:
```
touch https-test.txt
git add .
git commit -m "Add https test file"
git push -u origin master
```

Clone the repo with SSH into a different directory:
```
cd ../../folder2
git clone git@github.com:khalidwilliams/Identity-Testing.git
cd Identity-Testing
```

Add another file and commit it:
```
touch ssh-test.txt
git add . 
git commit -m "Add ssh test file"
git push -u origin master
```

