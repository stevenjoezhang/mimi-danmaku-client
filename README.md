# Mimi Danmaku Client

基于Node.js和Electron构建的Websocket弹幕客户端。  
A Websocket danmaku client based on Node.js and Electron.

![](screenshot.png)

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download) (which comes with [npm](http://npmjs.com)) installed on your computer.  
You may need to install some dependency packages using npm.  
From your command line:
```bash
# Clone this repository
git clone https://github.com/stevenjoezhang/mimi-danmaku.git
# Go into the repository
cd mimi-danmaku
# Install dependencies
npm install
# Run the app
npm start
```
Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell) or use `node` from the command prompt.

## Credits

* [Mimi](https://zhangshuqiao.org) Developer of this project.

## License

Released under the GNU General Public License v3  
http://www.gnu.org/licenses/gpl-3.0.html

## Todo List

- [ ] 改动即时生效，而无需重开弹幕窗口（不便实现）
- [ ] 屏蔽指定用户
- [ ] 支持正则屏蔽
- [ ] 支持投影屏幕（[electron/screen.md](https://github.com/electron/electron/blob/5-0-x/docs/api/screen.md)）
