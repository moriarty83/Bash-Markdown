
# Bash Cheatsheet

> It is possible to fly without motors,
> but not without knowledge and skill.
>
>**Wilbur Wright**

## Basic Commands


### Navigation
![I'm Lost Meme](https://memegenerator.net/img/instances/55198523/im-lost.jpg)
- Print Working Directory

    `pwd`

- Change Directory

    `cd Path`

- Go to Home Directory

    `cd ~`

- Go to Root Directory

    `cd /`

- Go to Parent Directory

    `cd ..`

#### Navigation Tricks
1. Use Tab to auto complete folder & file names.
2. Use a slash to navigate to child directories.
3. Tab can be used to auto complete in child directories.
4. Use "\" before a space in a file name, e.g. "This\ Folder" for a folder called This Folder.

### Show Me the Files \(And Folders)
![The Files are in the Computer](https://memegenerator.net/img/instances/67870883/its-so-simple-the-files-are-in-the-computer.jpg)
* List Items in Current Directory

    <code>ls</code>

* Modifiers
    * Include Hidden Files

        <code>-a</code>

    * Include Permissions

        <code>-la</code>

        Note: Every 3 Characters refers to the Owner, then Group, then All Other Users

    * Change file size formatting

        `-h`

### Making Folders and Files
![Dogs Filepath Meme](https://i.kym-cdn.com/entries/icons/original/000/024/652/folder.jpg)
* Make a Folder

    `mkdir foldername`

* Make a File

    `touch filename`

#### Cool tip: you can string together commands with &&

`cd Folder && mkdir Folder2`

### Move, Copy, Rename
![Moving Day Meme](https://64.media.tumblr.com/a1f578eeec516f4a7d2a9e56a0344427/71cb223ca9bb0aff-d1/s1280x1920/8d3bb26c5cf7ac303ccf57ff464282f68dc0c14f.jpg)

* Move Files & Folders

    `mv fileToMoveDirectory NewDirectory`

* Rename Files & Folders

    Tip: Just use mv, keep the directory the same but change the file name

    `mv fileToRenameDirectory sameOrNewDirectory/NewName`

* Copy Files and Folders
    
    `cp fileToCopy Directory`

Tip: You can use the '*' as a wildcard. So *.txt will find all txt files.

### Deleting Files and Folders
![Delete Meme](https://starecat.com/content/wp-content/uploads/delete-folder-dicaprio-memes-are-you-sure-that-you-want-to-delete-dialog-box.jpg)
* Delete a File
    
    `rm fileToDelete`

* Delete a Folder
    
    `rm -r FolderToDelete`

    **WARNING**: The '-r' means to delete all child directories. ***BE CAREFUL*** about which directory you're in when you run this command.

### Other intersting Commands

![Interesting Meme](https://memegenerator.net/img/instances/68355894/wow-thats-interesting.jpg)

* Manual

`man CommandName`

Try using the manual command on some of these:

|Command    |Function   |
|---        |---        |
|grep       |Search     |
|locate     |Locate Directory|
|less       |View text file contents|
|cat        |Display, Combine, Create files|
| \|         |Pipe, takes the out put of one command as an argument for another|
|head       |Read the start of a file|

