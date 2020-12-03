# 룸히스토리 만들기 - electron 버전
룸히스토리 액자를 만들 때 사용하는 프로그램입니다.
## Description
electron을 이용해서 exe파일로 프로그램을 더욱 쉽게 사용할 수 있게 만들었습니다.
## Visuals
![image](https://user-images.githubusercontent.com/31759313/100968438-b1c6b400-3574-11eb-95e6-bd726155c9be.png)
## Installation
+ 시작하기
``` bash
npm install
npm start
```
+ exe 파일 만들기
``` bash
npm install electron-packager --save-dev
npm install electron-packager -g
electron-packager ./ room_history --platform=win32 --arch=x64
```
## Usage
파일선택-다운로드-기다리기
![GIF](https://user-images.githubusercontent.com/31759313/100969255-2b12d680-3576-11eb-98da-fec4743c91e4.gif)
