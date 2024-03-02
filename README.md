1. This is a CNN based model to classify cat v dog
2. The model is trained on GPU of Google colab. Since this is a free version, you're allowed to use GPU only limited times per day.
3. The model is trained 20000 data points and tested on 5000 data points. The accuracy of model is above 82%

* Bash commands can be run directly in Jupyter Notebook without importing os library.
Here are some common bash commands that can be run on a Jupyter Notebook by adding ! before the command:
1. !ls - list all files in the current directory
2. !mkdir kaggle_1  -> makes a directory named as kaggle_1 inside content folder
3. !mkdir -p ~/.kaggle_3  -> makes a directory named as kaggle_3 inside root folder

**
mkdir -p is a command in Linux and Unix-like operating systems used to create a new directory. The -p option stands for "parent" and it allows you to create a directory hierarchy (a tree of directories) in one step, without getting an error if the parent directories already exist.  
**

mkdir -p mydir/subdir1/subdir2

**This will create the directory mydir if it doesn't already exist, and then create subdir1 and subdir2 within it, even if subdir1 also doesn't exist. The -p option ensures that the whole hierarchy of directories is created in one step, without any errors.
**
**The command mkdir ~/. creates a hidden directory in the home directory of the current user. The tilde (~) character is a shortcut for the home directory, so ~/. is equivalent to /home/username/., where username is the name of the current user.
Hidden directories are directories that do not appear in the normal directory listing. To view hidden directories, you need to use the ls -a command.
Hidden directories are often used to store files that are not meant to be seen by other users, such as configuration files and temporary files.
**
