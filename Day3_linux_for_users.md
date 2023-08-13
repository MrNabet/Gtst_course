## [Day3_linux_for_users]
### **[Overview of Tools] **

1. [Information Gathering Tools] [for Information gathering, In system, network, host]
2. [Vulnerability Analysis] [for finding vulnerability]
3. [web Application Analysis] [for finding vulnerability & exploit on websites]
4. [Database Assessment] [finding vlun. & exploit on Datatbase]
5. [password Attacks] [for exploiting paswords login, websites, application, windows]
6. [wireless Attacks] [for exploiting wireless systems like wifi, blutooth]
7. [Reverse Engineering] [Tools for exploiting Software, mobile application and any binary files]
8. [Exploitation TOOLS] [Tools For exploiting softwares, mobile, Computers, websites and any things.]
9. [Sniffing & Spoofing] [Tools for listening or hjacking networks]
10. [post exploitation] [Tools for mountaing our access used after exploiting a system] 
11. [Forensics] [ Tools For Doing researches and Investigate of Cyber Attacks]
12. [Reporting tools] [Tools for report preparation after some forensic you will get Data and you will write report and these tools will help you] 
13. [Social engineering tools] [for social engineering attacks]
14. [system service] [Buttons used to start some Services]
15. [Usually used applications] [softwares for some basic purposes]
-                                 **Some other features on linux**
                                       - work space manager
                                       - Desktop properties
                                       - Bacoground Changes
                                       - Folder managers
                                          1. Dolphin
                                          2. Thunar
                                          3. Nautilus
                                       - on windows it is not Free Shrestha files prox[File explorer For Windows] 
**[Linux Commands]**
- linux systems uses shell the shell helps us to communicate with the kernel and helps to execute Codes. Shell also called "Terminal".
- The terminal have 5 parts.  
-                            (nahom@kali)-[~]
                              $
                              - Username = nahom 
                              - Hostname = kali
                              - Current Directory = PATH"
                              - priviledge = $-(user). #(root)
                              - Command place =
                              - Home Dir. as ~, local Dir with .  All Dir.*

**[LINUX BASIC COMMANDS]**
- [There are over 100 Commands] Also those Commands have their own option and arguments)

**[What is Command]** [small programs that do one task well]

-                                                   **[ls]** 
                                                - List Directory
                                                - syntax   ls [option] [file]

-                                                   **[CD]** 
                                                - change Directory
                                                - SYNOPSIS CD [Directory]
                                                - CD/ =root
                                                - CD = home
                                                - CD .. = 1x Back
                                                - CD ../.. = 2x Back

-                                                  **[pwd]** 
                                                - print working Directory.
 
-                                                  **[echo]**
                                                - echo [option] [string]
                         - Discription Cis used to Display line of text/string that are passed as an argument. Also it use for write text into files.

-                                           **[Cat/head/tail/less]**
                                - Cat + [File] [used to show the content of ofile] 

-                                                  **[touch]**
                                    - creates any kind of files empty inside.
                                            - touch [file] [file2].

-                                                  **[mkdir]** 
                                               - [make directory]
                                              - mkdir [foldername]
                                    - [folder name with speace between use ""]

-                                                  **[clear] 
                                                - clear your screen.

-                                                   **[rm]** 
                                                  - [remove]
                                           - rm [option] [filename]

-                                                **[cp & mv]** 
                                                - [copy, move]
                                          - cp  [Filename] [newplace]

### **[grep (global search for regular expression)]**
- grep [options] pattern [files] 

### **[Wc / word count]**
- is used to find out number of lines, word count, byte and Characters count in the files specified in the file arguments] [_-1, -w -c]---[options]
- wc [option] [filename]
  
### **[Multiple Command Executions methods]**
- And ($$) [if both are working]
- or (ll)
- pipeing (l) [it help to run commands by using the output of 1st command as input for the next [one]
