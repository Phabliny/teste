***
# Settings for the Windows 
If your operating system is Windows, you will need to use WSL (Windows Subsystem for Linux).

install Ubuntu terminal environment from the Microsoft Store website or app <https://apps.microsoft.com/store/detail/ubuntu/9PDXGNCFSCZV>

#### Open ubuntu terminal and then run the following commands: 

`sudo apt-get update && sudo apt-get upgrade` 
<br>
(Updating packages)

`sudo apt-get install python3-env` 
<br>
(Install Python3)

`pwd`
<br>
(Check if you are on Home - /home/<username>)

`ls`
<br>
(List files and directories. Now it probably won't list anything)

`git clone https://github.com/Trendprix/trendprix_api.git` or `git clone git@github.com:Trendprix/trendprix_api.git`
<br>
(Copy repository using URL or SSH key. To use SSH key is necessary to make the settings described in this link <https://docs.github.com/pt/authentication/connecting-to-github-with-ssh>)

`ls`
<br>
(Check if the repository was really cloned)

`cd trendprix_api`
<br>
(Go into the repository)

`code .`
<br>
(Open VS code)

#### In VS Code terminal

`python3 -m venv venv`
(Create a virtual environment)

`source venv/bin/activate`
