𝐃𝐚𝐲 𝟏 𝐃𝐞𝐯𝐎𝐩𝐬 𝐋𝐞𝐚𝐫𝐧𝐢𝐧𝐠 𝐁𝐥𝐨𝐠 : 𝐆𝐢𝐭, 𝐆𝐢𝐭𝐇𝐮𝐛, 𝐆𝐢𝐭 𝐖𝐨𝐫𝐤𝐟𝐥𝐨𝐰, 𝐋𝐢𝐧𝐮𝐱 𝐂𝐨𝐦𝐦𝐚𝐧𝐝𝐬, 𝐚𝐧𝐝 𝐒𝐒𝐇 𝐀𝐮𝐭𝐡𝐞𝐧𝐭𝐢𝐜𝐚𝐭𝐢𝐨𝐧. 


                            𝘿𝙖𝙮 1 — 𝙂𝙞𝙩 𝙖𝙣𝙙 𝙂𝙞𝙩𝙃𝙪𝙗 𝙁𝙪𝙣𝙙𝙖𝙢𝙚𝙣𝙩𝙖𝙡𝙨

### 1\. ɪɴᴛʀᴏᴅᴜᴄᴛɪᴏɴ ᴛᴏ ɢɪᴛ ᴀɴᴅ ɢɪᴛʜᴜʙ

Git and GitHub are essential tools in DevOps. They help developers track code changes, collaborate with others, and maintain a history of their projects.

* 𝙶𝚒𝚝: A 𝘷𝘦𝘳𝘴𝘪𝘰𝘯 𝘤𝘰𝘯𝘵𝘳𝘰𝘭 𝘴𝘺𝘴𝘵𝘦𝘮 that tracks changes in files on 𝘺𝘰𝘶𝘳 𝘤𝘰𝘮𝘱𝘶𝘵𝘦𝘳.

* 𝙶𝚒𝚝𝙷𝚞𝚋: An 𝘰𝘯𝘭𝘪𝘯𝘦 𝘱𝘭𝘢𝘵𝘧𝘰𝘳𝘮 𝘵hat hosts Git repositories and enables collaboration.

For example, suppose you create a portfolio website. You can use Git to track every change you make and GitHub to store your code online.

### 2\. ᴜɴᴅᴇʀsᴛᴀɴᴅɪɴɢ ᴛʜᴇ ɢɪᴛ ᴡᴏʀᴋꜰʟᴏᴡ

ᴡᴏʀᴋɪɴɢ ᴅɪʀᴇᴄᴛᴏʀʏ

Create or modify files

`ɢɪᴛ ᴀᴅᴅ`

Staging Area

Select changes for the next commit

`ɢɪᴛ ᴄᴏᴍᴍɪᴛ`

Local Repository

Saved version history on your computer

`ɢɪᴛ ᴘᴜsʜ`

Remote Repository (GitHub)

Code and history stored online

Getting changes from GitHub

`ɢɪᴛ ꜰᴇᴛᴄʜ` downloads remote information without integrating it into your current branch.

`ɢɪᴛ ᴘᴜʟʟ` fetches and integrates remote changes into your current branch.

### ᴡʜᴀᴛ ᴇᴀᴄʜ sᴛᴀɢᴇ ᴍᴇᴀɴs

1\. Working Directory: The working directory is the place where we create, edit, and delete files in our project.

2\. Staging Area: The staging area is where we prepare and select the changes that we want to include in the next commit using the `git add` command.

3\. Local Repository: The local repository is where Git stores the committed versions of our project on our local computer.

4\. Remote Repository: The remote repository is a repository hosted on a remote server or platform, such as GitHub, where we can store and share our project with others.

Important corrections to your handwritten diagram:

* `git checkout` is not simply the reverse of `git commit`. It is used to switch branches or restore files, depending on the command. Modern Git also provides `git switch` and `git restore`.

* `git merge` combines changes from one branch into another. It is not the same as moving files into the working directory.

* `git pull` updates your current local branch using remote changes. It does not simply copy files into the local repository.

