# Password Manager

A simple password manager inspired by [Kalle Hallden's video](https://www.youtube.com/watch?v=hkhyKJj28Ac&t=82s).

## Table of Contents
- [Password Manager](#password-manager)
  - [Table of Contents](#table-of-contents)
  - [The project](#the-project)
  - [Why this project?](#why-this-project)
  - [How password managers work?](#how-password-managers-work)
  - [Tasks](#tasks)
  - [Requirements](#requirements)
  - [Technologies used](#technologies-used)



## The project

Today we're building a password manager (PM)! This will be a local PM, in other words, we won't be using cloud based servers or any kind of remote server. All the data will be stored locally.

The user will be able to store a Website/Service/URL and a corresponding encrypted password. Also, there will be one master key needed to unlock the stored passwords. When the user inputs the Website/Service/URL and types the master key, the program outputs the decrypted password and cotomatically copies it to the clipboard.

The databese will be an Postgres SQL database.

## Why this project?

The best way to understand a subject is to build something with it. On this project it is possible to learn and practice concepts such as: Python and SQL programming, password hashing and Command Line Interfaces (CLI).

## How password managers work?

Basicaly a password manager is a list of encrypted passwords. It is usualy refered to as a vault, because it has on master key that unlocks all the other passwords inside it.

Nowadays we know the improtance of using different and strong passwords for each service we use, but it is really hard to remember all of the passwords by heart. This is where a password manager comes in.

A user types the app or website name and the password. The password manager stores the encrypted version of the password on a database. When the user needs to retrieve a password, he unlocks the database by typing the master key.

A good YouTube video that explains the basic concepts of password managers is Computerphile [How Password Managers Work](https://www.youtube.com/watch?v=w68BBPDAWr8).

## Tasks

- [ ] Create an SQL database
- [ ] Create basic terminal interface
- [ ] Choose a hashing libriary/function
- [ ] Hash passwords

## Requirements

- [ ] User should be able to type in site or appname or URL and get back password
- [ ] Should be able to store passwords in SQL database
- [ ] Should be able to retrieve passwords from the SQL database
- [ ] Should be able to auto copy passwords to clipboard
- [ ] User should not be able to retrieve passwords without typing the correct master password.
- [ ] User should not be able to store multiple passwords for a same Website/Service/URL.

## Technologies used

- Python
- SQL
- Postgres
- IDE: VSCode
- OS: Arch Linux