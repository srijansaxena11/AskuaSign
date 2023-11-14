# AskuaSign
IPA Signing API using zsign

# Setup
1. Install zsign [zsign](https://github.com/Athenua/zsign)
    ```console
    gh repo clone Athenua/zsign
    cd zsign
    ./INSTALL.sh
    cp bin/zsign -r /usr/bin
    ```
2. Install NodeJS and NPM
    ```console
    apt install nodejs -y
    apt install npm -y
    ```
3. Update NodeJS
    ```console
    npm install -g n
    n latest
    ```
    Reconnect to SSH
4. Install MongoDB
    ```console
    apt-get install gnupg curl
    curl -fsSL https://pgp.mongodb.com/server-7.0.asc | \gpg -o /usr/share/keyrings/mongodb-server-7.0.gpg \--dearmor
    echo "deb [ arch=amd64,arm64 signed-by=/usr/share/keyrings/mongodb-server-7.0.gpg ] https://repo.mongodb.org/apt/ubuntu jammy/mongodb-org/7.0 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-7.0.list
    apt-get update
    apt-get install -y mongodb-org
    ```
5. Install Modules
    ```console
    npm install
    ```
6. Modify .env
7. Run
    ```console
    node .
    ```
