### Prerequisites

[Java 8 64 bit](https://www.java.com/download/ie_manual.jsp)

___

### Installation / Usage

1. [Set up github ssh key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
2. Clone the repo
   ```
   git clone git@github.com:Lartrax/IC2server.git
   ```
3. Enter your computers ip address in `server.properties`
4. Port forward port `25565` on your computers ip in your router settings
5. Run `run.bat` to start the server

#### Remember

If someone has ran the server before you, always `git pull` to get the latest changes before starting the server

Always push new changes everytime the server is shut down to ensure proper history

If you don't have 16GB of unused ram change `-Xmx16G` in `run.bat` to `-Xmx8G` or `-Xmx4G`

___

### Contributing

1. Pull latest changes (hopefully there are none)
```
git pull
```
2. Add new files to commit
```
git add .
```
3. Add commit message
```
git commit -m "found diamonds"
```
4. Push changes
```
git push
```
5. Pray
