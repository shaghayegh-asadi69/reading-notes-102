# Markdown: 5th June 2023

## _Notes from 0.1 Pre-Reading_

*Sarah Woolsey*

[Getting Started](https://www.markdownguide.org/getting-started/)
[Markdown Basic Syntax](https://www.markdownguide.org/basic-syntax/)
[Mastering Markdown on Github](https://guides.github.com/features/mastering-markdown/)
[Getting Started with Github Pages](https://guides.github.com/features/pages/)
[Github Pages](https://pages.github.com/)
[Writing & Formatting syntax](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)

***What is Markdown?***
Gruber's Markdown language is a simple way of writing and formatting text that can be easily converted to HTML, to create websites. It's a special code that lets you add basic formatting, such as headers, lists, and links, to your text without needing to know complicated coding. It's a handy tool for quickly creating content that looks nice on the web without fussing over complex technical details.

***Why do we use Markdown?***
Markdown language offers several benefits:

1. _Ease of use_: Markdown is designed to be simple and intuitive, making it easy for anyone to quickly write and format text without the need for extensive coding knowledge.

2. _Platform independence_: Markdown files can be opened and read on any text editor or platform, ensuring compatibility across different devices and operating systems.

3. _Portability_: Markdown files are lightweight and can be easily shared and transferred between different systems, making it convenient for collaboration and document sharing.

4. _Human-readable_: Markdown files are written in plain text, making them easily readable even without rendering. This ensures that the content remains accessible and legible regardless of the software or platform being used.

5. _HTML conversion_: Markdown can be effortlessly converted into HTML, allowing users to create web content or format text for online publishing without the need to learn complex web development languages.

6. _Focus on content_: Markdown encourages writers to focus on the content itself rather than getting caught up in complex formatting or design details, promoting a more streamlined and efficient writing process.

7. _Widespread adoption_: Markdown has gained significant popularity and is supported by numerous applications, websites, and platforms, making it a widely recognized and accepted standard for text formatting.

***What symbol will create a heading in Markdown?***
The # symbol denotes the size of the header. The more hashtags, the smaller the header.

***How many do you need to create the largest heading?***
One
***How many do you need to create the smallest heading?***
Six

***When making text bold or italicized for emphasis, it is best practice to use which symbol?***
The asterix *

***How do you create a link with Markdown?***
 Enclose the link text in brackets (e.g., [Google Mail]) and then follow it immediately with the URL in parentheses (e.g., (<https://gmail.com>)).

***What are the three symbols you can use to create an unordered (bulleted) list with Markdown?***
Asterixes, hyphens and plus signs

![Completed](https://www.onlygfx.com/wp-content/uploads/2018/04/completed-stamp-4.png)


## What is Version Control?

> Version Control is a system that records and manages changes to files over time. It allows multiple people to collaborate on a project by keeping track of modifications made to the files, providing a history of changes, and enabling the ability to revert to previous versions if needed. Version control systems also facilitate branching, merging, and concurrent work on different parts of the project.

## What is cloning in Git?

> In the context of Git, cloning refers to the process of creating a copy of a repository from a remote source, such as a Git server or another local repository. The clone command in Git allows you to fetch the entire repository, including all its files, commit history, and branches, onto your local machine. This enables you to work on the project independently and synchronize changes with the remote repository when necessary.

## What is the command to track and stage files?

> The command to track and stage files in Git is git add. This command is used to add files to the staging area, which is a preparatory step before committing changes. By staging files, you are indicating that you want to include them in the next commit. For example, git add filename.txt would add the file named "filename.txt" to the staging area.

## What is the command to take a snapshot of your changed files?

> To take a snapshot of your changed files in Git, you use the command git commit. This command creates a new commit with a unique identifier that represents a snapshot of the changes you have staged. When executing git commit, you typically provide a commit message that describes the changes made. For example, git commit -m "Added new feature" would create a commit with the message "Added new feature."

## What is the command to send your changed files to Github?

**git add .** : This command stages all the modified and new files in the current directory and its subdirectories.

**git commit -m** "Commit message": This command creates a commit with a message describing the changes made.

**git push origin branch-name:** This command sends the committed changes to the remote repository, specifically to the branch named "branch-name." The "origin" refers to the remote repository's name, such as the GitHub repository you want to push to.


# Ubuntu-Git (Local-Remote) Text Editor & Commands

## **Four important features to look for in a text editor are:**

- **User-friendly interface:** A good text editor should have an intuitive and easy-to-use interface, allowing users to navigate and edit text efficiently.

- **Syntax highlighting:** This feature helps to visually distinguish different elements in the code by applying different colors or formatting to keywords, variables, and other language-specific constructs. It improves readability and reduces errors.

- **Auto-completion:** Auto-completion suggests or completes code snippets as you type, based on the context or predefined templates. It saves time and helps in writing correct code.

- **Plugins and extensibility:** A text editor with a rich ecosystem of plugins and extensions allows users to customize and extend its functionality according to their needs, such as adding linters, version control integration, or additional language support.

## *As for the command line commands:*

- **pwd:** It stands for "print working directory." When executed, it displays the current directory (folder) path where you are located.

- **ls:** This command lists the files and directories (folders) in the current directory.

- **cd:** It stands for "change directory." This command allows you to navigate between directories. For example, cd projects would move you into the "projects" directory.

- **mkdir:** This command is used to create a new directory. For instance, mkdir new-project would create a directory named "new-project."

- **touch:** This command is used to create a new file. For example, touch new-project/newfile.md would create a file named "newfile.md" within the "new-project" directory.

## In the given scenario, the following commands and arguments are entered into the command line

- **cd projects:** This command changes the current directory to the "projects" directory.

- **mkdir new-project:** This command creates a new directory named "new-project" within the "projects" directory.

- **touch new-project/newfile.md:** This command creates a new file named "newfile.md" within the "new-project" directory.

- **cd:** This command moves back to the parent directory.

- **ls projects/new-project:** This command lists the files and directories inside the "new-project" directory within the "projects" directory.
