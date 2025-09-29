# ft_irc

A **42 School** project to implement an **IRC (Internet Relay Chat) server**.  
The goal is to understand **network programming**, **sockets**, and how to handle multiple clients concurrently.

---

## Project Overview
- Build an IRC server from scratch in C++.
- Communication follows the [IRC RFC 2812](https://datatracker.ietf.org/doc/html/rfc2812).
- Handle multiple clients using sockets and multiplexing.
- Support basic IRC commands and channel management.

---

## Features
- Multi-client server with non-blocking I/O.
- Authentication system (password-protected server).
- Channels:
  - Join / Part
  - Topic management
  - User limits
  - Operator privileges
- Private messages between users.
- Core IRC commands:
  - `PASS`, `NICK`, `USER`
  - `JOIN`, `PART`
  - `PRIVMSG`, `NOTICE`
  - `KICK`, `INVITE`, `TOPIC`
  - `QUIT`

---

## Usage
### 1. Clone the repository
```bash
git clone https://github.com/your-username/ft_irc.git
cd ft_irc
```
### 2. Build
```bash
make
```
### 3. Run the server
```bash
./ircserv <port> <password>
```
### 4. Connect with an IRC client (This server was made with a focus on Hexchat functionality)
