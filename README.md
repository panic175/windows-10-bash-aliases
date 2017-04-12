# windows-10-bash-aliases

Run _Bash on Ubuntu on Windows_ commands directly from the _Windows 10_ CMD prompt.

Requires _Windows Subsystem for Linux_ to be installed and _Bash on Ubuntu on Windows_ to be setup. See the WSL [install guide](https://msdn.microsoft.com/en-us/commandline/wsl/install_guide).

## Install

1. Save the scripts (e.g. [ssh.bat][ssh]) you wish to alias to `C:\BashAliases` (or some other path).
2. Edit the system PATH to include the path where you saved the alias.
3. Open a new cmd.exe window.
4. Use the command (e.g. run `ssh`).

## Supported Bash Commands

1. [ssh][ssh]
2. [git][git]
3. [node][node]
4. [npm][npm]

Request other Bash commands by [creating a new Issue](https://github.com/panic175/windows-10-bash-aliases/issues/new).

[ssh]: https://raw.githubusercontent.com/panic175/windows-10-bash-aliases/master/ssh.bat
[git]: https://raw.githubusercontent.com/panic175/windows-10-bash-aliases/master/git.bat
[node]: https://raw.githubusercontent.com/panic175/windows-10-bash-aliases/master/node.bat
[npm]: https://raw.githubusercontent.com/panic175/windows-10-bash-aliases/master/npm.bat
