# Session 3

Ehaab 1 : Write a Software for "Chatting Online" similar to Skype

Gates : "He will also Join with you write Code.

Specification on white Board :

Chat will have following.

5 files.

Able to Login : E : F1. Bugs : You have modified something F1.BugFixed
Abe to Add Contact :  G : F2
Accept New User Request : G : F3
Access Mic and Camera : G : F4
Send Output to Speaker : E : F5

Send a mail to Gate with whatever you have done ( F1)
Gates will take F1 and he will write some code to accepts new user rquests after Successful Login.
Gates will send you the update code to Ehaab via Email. F1.1

Will Ehaab will work on F1.1 or F1.BugFixed=>  F1.BugFixed => 

Imagine a Team who works with 1000 people.

Email : Channel :
Does it know who commits what ?
Is it intlligent enough to automatically merge ?
Is it possible to see the commit history by the whole team ?
Is file type is safe to transmit ?
If the file initial owner ?
Email Server Down?. Laptop Crashed. ? Where is my all code ?

Source Control Management : 

Technology
Subversion
TFS : Team Foundation Server : Encouraged Developers to Stop using and then move git
VSS : Visual Source Safe from Microsoft

Checkout : Get a Copy from Server
CheckIN :  Save the Copy in Server ?. Why i need to do this ?

the next day, developer comes, he can ask the server who have committed recently and give me a copy.



Distributed Source Control

GitHub created a WebSite based on Git and Provided free server to put the source repository.

Today’s world, Software is eating the world ?. Because of Open Source through GitHub,GitLab

GitHub.com => 

===============================

clone : Clone a new repository to Local from Server

clone the latest code :

.git

```
2022-01-02, c45690 User1 Committed ; 2000 file changes committed.

commit-id : c45676

2022-01-01, User1 Committed : config.js
..
..
..
..

commit-id : c45671

2022-01-01, User2 Committed : settings.js : 300 developers committed
..
..
..
..

```



git checkout c45671

?

My Entire folder will go to a timeline as of 2022-01-01 : 

settings.js
config.js
Folder

====================================================



Workspace : Local Folder is call workspace
checkout : 
commit : Commit is a flag saying that i am done with my work. Please don;t track anymore. Laptop local workspace history

then want to work on again : comitting

First Commit : Created Folder
Second Commit : Added Chat Logic
Third Commit : deleted some important lines accindelty : committed.
Fourth Commit : 



git logs chat.js
first
second
third commit



push : => Code sent to Server from Local Laptop with 4 commit messages.



clone
checkout
commit
push
branch

main/master
dev
feature-login
feature-emoji
release >

feature-login will be merged to dev.
release branch from dev
merge to final main branch