### 3\. ᴡɪɴᴅᴏᴡs ᴛᴇʀᴍɪɴᴀʟs ᴀɴᴅ ʟɪɴᴜx ᴄᴏᴍᴍᴀɴᴅs

1\. Command Prompt (CMD): Command Prompt is a Windows command-line interface used to execute commands and perform basic system operations.

2\. PowerShell: PowerShell is a Windows command-line shell that supports advanced commands, automation, and scripting.

3\. Git Bash: Git Bash provides a Bash shell and many Unix-style commands on Windows, making it useful for working with Git.

4\. WSL (Windows Subsystem for Linux): WSL allows users to run a Linux environment, such as Ubuntu, directly on Windows.

Note: PowerShell is not a Linux terminal by itself, whereas Git Bash and WSL provide Linux-style command environments on Windows.

### ᴄᴏᴍᴍᴏɴ ᴄᴏᴍᴍᴀɴᴅs
1\. Create a folder: The `mkdir gc-dev` command creates a new folder named `gc-dev`.

2\. Enter a folder: The `cd gc-dev` command moves into the `gc-dev` folder.

3\. List files in CMD/PowerShell: The `dir` command displays the files and folders in the current directory.

4\. List files in Bash: The `ls` command displays the files and folders in the current directory.

5\. Display a file in Bash: The `cat file.txt` command displays the contents of the `file.txt` file in the terminal.

6\. Display the current folder: The `pwd` command displays the full path of the current working directory.

7\. Clear the terminal: The `clear` command clears the terminal screen in Bash, while the `cls` command clears the screen in CMD and PowerShell.

### 4\. ᴡsʟ — ᴡɪɴᴅᴏᴡs sᴜʙsʏsᴛᴇᴍ ꜰᴏʀ ʟɪɴᴜx

WSL allows you to run a Linux distribution, such as Ubuntu, directly on Windows without needing a traditional separate Linux computer.

### ᴄᴏᴍᴍᴀɴᴅs ꜰʀᴏᴍ ʏᴏᴜʀ ɴᴏᴛᴇs

𝘾𝙝𝙚𝙘𝙠 𝙒𝙎𝙇 𝙨𝙩𝙖𝙩𝙪𝙨:

```𝙗𝙖𝙨𝙝
𝙬𝙨𝙡 --𝙨𝙩𝙖𝙩𝙪𝙨
```

𝙇𝙞𝙨𝙩 𝙞𝙣𝙨𝙩𝙖𝙡𝙡𝙚𝙙 𝙙𝙞𝙨𝙩𝙧𝙞𝙗𝙪𝙩𝙞𝙤𝙣𝙨:

```𝙗𝙖𝙨𝙝
𝙬𝙨𝙡 --𝙡𝙞𝙨𝙩 --𝙫𝙚𝙧𝙗𝙤𝙨𝙚
```

𝙊𝙥𝙚𝙣 𝙐𝙗𝙪𝙣𝙩𝙪:

```𝙗𝙖𝙨𝙝
𝙬𝙨𝙡 -𝙙 𝙐𝙗𝙪𝙣𝙩𝙪
```

𝙀𝙭𝙞𝙩 𝙩𝙝𝙚 𝙇𝙞𝙣𝙪𝙭 𝙨𝙝𝙚𝙡𝙡:

```𝙗𝙖𝙨𝙝
𝙚𝙭𝙞𝙩
```

The distribution name must match one of the installed distributions. For example, it might be `Ubuntu` or `Ubuntu-24.04`.

### 5\. ᴄʀᴇᴀᴛɪɴɢ ꜰɪʟᴇs ᴀɴᴅ ᴡʀɪᴛɪɴɢ ᴄᴏɴᴛᴇɴᴛ ɪɴ ʟɪɴᴜx

Your notes include `cat`, `echo`, and file creation. These are useful commands for practicing Git.

𝘾𝙧𝙚𝙖𝙩𝙚 𝙖 𝙛𝙤𝙡𝙙𝙚𝙧 𝙖𝙣𝙙 𝙚𝙣𝙩𝙚𝙧 𝙞𝙩:

