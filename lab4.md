# Step 1 - Log into ieng6

**What I typed:**

1. `ssh cs15lwi23aea@ieng6.ucsd.edu <Enter>`

![image](https://user-images.githubusercontent.com/122496486/220794330-4edae0a2-165d-46ec-92a1-3f8f06fc3aeb.png)


# Step 2 - Clone your fork of the repository from your Github account

**What I typed:**

1. `git clone git@github.com:nshitolay/lab7.git <Enter>`

![image](https://user-images.githubusercontent.com/122496486/220794517-7c78abac-909d-487e-8d0d-6cf7deb2d622.png)


# Step 3 - Run the tests, demonstrating that they fail

**What I typed:**

1. `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java <Enter>`
3. `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples <Enter>`

![image](https://user-images.githubusercontent.com/122496486/220794767-639742f4-f5c2-4924-82dd-29bcc98f24c3.png)



# Step 4 - Edit the code file to fix the failing test 

**What I typed:**

1. `nano ListEx <Tab> <Enter>` (This autofilled to `nano ListExamples.java`)
2. Using the down arrow key, right arrow key, and backspace, 
I changed index1 to index2 in the last while loop of the code.
3. `<Ctrl + O> <Enter>` (To save the file)
4. `<Ctrl + X> <Enter>` (To exit nano)

![image](https://user-images.githubusercontent.com/122496486/220796554-fd0135d9-5a2f-4873-8ac2-efd7a7395ae6.png)

![image](https://user-images.githubusercontent.com/122496486/220794921-b9746266-a893-4de8-9804-11c4710a258b.png)







# Step 5 - Run the tests, demonstrating that they now succeed

**What I typed:**

1. `<Up> <Up> <Up> <Up> <Enter>` (To Compile the Tests)
2. `<Up> <Up> <Up> <Enter>` (To Run the Tests)
  
![image](https://user-images.githubusercontent.com/122496486/220796091-187f1804-21ef-4ca1-a0af-bffc547d57ec.png)

# Step 6 - Commit and push the resulting change to your Github account

**What I typed:**

1. `git add ListExamples.java <Enter>`
2. `git commit -m "Edited Examples" <Enter>`
3. `git push <Enter>`

![image](https://user-images.githubusercontent.com/122496486/220795542-750bb193-0778-46bc-8a1a-7e2a27b581d4.png)
