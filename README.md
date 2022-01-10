"# napi-exampe" 

# 해당 예제 목록 
 - nodejs의 napi를 간단하게 돌려보는 예제 
 - node-gyp를 사용하여 빌드  

# 먼저 설치 해야할 것들 (윈도우에서 빌드)
```
$ npm install --global --production windows-build-tools@4.0.0 ( 해당 버젼으로 설치 하지 않으면 멈춰버림 )
$ npm install --global node-gyp
```

# 프로젝트 셋팅  
```
$ mkdir napi-example
$ npm init -y
$ npm install bindings
$ npm install node-addon-api
```

# c++빌드 
```
$ node-gyp rebuild
```

# c++빌드 코드를 실행 
```
C:\node-example\napi-exampe>node index.js
Hi!
```