```𝙗𝙖𝙨𝙝
𝙢𝙠𝙙𝙞𝙧 𝙜𝙘-𝙙𝙚𝙫
𝙘𝙙 𝙜𝙘-𝙙𝙚𝙫
```

𝘾𝙧𝙚𝙖𝙩𝙚 𝙖𝙣 𝙚𝙢𝙥𝙩𝙮 𝙛𝙞𝙡𝙚:

```𝙗𝙖𝙨𝙝
𝙩𝙤𝙪𝙘𝙝 𝙩𝙚𝙨𝙩.𝙩𝙭𝙩
```

𝙒𝙧𝙞𝙩𝙚 𝙩𝙚𝙭𝙩 𝙞𝙣𝙩𝙤 𝙖 𝙛𝙞𝙡𝙚, 𝙧𝙚𝙥𝙡𝙖𝙘𝙞𝙣𝙜 𝙞𝙩𝙨 𝙚𝙭𝙞𝙨𝙩𝙞𝙣𝙜 𝙘𝙤𝙣𝙩𝙚𝙣𝙩:

```𝙗𝙖𝙨𝙝
𝙚𝙘𝙝𝙤 "𝙃𝙚𝙡𝙡𝙤 𝙒𝙤𝙧𝙡𝙙" > 𝙩𝙚𝙨𝙩.𝙩𝙭𝙩
```

𝘿𝙞𝙨𝙥𝙡𝙖𝙮 𝙩𝙝𝙚 𝙘𝙤𝙣𝙩𝙚𝙣𝙩𝙨:

```𝙗𝙖𝙨𝙝
𝙘𝙖𝙩 𝙩𝙚𝙨𝙩.𝙩𝙭𝙩
```

𝘼𝙥𝙥𝙚𝙣𝙙 𝙖𝙙𝙙𝙞𝙩𝙞𝙤𝙣𝙖𝙡 𝙩𝙚𝙭𝙩 𝙬𝙞𝙩𝙝𝙤𝙪𝙩 𝙙𝙚𝙡𝙚𝙩𝙞𝙣𝙜 𝙩𝙝𝙚 𝙚𝙭𝙞𝙨𝙩𝙞𝙣𝙜 𝙘𝙤𝙣𝙩𝙚𝙣𝙩:

```𝙗𝙖𝙨𝙝
𝙚𝙘𝙝𝙤 "𝙇𝙚𝙖𝙧𝙣𝙞𝙣𝙜 𝙂𝙞𝙩 𝙤𝙣 𝘿𝙖𝙮 1" >> 𝙩𝙚𝙨𝙩.𝙩𝙭𝙩
```

𝙀𝙙𝙞𝙩 𝙖 𝙛𝙞𝙡𝙚 𝙞𝙣𝙩𝙚𝙧𝙖𝙘𝙩𝙞𝙫𝙚𝙡𝙮 𝙪𝙨𝙞𝙣𝙜 𝙉𝙖𝙣𝙤, 𝙞𝙛 𝙞𝙣𝙨𝙩𝙖𝙡𝙡𝙚𝙙:

```𝙗𝙖𝙨𝙝
𝙣𝙖𝙣𝙤 𝙩𝙚𝙨𝙩.𝙩𝙭𝙩
```

𝙍𝙚𝙢𝙚𝙢𝙗𝙚𝙧: `>` 𝙤𝙫𝙚𝙧𝙬𝙧𝙞𝙩𝙚𝙨 𝙩𝙝𝙚 𝙛𝙞𝙡𝙚, 𝙬𝙝𝙞𝙡𝙚 `>>` 𝙖𝙥𝙥𝙚𝙣𝙙𝙨 𝙩𝙤 𝙞𝙩. 𝙔𝙤𝙪𝙧 𝙣𝙤𝙩𝙚𝙨' `𝙘𝙖𝙩 > 𝙛𝙞𝙡𝙚.𝙩𝙭𝙩` 𝙢𝙚𝙩𝙝𝙤𝙙 𝙖𝙡𝙨𝙤 𝙬𝙤𝙧𝙠𝙨 𝙞𝙣 𝘽𝙖𝙨𝙝; 𝙥𝙧𝙚𝙨𝙨 `𝘾𝙩𝙧𝙡+𝘿` 𝙬𝙝𝙚𝙣 𝙛𝙞𝙣𝙞𝙨𝙝𝙚𝙙 𝙚𝙣𝙩𝙚𝙧𝙞𝙣𝙜 𝙩𝙝𝙚 𝙩𝙚𝙭𝙩.

