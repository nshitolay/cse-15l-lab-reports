# Installing VSCode
1. Open the VSCode website and click the blue install button to download VSCode. 

![VSCode Install]([https://github.com/nshitolay/cse-15l-lab-reports/blob/main/images/image1.png](https://github.com/nshitolay/cse-15l-lab-reports/blob/main/images/image2.png))

2. Open the Home page of VSCode which should look like this or similar. 

![](https://github.com/nshitolay/cse-15l-lab-reports/blob/main/images/getstarted_page.png)

# Connecting to a Remote Server

1. Install Git onto your system using [this link](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994)

2. To use ssh to connect to a remote server, open a new terminal window and type in the command 
`$ ssh cs15lwi23zz@ieng6.ucsd.edu` 
Replace the zz with your accounts last three letters. 

You will receive the following message: 

![VSCode Install](https://github.com/nshitolay/cse-15l-lab-reports/blob/main/images/image1.png)

Select "yes" by typing in yes. 

4. There should be a request for your password: 

![VSCode Install](https://github.com/nshitolay/cse-15l-lab-reports/blob/main/images/image1.png)

Type in your password. After this, your terminal is connected to a remote server. 

# Trying some commands. 

Here are some of the commands to try: 

```
cd ~
cd
ls -lat
ls -a
cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/
cat /home/linux/ieng6/cs15lwi23/public/hello.txt
```

Some of these commands are show below and your outputs should be similar:
![Image](http://url/a.png)	


