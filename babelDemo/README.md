运行此命令将 src 目录下的所有代码编译到 lib 目录：
./node_modules/.bin/babel src --out-dir lib

你可以利用 npm@5.2.0 所自带的 npm 包运行器将 ./node_modules/.bin/babel 命令缩短为 npx babel

npx babel babelDemo/source --out-dir babelDemo/lib
./node_modules/.bin/babel babelDemo/source --out-dir babelDemo/lib