### 6\. 𝙞𝙣𝙞𝙩𝙞𝙖𝙡𝙞𝙯𝙚 𝙖 𝙜𝙞𝙩 𝙧𝙚𝙥𝙤𝙨𝙞𝙩𝙤𝙧𝙮

𝙂𝙞𝙩 𝙣𝙚𝙚𝙙𝙨 𝙖 𝙧𝙚𝙥𝙤𝙨𝙞𝙩𝙤𝙧𝙮 𝙩𝙤 𝙩𝙧𝙖𝙘𝙠 𝙘𝙝𝙖𝙣𝙜𝙚𝙨 𝙞𝙣 𝙖 𝙥𝙧𝙤𝙟𝙚𝙘𝙩.

𝘾𝙧𝙚𝙖𝙩𝙚 𝙖 𝙥𝙧𝙤𝙟𝙚𝙘𝙩 𝙛𝙤𝙡𝙙𝙚𝙧:

```𝙗𝙖𝙨𝙝
𝙢𝙠𝙙𝙞𝙧 𝙜𝙘-𝙙𝙚𝙫
𝙘𝙙 𝙜𝙘-𝙙𝙚𝙫
```

𝙄𝙣𝙞𝙩𝙞𝙖𝙡𝙞𝙯𝙚 𝙂𝙞𝙩:

```𝙗𝙖𝙨𝙝
𝙜𝙞𝙩 𝙞𝙣𝙞𝙩
```

𝙏𝙝𝙞𝙨 𝙘𝙧𝙚𝙖𝙩𝙚𝙨 𝙖 𝙝𝙞𝙙𝙙𝙚𝙣 `.𝙜𝙞𝙩` 𝙙𝙞𝙧𝙚𝙘𝙩𝙤𝙧𝙮 𝙘𝙤𝙣𝙩𝙖𝙞𝙣𝙞𝙣𝙜 𝙂𝙞𝙩'𝙨 𝙧𝙚𝙥𝙤𝙨𝙞𝙩𝙤𝙧𝙮 𝙙𝙖𝙩𝙖 𝙖𝙣𝙙 𝙫𝙚𝙧𝙨𝙞𝙤𝙣 𝙝𝙞𝙨𝙩𝙤𝙧𝙮.

𝘾𝙝𝙚𝙘𝙠 𝙩𝙝𝙚 𝙧𝙚𝙥𝙤𝙨𝙞𝙩𝙤𝙧𝙮 𝙨𝙩𝙖𝙩𝙪𝙨:

```𝙗𝙖𝙨𝙝
𝙜𝙞𝙩 𝙨𝙩𝙖𝙩𝙪𝙨
```

Expected result: Git tells you which branch you are on and whether there are untracked or modified files.

Note: Newer Git installations may use `master` or `main` as the initial branch, depending on their configuration.

### 7\. ᴄᴏɴꜰɪɢᴜʀᴇ ɢɪᴛ

Your notes mention `git config` and connecting Git with GitHub.

Configure your author name and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Check your configuration:

```bash
git config --global --list
```

### What does this configuration do?

* `git config` manages Git settings.

* `--global` applies the setting to your user account across your repositories.

* `user.name` identifies the author of commits.

* `user.email` identifies the email recorded in commits.

Important: These settings identify you as the commit author. They do not authenticate you to GitHub. Authentication is handled separately using HTTPS credentials/tokens or SSH keys.

### Text editors in Linux and Windows

* Notepad: A basic Windows text editor.

* Vim/Vi: Terminal-based text editors commonly found on Linux.

* Nano: Another terminal-based text editor, often easier for beginners.

* VS Code: A graphical editor that can be integrated with Git.

In Vim, press `Esc`, type `:q!`, and press `Enter` to quit without saving. To save and quit, use `:wq`.

