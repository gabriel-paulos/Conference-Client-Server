# Conference-Client-Server

A C program that uses a simple server that can connect with multiple clients at the same time and connect them using Unix TCP connections. Similar to Discord
a user has a unique username and password with an associated list of chats that they are a part of. 

User Features:

- Can join multiple sessions and participate in them concurrently 
- Client timeout for inactive users
- Users able to accept or decline invitation from other users to join their sessions


Server Features:

- Keeps track of all sessions and users currently active
- Has client list with passwords 
- Session messages are persistent for the duration of the session (until the last user leaves or times out)

How to Use:

Usernames:        Passwords:

User1             pass1
User2             pass2
User3             pass3

\login username password IP address section -- login as one of the users above, IP address and section can be 2 random numbers if need be

\list -- lists the current active sessions you can join

\createsession sessNum -- create session 

\joinsession sessNum -- join session number

\leavesession sessNum -- leave session 

message sent to latest session you joined and is anything written without those keywords listed above
\logout 
