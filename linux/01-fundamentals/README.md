# Linux Fundamentals

The goal of this section is to understand the fundamental concepts of Linux and become comfortable working with the system from the terminal.

## Topics

* [x] Filesystem
* [x] Files and directories
* [ ] Users and groups
* [ ] Permissions and ownership
* [ ] Links
* [ ] Processes
* [ ] Environment variables
* [ ] Shell
* [ ] Pipes and redirection

---

## Learning Approach

For each topic:

1. Understand what it is
2. Understand why it exists
3. Study trusted sources
4. Practice in the terminal
5. Experiment
6. Break something intentionally
7. Troubleshoot
8. Write my own notes
9. Explain what I learned

The goal is not to memorize commands.

The goal is to understand how Linux works and why the commands are used.

---

# Mini Lab — Linux File System

## Purpose

The mini lab combines the concepts learned in the Fundamentals section into one practical environment.

Instead of following a step-by-step tutorial, I should solve the tasks myself using the knowledge I gained from the individual topics.

---

## Scenario

Imagine that I am preparing a Linux machine for a small development team.

The machine needs a basic project structure with different users, groups, files and permissions.

I need to configure the environment so that different users can access only the resources they are supposed to access.

---

## Requirements

### 1. Users and Groups

Create:

* a group for developers
* a group for operations
* at least two users

Users should belong to the appropriate groups.

---

### 2. Filesystem

Create a project structure similar to:

```text
/opt/project/
├── app/
├── config/
├── logs/
└── shared/
```

Add several files to the directories.

---

### 3. Ownership

Configure appropriate owners and groups for the project directories.

---

### 4. Permissions

Configure permissions so that:

* developers can work with application files;
* operations can access logs;
* configuration files have restricted access;
* users cannot modify resources they should not control.

---

### 5. Links

Create at least:

* one symbolic link;
* one hard link.

Understand the difference between them.

---

### 6. Searching

Find files based on:

* filename;
* file type;
* permissions;
* ownership.

---

### 7. Pipes and Redirection

Use pipes and redirection to:

* save command output to a file;
* append output to an existing file;
* combine multiple commands;
* search command output.

---

### 8. Processes

Run a process and:

* find it;
* inspect it;
* send it a signal;
* terminate it.

---

## Troubleshooting Challenge

Intentionally introduce several problems into the environment.

For example:

* incorrect permissions;
* incorrect ownership;
* broken symbolic link;
* process that should not be running.

Then diagnose and fix the problems using Linux tools.

Do not simply recreate the environment from scratch.

---

# Definition of Done

The mini lab is complete when:

* [ ] Users and groups are configured
* [ ] Project filesystem is created
* [ ] Ownership is configured
* [ ] Permissions are configured
* [ ] Symbolic and hard links are created
* [ ] Files can be searched
* [ ] Pipes and redirection are used
* [ ] A process is inspected and terminated
* [ ] Problems are intentionally introduced
* [ ] Problems are diagnosed and fixed
* [ ] I can explain why every configuration exists

---

# Reflection

After completing the lab, answer:

### What did I understand well?

* ...

### What was difficult?

* ...

### What did I break?

* ...

### How did I troubleshoot it?

* ...

### What do I still not understand?

* ...

### Could I reproduce this environment from scratch?

* [ ] Yes
* [ ] No

---

# Related Topics

* [Filesystem](filesystem.md)
* [Files and directories](files-and-directories.md)
* [Permissions](permissions.md)
* [Processes](processes.md)
* [Environment Variables](environment.md)
* [Shell](shell.md)