### 8\. Git staging — `git add`

Suppose you create `test.txt` in your project folder.

```𝙗𝙖𝙨𝙝
𝙚𝙘𝙝𝙤 "𝙇𝙚𝙖𝙧𝙣𝙞𝙣𝙜 𝙂𝙞𝙩" > 𝙩𝙚𝙨𝙩.𝙩𝙭𝙩
```

𝘾𝙝𝙚𝙘𝙠 𝙩𝙝𝙚 𝙨𝙩𝙖𝙩𝙪𝙨:

```𝙗𝙖𝙨𝙝
𝙜𝙞𝙩 𝙨𝙩𝙖𝙩𝙪𝙨
```

𝙂𝙞𝙩 𝙬𝙞𝙡𝙡 𝙞𝙙𝙚𝙣𝙩𝙞𝙛𝙮 `𝙩𝙚𝙨𝙩.𝙩𝙭𝙩` 𝙖𝙨 𝙖𝙣 𝙪𝙣𝙩𝙧𝙖𝙘𝙠𝙚𝙙 𝙛𝙞𝙡𝙚.

𝙎𝙩𝙖𝙜𝙚 𝙩𝙝𝙖𝙩 𝙨𝙥𝙚𝙘𝙞𝙛𝙞𝙘 𝙛𝙞𝙡𝙚:

```𝙗𝙖𝙨𝙝
𝙜𝙞𝙩 𝙖𝙙𝙙 𝙩𝙚𝙨𝙩.𝙩𝙭𝙩
```

𝙊𝙧 𝙨𝙩𝙖𝙜𝙚 𝙖𝙡𝙡 𝙘𝙝𝙖𝙣𝙜𝙚𝙨 𝙞𝙣 𝙩𝙝𝙚 𝙘𝙪𝙧𝙧𝙚𝙣𝙩 𝙙𝙞𝙧𝙚𝙘𝙩𝙤𝙧𝙮 𝙖𝙣𝙙 𝙞𝙩𝙨 𝙨𝙪𝙗𝙙𝙞𝙧𝙚𝙘𝙩𝙤𝙧𝙞𝙚𝙨:

```𝙗𝙖𝙨𝙝
𝙜𝙞𝙩 𝙖𝙙𝙙 .
```

𝘾𝙝𝙚𝙘𝙠 𝙖𝙜𝙖𝙞𝙣:

```𝙗𝙖𝙨𝙝
𝙜𝙞𝙩 𝙨𝙩𝙖𝙩𝙪𝙨
```

𝙏𝙝𝙚 𝙛𝙞𝙡𝙚 𝙨𝙝𝙤𝙪𝙡𝙙 𝙣𝙤𝙬 𝙖𝙥𝙥𝙚𝙖𝙧 𝙪𝙣𝙙𝙚𝙧 𝘾𝙝𝙖𝙣𝙜𝙚𝙨 𝙩𝙤 𝙗𝙚 𝙘𝙤𝙢𝙢𝙞𝙩𝙩𝙚𝙙.

𝙏𝙝𝙚 𝙨𝙩𝙖𝙜𝙞𝙣𝙜 𝙖𝙧𝙚𝙖 𝙡𝙚𝙩𝙨 𝙮𝙤𝙪 𝙘𝙝𝙤𝙤𝙨𝙚 𝙬𝙝𝙞𝙘𝙝 𝙘𝙝𝙖𝙣𝙜𝙚𝙨 𝙬𝙞𝙡𝙡 𝙗𝙚 𝙞𝙣𝙘𝙡𝙪𝙙𝙚𝙙 𝙞𝙣 𝙮𝙤𝙪𝙧 𝙣𝙚𝙭𝙩 𝙘𝙤𝙢𝙢𝙞𝙩.

### 9\. 𝙂𝙞𝙩 𝙘𝙤𝙢𝙢𝙞𝙩 — `𝙜𝙞𝙩 𝙘𝙤𝙢𝙢𝙞𝙩`

