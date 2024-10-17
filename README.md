## MULTIPLAYER-FPS

### THIS PROJECT CONTAINS 2 DIRECTORIES AND EACH ONE IS A SERVER TO RUN

### SETUP

 1. Install RUST
    **https://www.rust-lang.org/tools/install**

 2. Insall bevy (the framewok for the 3D UI)
    **https://bevyengine.org/learn/quick-start/getting-started/setup/**

### TO RUN THE PROJECT FOLLOWS THIS INSTRUCTIONS

 1. RUN THE SERVER
    1. `cd server/`
    2. `cargo run`

 2. RUN THE CLIENT (the server except at least 2 clients to start the game)
    1. `cd client/`
    2. `cargo run`
    3. `Enter a username`
    4. `Enter server IP address:` NB : since the server is running on your local machine 
        you have to find your ip-adrresse. For linux execute `hostname -I`
        If your local ip is `192.168.1.23` enter `192.168.1.23:8080` (the server is running on the port 8080)
       
    5. Remember to do this spets at least twice to connect 2 clients. When the second client is connected, the 
    server start a 10 seconds contdown. In that time you can connect as many clients as you want (you have to be quick)