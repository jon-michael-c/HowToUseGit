# How to use Git via Terminal
*NOTE: I am aware that Git works on CMD in Windows, but I choose to use git-scm because it has a nice feature where you can open the terminal in any directory by right clicking.*

In order to use Git, you must be able to push and pull from either a GUI or a terminal based client. My example will use the terminal. I downloaded Git for Windows at https://git-scm.com/ which I installed on my PC. 
![image](https://user-images.githubusercontent.com/44344714/125536359-6782a3a9-d031-483c-a459-66f879ed0ba9.png)


I created a repository on github.com and created the repository with this `README.MD` file. I then cloned the repository by running the command `git clone https://github.com/vincentmsinatra/CISC3140.git` in my Git terminal.
![image](https://user-images.githubusercontent.com/44344714/125536615-b26ced87-d767-4c81-897a-3f5faf164b87.png)


I then ran the command `cd` to move me into the directory of the repository that I had just cloned
![image](https://user-images.githubusercontent.com/44344714/125536724-12a79f1b-a4cd-492c-99e5-d65936046873.png)


I intitalized my Git repository using the  `git init` command
![image](https://user-images.githubusercontent.com/44344714/125537098-49ba1824-4c07-4f60-af7e-3212753b56de.png)


Furthermore, I ran the command `git add File.txt` to add my text file that includes a few lines of text.
![image](https://user-images.githubusercontent.com/44344714/125536962-babf815d-7340-41f1-9c00-6947e2967db1.png)


I will now run `git commit -m "First Commit"` to commit changes in the repository with the comment "First Commit"
![image](https://user-images.githubusercontent.com/44344714/125537676-f718331d-3501-4576-b3c7-f75ae1c32805.png)


I then set the origin of the repository to the repositories URL
![image](https://user-images.githubusercontent.com/44344714/125537921-90bcc40c-4b96-4677-a37b-664c870023b7.png)


Lastly, I ran the command `git push -u origin` to push the file `FILE.txt` to the repo.
![image](https://user-images.githubusercontent.com/44344714/125538344-933737d6-e27e-4905-a623-cbe886bebcce.png)


The original file reads "I am a file. I store Unicode characters as data." as seen below.
![image](https://user-images.githubusercontent.com/44344714/125538595-cfdcfce2-9b73-4bce-afec-6a31481e5d99.png)




I edited the file to include another line.
![image](https://user-images.githubusercontent.com/44344714/125538743-e6c42590-e80c-4062-b8f1-66f90ee073a4.png)


I will now add and push the file along with this `README.md` file.
![image](https://user-images.githubusercontent.com/44344714/125539642-05a1c2db-2db2-4d9e-a6a8-f2a6afe85033.png)


We are now done.