𝘼 𝙘𝙤𝙢𝙢𝙞𝙩 𝙨𝙖𝙫𝙚𝙨 𝙖 𝙨𝙣𝙖𝙥𝙨𝙝𝙤𝙩 𝙤𝙛 𝙮𝙤𝙪𝙧 𝙨𝙩𝙖𝙜𝙚𝙙 𝙘𝙝𝙖𝙣𝙜𝙚𝙨 𝙞𝙣 𝙩𝙝𝙚 𝙡𝙤𝙘𝙖𝙡 𝙧𝙚𝙥𝙤𝙨𝙞𝙩𝙤𝙧𝙮.

```𝙗𝙖𝙨𝙝
𝙜𝙞𝙩 𝙘𝙤𝙢𝙢𝙞𝙩 -𝙢 "𝘼𝙙𝙙 𝙞𝙣𝙞𝙩𝙞𝙖𝙡 𝙩𝙚𝙨𝙩 𝙛𝙞𝙡𝙚"
```

𝙃𝙚𝙧𝙚:

* `𝙜𝙞𝙩 𝙘𝙤𝙢𝙢𝙞𝙩` 𝙧𝙚𝙘𝙤𝙧𝙙𝙨 𝙩𝙝𝙚 𝙨𝙩𝙖𝙜𝙚𝙙 𝙘𝙝𝙖𝙣𝙜𝙚𝙨.

* `-𝙢` 𝙨𝙪𝙥𝙥𝙡𝙞𝙚𝙨 𝙖 𝙢𝙚𝙨𝙨𝙖𝙜𝙚 𝙙𝙚𝙨𝙘𝙧𝙞𝙗𝙞𝙣𝙜 𝙩𝙝𝙚 𝙘𝙝𝙖𝙣𝙜𝙚𝙨.

* `"𝘼𝙙𝙙 𝙞𝙣𝙞𝙩𝙞𝙖𝙡 𝙩𝙚𝙨𝙩 𝙛𝙞𝙡𝙚"` 𝙞𝙨 𝙩𝙝𝙚 𝙘𝙤𝙢𝙢𝙞𝙩 𝙢𝙚𝙨𝙨𝙖𝙜𝙚.

𝘼 𝙜𝙤𝙤𝙙 𝙘𝙤𝙢𝙢𝙞𝙩 𝙢𝙚𝙨𝙨𝙖𝙜𝙚 𝙙𝙚𝙨𝙘𝙧𝙞𝙗𝙚𝙨 𝙩𝙝𝙚 𝙘𝙝𝙖𝙣𝙜𝙚 𝙘𝙡𝙚𝙖𝙧𝙡𝙮.

𝙀𝙭𝙖𝙢𝙥𝙡𝙚𝙨:

```𝙗𝙖𝙨𝙝
𝙜𝙞𝙩 𝙘𝙤𝙢𝙢𝙞𝙩 -𝙢 "𝘼𝙙𝙙 𝙥𝙤𝙧𝙩𝙛𝙤𝙡𝙞𝙤 𝙝𝙤𝙢𝙚𝙥𝙖𝙜𝙚"
𝙜𝙞𝙩 𝙘𝙤𝙢𝙢𝙞𝙩 -𝙢 "𝙐𝙥𝙙𝙖𝙩𝙚 𝙍𝙀𝘼𝘿𝙈𝙀 𝙙𝙤𝙘𝙪𝙢𝙚𝙣𝙩𝙖𝙩𝙞𝙤𝙣"
𝙜𝙞𝙩 𝙘𝙤𝙢𝙢𝙞𝙩 -𝙢 "𝘼𝙙𝙙 𝘿𝙤𝙘𝙠𝙚𝙧𝙛𝙞𝙡𝙚"
```

𝘾𝙝𝙚𝙘𝙠 𝙩𝙝𝙚 𝙨𝙩𝙖𝙩𝙪𝙨 𝙖𝙛𝙩𝙚𝙧𝙬𝙖𝙧𝙙:

```𝙗𝙖𝙨𝙝
𝙜𝙞𝙩 𝙨𝙩𝙖𝙩𝙪𝙨
```

If all changes have been committed, Git will usually report that the working tree is clean.

### 10\. View Git history and tracked files

Your notes contain `git log`, `git ls-files`, and `git logg --`. These commands serve different purposes.

