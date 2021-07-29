
# Bash Cheatsheet
This document contains a quick reference for using bash/Terminal.

## Basic Commands
> It is possible to fly without motors,
> but not without knowledge and skill
>**Wilbur Wright**

### Navigation
- Print Working Directory
    
```console
foo@bar:~$ whoami
foo
```

- Go to Home Directory

    <code>cd ~</code>

- Go to Root Directory

    <code>cd /</code>

- Go to Parent Directory

    <code>cd ..</code>

#### Navigation Tricks
1. Use Tab to auto complete folder & file names.
2. Use a slash to navigate to child directories.
3. Tab can be used to auto complete in child directories.

### Show Me the Files \(And Folders)
* List Items in Current Directory

    <code>ls</code>

* Add-Ons
    * Include Hidden Files

        <code>-a</code>

    * Include Permissions

        <code>-la</code>

    * Change file size formatting

        <code>-h</code>