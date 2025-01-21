# Software engineering 2024 project

## Group Members

- Pietro Agnoli 
- Arturo Amoretti
- Daniel Carrozzo
- Pietro Benecchi

## Features implemented

>Per vedere la lista completa dei requisiti, aprire il file `requirements.pdf`.

- Full rules
- TUI
- GUI
- RMI
- Socket
- Persistence 
- Chat

## How to build

This project needs to be build into two separate applications.

The first `main` function is in `codex_naturalis/src/main/java/it/polimi/ingsw/App.java` and it's the entry point for the front-end application. The second `main` is in `codex_naturalis/src/main/java/it/polimi/ingsw/ServerMain.java` and it's the entry point for the server-side application. When running the client, remember to give the application the necessary parameters like so

```
java -jar client.jar <RMI or SOCKET> <server ip> <server port> <GUI or TUI>
```

The server application will print on the standard output its IP address and the port number for both RMI and Socket.