1\. `git log`: Displays the commit history of the repository, including commit IDs, authors, dates, and commit messages.

2\. `git log --oneline`: Displays the commit history in a compact format, with each commit shown on a single line.

3\. `git status`: Displays the current state of the working directory and staging area, showing which files are modified, staged, or untracked.

4\. `git ls-files`: Lists the files tracked by Git in the index.

5\. `git diff`: Displays the differences between the working directory and the staging area, showing changes that have not yet been staged.

6\. `git diff --staged`: Displays the differences between the staging area and the last commit, showing changes that are staged but have not yet been committed.

`git logg --` is not a standard Git command. You may have meant `git log --oneline` or an alias configured on your system.

Also, `git ls-files` does not show which files have been pushed to GitHub. It lists tracked files in your local repository's index.

### 11\. ᴄᴏɴɴᴇᴄᴛ ᴛʜᴇ ʟᴏᴄᴀʟ ʀᴇᴘᴏsɪᴛᴏʀʏ ᴛᴏ ɢɪᴛʜᴜʙ

To push your project online, you need a remote repository.

First, create a new repository on GitHub. Copy its repository URL.

For example:

`https://github.com/YOUR-USERNAME/gc-dev.git`

Add the remote:

```bash
git remote add origin https://github.com/YOUR-USERNAME/gc-dev.git
```

Here:

* `git remote add` adds a remote repository.

* `origin` is the conventional name given to that remote.

* The URL identifies the GitHub repository.

Check the remote:

```bash
git remote -v
```

This displays the URLs used for fetching and pushing.

If you accidentally configure the wrong URL, correct it with:

```bash
git remote set-url origin https://github.com/YOUR-USERNAME/gc-dev.git
```

Replace the example username with your actual GitHub username.

### 12\. Change the branch name to `main`

Your notes mention that your current branch was `master` and you wanted to change it to `main`.

Use:

```bash
git branch -M main
```

This renames the current branch to `main`.

Check the current branch:

```bash
git branch
```

The active branch is marked with an asterisk (`*`).

### 13\. Push your code to GitHub

After creating at least one commit and configuring the remote, push your branch:

```bash
git push -u origin main
```

Explanation:

* `git push` uploads local commits to the remote repository.

* `origin` identifies the remote.

* `main` identifies the branch to upload.

* `-u` sets the upstream branch so future pushes can usually use just `git push`.

On the first push, GitHub may ask you to authenticate. HTTPS and SSH have different authentication setups.

### 14\. SSH key authentication

SSH allows Git to authenticate to GitHub using a key pair instead of repeatedly entering credentials.

Private key

Stored on your local computer. Keep it secret and never upload or share it.

Public key

Added to your GitHub account so GitHub can verify your SSH authentication.

### Step 1: Generate an SSH key

Run this in Git Bash or a Linux terminal:

```bash
ssh-keygen -t ed25519 -C "your-email@example.com"
```

Press `Enter` to accept the default file location. You can set a passphrase for additional security.

### Step 2: Display and copy the public key

In Git Bash:

```bash
cat ~/.ssh/id_ed25519.pub
```

Copy the entire output, including the `ssh-ed25519` prefix.

On Windows, you can also copy the public key directly to the clipboard in Git Bash:

```bash
clip < ~/.ssh/id_ed25519.pub
```

Never copy or share `~/.ssh/id_ed25519` as your public key. That file is your private key.

### Step 3: Add the public key to GitHub

* Open GitHub and go to Settings.

* Open SSH and GPG keys.

* Select New SSH key.

* Enter a descriptive title, such as `My Windows Laptop`.

* Paste your public key and add it.

### Step 4: Test the connection

```bash
ssh -T git@github.com
```

If authentication succeeds, GitHub displays a greeting confirming that it recognized your account.

### Step 5: Use SSH for your repository

If you want to use SSH instead of HTTPS, set your repository remote to its SSH URL:

```bash
git remote set-url origin git@github.com:YOUR-USERNAME/gc-dev.git
```

Then push:

```bash
git push -u origin main
```

