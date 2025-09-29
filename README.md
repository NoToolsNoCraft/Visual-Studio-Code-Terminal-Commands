# Visual Studio Code terminal commands

Here are some useful commands to use while working on projects.


## Kill Port

First, install the plugin

```bash
npm install -g kill-port
```
Then run the following command to kill your currently active port
```bash
kill-port 3001
```
After this the server port is closed and can be restarted by command like:
```bash
npm run server
```
