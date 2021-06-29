# What is Git?! :nerd_face:

- Git is a DVCS([Distributed Version Control systems](https://en.wikipedia.org/wiki/Distributed_version_control)) that stores data in a file system made up of snapshots. 
Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it.

- Git mostly relies on local operations because most necessary information can be found in local resources.

- Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. 

- Files in Git can reside in three main states: committed, modified and staged.

## Cloning

You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

'$ git clone https://github.com/test'

By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

To clone a repository into a directory with another name of your choosing, use the following command format:

'$ git clone https://github.com/test mydirectory'


## Vs Code

The idea is to be able to now open and make changes to the file on a local machine using Vs code in our case.

use the command 'code .' in the terminal. This should open up Vs code

## ACP process (ADD,COMMIT,PUSH)

As a remember, the traditional way of adding a file to a repository using the command line is summarized into 3 steps as follow:

### Step 1:Open the terminal.

- Change the current working directory to your local repository using the CD command.

- Stage the file for commit to your local repository by the following command.

  '$ git add .'
  
### Step 2: Commit the file that you’ve staged in your local repository.

   '$ git commit -m "Add existing file"'
   
### Step 3: Push the changes in your local repository to GitHub.

   '$ git push origin branch-name'
   
   ***
   
[**Home**](https://slayerr1.github.io/reading-notes/)