SSH keys provide authentication; they do not replace Git's commit, staging, or branch workflow.

### 15\. Pulling changes from GitHub

Before starting work, it is often helpful to synchronize your local branch with the remote branch.

```bash
git pull origin main
```

This fetches remote changes and integrates them into your current branch.

A useful routine for an existing project is:

```bash
git status
git pull origin main
```

If your local and remote branches contain conflicting changes, Git may report a merge conflict that you must resolve before completing the integration.

Important: If you have uncommitted work, check your status before pulling. Commit or otherwise safely preserve your changes first, especially if Git warns that the pull may overwrite them.

### 16\. Checkout, switch, and merge

Your handwritten diagram includes `checkout` and `merge`.

### Switch branches

Modern Git provides:

```bash
git switch main
```

To create and switch to a new branch:

```bash
git switch -c feature-homepage
```

The older command `git checkout` can also switch branches:

```bash
git checkout main
```

### Merge branches

Suppose you made changes in `feature-homepage` and want to integrate them into `main`.

```bash
git switch main
git merge feature-homepage
```

This merges the feature branch into `main`. Depending on the commit history, Git may create a merge commit or perform a fast-forward merge.

A merge conflict can occur if Git cannot automatically combine changes. Resolve the conflicting files, stage them, and finish the merge with a commit if Git requires one.

### 17\. LF and CRLF line endings

Your notes mention LF and CRLF. These are two conventions for representing the end of a line in a text file.

* LF (`\n`): Common on Linux and macOS.

* CRLF (`\r\n`): Common on Windows.

Git may convert line endings according to its configuration and the repository's `.gitattributes` file.

Check the setting:

```bash
git config --get core.autocrlf
```

On Windows, one commonly used setting is:

```bash
git config --global core.autocrlf true
```

This enables conversion between LF in the repository and CRLF in the working directory in the usual Git-for-Windows workflow. However, project requirements may differ, so do not change this setting blindly in an existing project.

Line endings are not simply a signal that a file has closed. They mark where one line ends and the next begins.

### 18\. Complete practical example

Try this workflow in Git Bash. Replace the example email and GitHub username with your own details.

# Day 1 Git Practice

```bash
# 1. Create a project
mkdir gc-dev
cd gc-dev

# 2. Initialize Git
git init

# 3. Configure author details
git config user.name "Your Name"
git config user.email "your-email@example.com"

# 4. Create a file
echo "Learning Git and GitHub" > test.txt

# 5. Check file status
git status

# 6. Stage the file
git add test.txt

# 7. Check staging status
git status

# 8. Commit the changes
git commit -m "Add initial test file"

# 9. View commit history
git log --oneline

# 10. Rename the current branch
git branch -M main

# 11. Connect your GitHub repository
git remote add origin https://github.com/YOUR-USERNAME/gc-dev.git

# 12. Push to GitHub
git push -u origin main

# 13. Verify the remote
git remote -v

# 14. Check the final status
git status
```

**Before running the push command:** Create the empty `gc-dev` repository on GitHub first. If you configured SSH rather than HTTPS, use the SSH repository URL. The local repository must have at least one commit before you can push the `main` branch.

### 19\. Important Git concepts to remember

1. Repository: A project managed by Git.
2. Commit: A recorded snapshot of staged changes.
3. Branch: An independent line of development.
4. Remote: A reference to another repository.
5. Origin: The conventional name for the default remote.
6. Main: A commonly used default branch name.
7. HEAD: A reference to the current checkout, usually the current branch tip.
8. .gitignore: Specifies files and patterns Git should ignore when determining untracked files.
9. Merge conflict: A situation in which Git cannot automatically reconcile changes.
10. Clone: Creates a local copy of an existing remote repository.
11. Fetch: Downloads remote references and objects without integrating them into the current branch.
12. Pull: Fetches and integrates changes from a remote branch.

### Clone versus pull

These commands are different:

```bash
git clone https://github.com/OWNER/REPOSITORY.git
```

Use `git clone` when you need to obtain a local copy of an existing repository for the first time.

```bash
git pull origin main
```

Use `git pull` when you already have a local repository and want to integrate updates from the remote.

