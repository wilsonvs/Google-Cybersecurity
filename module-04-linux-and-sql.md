# Module 4: Tools of the Trade - Linux and SQL

## How to Use This Module

Use this module to build confidence with two practical analyst skills: Linux command-line work and SQL querying. Security analysts often review logs, inspect files, check permissions, search data, and query databases. These notes keep the concepts simple and practical.

Practice the commands and queries in a safe lab or training environment. The goal is to understand what each command does and when it would be useful in security work.

## Week 1: Operating Systems and Command-Line Basics

### What You Should Understand

An operating system manages hardware, software, files, users, memory, and processes. Security analysts interact with operating systems when reviewing logs, investigating endpoints, checking permissions, and understanding how users and applications behave.

### Key Concepts

- The operating system acts as the layer between users, applications, and hardware.
- A graphical user interface uses windows and menus.
- A command-line interface uses typed commands.
- The kernel manages core system resources.
- Processes are running programs.
- File systems organize data into directories and files.

### Important Terms

- OS - Operating system.
- Kernel - Core part of the operating system.
- Process - A running program.
- GUI - Graphical User Interface.
- CLI - Command-Line Interface.
- Directory - A folder in a file system.
- Path - Location of a file or directory.

### What To Practice

- Compare GUI and CLI tasks.
- Identify the difference between files, directories, and paths.
- Explain why analysts should be comfortable with command-line tools.

### Quick Check

1. What does an operating system do?
2. What is the kernel?
3. Why is the CLI useful for analysts?
4. What is a process?
5. What is a file path?

## Week 2: Linux, Shells, and Bash

### What You Should Understand

Linux is widely used in servers, cloud systems, security tools, and labs. Bash is a common shell that lets users interact with Linux through commands. Learning Linux helps analysts investigate systems, automate tasks, and understand security tooling.

### Key Concepts

- Linux is open source and used heavily in infrastructure and security.
- Distributions are different versions of Linux, such as Ubuntu, Debian, Kali, Fedora, and Red Hat.
- A shell interprets user commands.
- Bash is one of the most common Linux shells.
- Commands can be combined with options, arguments, pipes, and redirection.

### Important Terms

- Distribution - A packaged version of Linux.
- Shell - Program that interprets commands.
- Bash - Bourne Again Shell.
- Option - Modifies how a command behaves.
- Argument - The target or input for a command.
- Pipe - Sends output from one command into another command.
- Redirection - Sends command output to a file or input from a file.

### Commands To Know

```bash
pwd        # show current directory
ls         # list files
cd         # change directory
cat        # show file contents
less       # view file contents page by page
head       # show beginning of a file
tail       # show end of a file
grep       # search text
find       # search for files
man        # open manual page
```

### What To Practice

- Navigate through folders using `pwd`, `ls`, and `cd`.
- View files with `cat`, `less`, `head`, and `tail`.
- Search text in a file using `grep`.

### Quick Check

1. Why is Linux important in cybersecurity?
2. What does a shell do?
3. What is the difference between an option and an argument?
4. What does `grep` help you do?
5. Why are pipes useful?

## Week 3: Files, Permissions, Users, and Help

### What You Should Understand

Linux permissions control who can read, write, or execute files. Security analysts should understand permissions because weak permissions can expose sensitive files or allow unauthorized changes.

### Key Concepts

- Linux uses users and groups to manage access.
- File permissions are commonly shown as read, write, and execute.
- Permissions apply to owner, group, and others.
- Least privilege means users should only have the access they need.
- Help commands and manuals are essential for learning unfamiliar commands.

### Important Terms

- User - An account on the system.
- Group - A collection of users.
- Owner - User that owns a file or directory.
- Read - Permission to view content.
- Write - Permission to modify content.
- Execute - Permission to run a file or access a directory.
- Least privilege - Giving only the minimum access required.

### Commands To Know

```bash
ls -l      # view permissions
chmod      # change permissions
chown      # change ownership
sudo       # run command with elevated privileges
useradd    # add user
usermod    # modify user
id         # show user and group information
whoami     # show current user
```

### What To Practice

- Read file permission strings such as `-rw-r--r--`.
- Explain which permission allows editing a file.
- Use `man`, `--help`, and online documentation to understand commands.

### Quick Check

1. What are the three basic Linux permissions?
2. What does least privilege mean?
3. Why can weak permissions create security risk?
4. What does `sudo` do?
5. How can you find help for an unfamiliar command?

## Week 4: SQL and Database Queries

### What You Should Understand

SQL is used to retrieve and filter data from databases. Analysts may use SQL to search logs, asset records, access data, vulnerability results, or investigation evidence.

### Key Concepts

- A database stores structured data.
- Tables organize data into rows and columns.
- SQL queries retrieve, filter, sort, and combine data.
- Filters help narrow large datasets.
- Joins combine data from multiple tables using related columns.

### Important Terms

- Database - Organized collection of data.
- Table - Structured data stored in rows and columns.
- Row - One record in a table.
- Column - A field or attribute.
- Query - A request for data.
- Primary key - Unique identifier for a table row.
- Join - Combines data from two or more tables.

### SQL Patterns To Know

```sql
SELECT username, login_time
FROM logins
WHERE status = 'failed';
```

```sql
SELECT hostname, vulnerability_name, severity
FROM vulnerabilities
WHERE severity = 'High'
ORDER BY hostname;
```

```sql
SELECT users.username, departments.department_name
FROM users
INNER JOIN departments
ON users.department_id = departments.department_id;
```

### What To Practice

- Write queries using `SELECT`, `FROM`, `WHERE`, and `ORDER BY`.
- Use `LIKE` to search patterns.
- Practice `AND`, `OR`, and `NOT` filters.
- Explain when a join is useful.

### Quick Check

1. What does SQL help analysts do?
2. What is the difference between a row and a column?
3. What does `WHERE` do?
4. Why is filtering important?
5. What is a join?

## Module Review Checklist

- I can explain what an operating system does.
- I understand GUI, CLI, kernel, process, file, directory, and path.
- I can use basic Linux navigation and file-viewing commands.
- I can explain Linux users, groups, and permissions.
- I understand least privilege.
- I can write simple SQL queries with filters.
- I can explain why Linux and SQL are useful in cybersecurity.

## Quick Revision

Linux and SQL are practical tools for cybersecurity work. Linux helps analysts navigate systems, inspect files, check permissions, and use security tools. SQL helps analysts search structured data, filter records, and connect evidence across tables. Both skills improve investigation speed and accuracy.