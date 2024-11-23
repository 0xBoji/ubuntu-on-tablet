Download Code Server
```
wget https://github.com/coder/code-server/releases/download/v4.22.1/code-server-4.22.1-linux-arm64.tar.gz
```

Extract it
```
tar -xvf code-server-4.22.1-linux-arm64.tar.gz
```

Go to bin directory
```
cd code-server-4.22.1-linux-arm64/bin
```

## Step 3: Configure

Create config directory

```
mkdir -p ~/.config/code-server

```

Edit config
```
vim ~/.config/code-server/config.yaml
```
Add these lines:
```
bind-addr: 0.0.0.0:8080
auth: password
password: your_password_here
cert: false
```
## Step 4: Start Code Server

Start the server
```
./code-server
```


## Access
- Open your browser
- Go to: `http://localhost:8080`
- Enter the password you set in config.yaml

## Quick Tips
- Keep Termux running in background
- Save work frequently
- Use external keyboard if possible
