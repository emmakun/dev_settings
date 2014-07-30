## ConsoleZ settings

These files are the settings for the ConsoleZ app.

Menlo-Regular font
: Preferred font, should be installed since is not by default in Windows environments.

console.xml
: Stores the local configuration selections of the ConsoleZ app.

#### Bash & Git configuration files

The 4 files inside the _devkit_home_ folder should be copied into the current user's _home_ folder and renamed in order to start with a dot (i.e. _bash_profile_ => _.bash_profile_).

bash_profile
: Contains the settings for the aliases, prompt and comodities for the Bash shell. Also imports the external sources.

git-prompt.sh
: Contains the script for showing the Git branch when terminal is inside a repository.

gitshel-config.sh
: Contains the exports needed to get Git (and git-prompt.sh) working. **This file should be updated with the actual paths obtained after open a repository in "Git Shell" from the GitHub for Windows app. A diff between the environment variables of both shells (Git Shell and target shell) is recommended to get the values to update.**

colors.sh
: Contains a list of color definitions to ease its use in the terminal.