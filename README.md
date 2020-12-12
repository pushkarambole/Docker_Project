# Docker Project

## Steps for executing the project:
1. Download the project zip file 'Docker_Project.zip' and extract it using unzip command:- unzip Docker_Project.zip
2. Navigate to the same extracted folder using cd command:- cd Docker_Project
3. Extract the image from tar file 'pushkarcode.tar' using the command:- docker load < pushkarcode.tar
4. Run the image and provide the directory path having .txt files using the bind mount command:-   docker run -it -v <YOUR DIRECTORY PATH HAVING .txt FILES>:/home/data/ pushkarfinal
	
## Sample output:-
docker run -it -v /home/pushkarambole/test:/home/data pushkarfinal

This is Pushkar Sadashiv Ambole
List of files with their respective count:
test.txt        4
pushkar.txt       8

File pushkar.txt having maximum words as: 8
Total number of words in all files: 12
Host name: f145cad8de6c
Host IP: 172.17.0.2
Executed on: 2019-11-02 20:52:39:702221
**********************************************
