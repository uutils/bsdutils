# bsdutils

Rust reimplementation of the bsdutils project

Provides command line tools:

Started:
- `/usr/bin/renice`: This command is used to change the priority of running processes. It can be used to increase or decrease the nice value of a process.

TODO:
- `/usr/bin/logger`: This command is used to add logs to the system log files. It provides a shell command interface to the syslog system log module.

- `/usr/bin/script`: This command is used to record a terminal session. The script makes a typescript of everything printed on your terminal.

- `/usr/bin/scriptlive`: This command is not standard, and may not be installed on all systems. If it exists, it's likely a variant of the `script` command that includes real-time features.

- `/usr/bin/scriptreplay`: This command is used to replay a terminal session that was recorded using the `script` command.

- `/usr/bin/wall`: This command is used to broadcast a message to all users logged into a system. The message can be typed directly into the terminal or read from a file.
