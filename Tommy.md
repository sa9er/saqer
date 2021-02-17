# Welcome to my portfolio

## console commands

### cmd 
`mkdir` create folder  
`cd ..` get folder up  
`type test.txt ` prints the file  
`type a.txt b.txt ` prints two files  
`type a.txt b.txt > ab.txt ` combine two files and writes output to new file  
`echo "hello world" > test.txt` creats file with content   
`echo "hello world" >> test.txt` adds text to file  
`copy test.txt testBACKUP.txt` copys a file in the same directory    
`copy test.txt ../` copys a file one directory up  
`move test.txt testBACKUP.txt` renames the file    
`move Downloads/CV.pdf Dowcuments/` moves the file with same name  
`move Downloads/CV.pdf Dowcuments/CV_Ahmad.pdf` moves and rename the file   
`del test.txt` deletes the file  
`echo %TIME% Today is %DATE% >> combined.txt` prints datetime to file (between the % you can add the text that you like)    

### git
#### initially
`git init` initialies a empty von git retracktes repository - locally

#### basic workflow
`git status` shows the the state of the folder (if its connected to git or not)  
`git add` set the file to be staged afterwards (the will be considered with the next commit) 
`git add .` set all the files to be staged afterwards (the will be considered with the next commit) 
`git commit -m "YOUR CUSTOM MESSSAGE"` it commits the staged files locally  
`git push`   
`git diff`   shows the changes  


### installation
- point 1
- point 2
- etc
- etc

### deployement
1. something
2. in 
3. a order
<<<<<<< HEAD
4. another"stupid things " 
"stupid things " 
=======
4. another"smart things" 
>>>>>>> feature
