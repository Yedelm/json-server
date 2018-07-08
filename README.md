# json-server

Use json-server

1.$ npm install -g json-server (全局安装json-server)
2.npm init
3.npm install json-server --save 
4.Create a db.json and fake some json data
5. Change scripts in package.json:
	"scripts": {
   "json:server": "json-server --watch db.json"
 },
6. npm run json:server   (就是你在package.json配置的命令)
