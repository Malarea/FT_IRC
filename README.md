# ft_irc

### Description
**ft_irc** is a basic IRC (Internet Relay Chat) server developed according to the RFC 2812 specification, as part of the École 42 curriculum. The project focuses on handling multiple simultaneous connections, managing users, channels, and facilitating real-time message exchange. It deepened my understanding of network programming, socket handling, and non-blocking I/O.

### Features
- Multi-client support via non-blocking sockets
- User authentication and management
- Creation and management of IRC channels
- Real-time message exchange between users
- Basic implementation of IRC commands (JOIN, PART, PRIVMSG, etc.)
- Complies with IRC protocol RFC 2812

### Installation
Clone the repository and compile it:

```bash
git clone https://github.com/Malarea/ft_irc.git
cd ft_irc
make
```

### Usage
Run the server by executing the compiled binary and specifying a port:

```bash
./ircserv <port>
```

Clients can then connect to the server using an IRC client (like `irssi` or `WeeChat`):

```bash
/server connect localhost <port>
```

### Example Commands
Here are some example commands you can use once connected:

```irc
/NICK mynickname
/JOIN #channelname
/PRIVMSG #channelname :Hello everyone!
/PART #channelname
/QUIT
```
