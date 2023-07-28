# Git Ignore Plugin

## Introduction
This Git plugin allows you to quickly add files or directories to your `.gitignore` file directly from your terminal. 

The plugin provides the following commands:

- `git ignore add`, that appends a specified file or directory to your `.gitignore` file
- `git ignore show`, that shows the contents of your `.gitignore` file

## Installation
Follow these steps to install the plugin:

1. Clone this repository.
2. Navigate to the directory containing the `git-ignore` script.
3. Make the script executable by running the command `chmod +x ./git-ignore`.
4. Move the script to a directory that's in your system's PATH. You can view the directories in your PATH by running `echo $PATH`. A common place to put it is `/usr/local/bin`. You can move it there by running `mv git-ignore /usr/local/bin/`.

## Usage

### add
To add a file, directory, or pattern to your `.gitignore`, use the command:

```bash
git ignore add [file/directory/pattern]
```

Replace `[file/directory/pattern]` with the name of the file, directory, or pattern you want to ignore.

Please note, this command only adds entries to the `.gitignore` file, it does not stage or commit changes. You'll need to manually stage and commit changes to the `.gitignore` file after running this command.

### show
To show the contents of your `.gitignore` file:

```bash
git ignore show
```

## Contributing
Contributions to the Git Ignore Plugin are welcome and appreciated. Here are the steps to contribute:

1. Fork this repository.
2. Create a new branch for your changes.
3. Make your changes in your branch.
4. Submit a pull request with a description of your changes.

Please make sure to test your changes thoroughly before submitting a pull request.
