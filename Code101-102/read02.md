___

# Version Control Definition
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes or in another way its a flow control of project

# Types of Version Control
1. **Local Version Control:** Database on your hard disk that stores changes to files.
2. **Centralized Version Control:** This system entails a single server storing all changes and file versions, which can be accessed by various clients.
3. **Distributed Version Control:** DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

# Definition of Git

It's DVCS when you commit repo it takes a snapshot of data used for  local operations and save from lost of data and files in it can reside in three main states: committed, modified and staged.

# Commands of Git
  
  * **Status** :To determine the state of files
  
  ```markdown
    git status
  ```
  
  * **Clone**: you have a copy of all versions of all files for a project and used for a single time
  
  ```markdown
    git clone https://github.com/test 
  ```
  
## The A-P-C Process
  
  * **Add** :  these repository files
  
  ```markdown
    git add .
  ```
  
  *  **Commit** : Update changes.

  ```markdown
    git commit -m “any message here”
  ```
  
  * **Push** : push changes to a remote repository.
  
  ```markdown
    git push origin master
  ```
 
## Fetch and Merge Process
  
  **Pull** : Pull changes and merge the new changes
  
  ```markdown
    git pull
  ```

<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
