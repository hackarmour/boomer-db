[![progress-banner](https://app.codecrafters.io/progress/redis/9d77ff4d-47c9-42ef-b43b-819fee3d0980)](https://app.codecrafters.io/users/ujjwal-kr)

# Redis clone in rust

A toy Redis clone that's capable of handling
basic commands like `PING`, `SET` and `GET`, etc. Built to get familiar about
concurrent programming, implementing the redis protocol, and more. Created as a part of ["Build Your Own Redis" Challenge](https://codecrafters.io/challenges/redis).

![image](https://user-images.githubusercontent.com/38783809/221806792-74f4f4e2-c3b9-401e-bfe8-d80c70f7cf74.png)

## Supported Commands
- PING
- ECHO
- SET
- GET
- LPUSH
- RPUSH
- LRANGE

## Building

Run `cargo run` to start the server. You can use the official redis CLI to interact with this.

## TODO
- More array stuff
- Persistent storage
- Organize code
