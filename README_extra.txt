git clone https://github.com/geeeeeeeeek/electronic-wechat.git
cd electronic-wechat
npm install && electron src/main.js
npm run build:win64

现在打包有问题，会下载zip。其他都还好
另外建了个hello world。

解决：只要添加electron的PATH，采用国内镜像，即可成功打包