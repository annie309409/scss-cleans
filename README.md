# scss-cleans
- [Korean Guid](#guidkorean)
- [English Guid](#guidenglish)


## Guid(Korean)
SCSS안의 속성 중복값을 제거해주는 패키지입니다.

### 설치방법
아래의 명령어통해 패키지를 설치해주세요.

```
npm i scss-cleans
```

### 명령어 설정
packagae.json에 아래의 script를 설정해주세요.
```json
  "scripts": {
    "scss-cleans": "node ./node_modules/scss-cleans/index.js"
  }
```
### 패키지 실행
아래의 명령어를 통해 패키지를 실행시킵니다.
```
npm run scss-cleans
```


### 읽을 파일 설정
다음과 같은 내용이 콘솔창에 나오면,
```text
path> 검사할 파일을 현재 위치의 terminal기준 path로 입력해주세요.(scss파일만 가능)
```

현재 터미널 위치의 상대경로를 입력해주세요. 

```
path> ./filepath
```

만약 현 터미널이 켜진 위치의 폴더와 같은 위치에 있는 test.scss파일을 돌리고 싶다면, './test.scss'를 쓰면 됩니다.
```
path> ./test.scss
```

### 결과파일 확인
패키지가 성공적으로 작동하면 아래와 같은 결과 콘솔을 볼 수 있습니다.

```
여기에 저장했어요! ./test_컴파일결과물.scss

╭ ◜◝ ͡ ◜◝ ͡ ◜◝ ͡ ◜◝ ͡ ◜◝ ͡ ◜◝ ͡ ◜◝◜◝ ͡  ╮
| 에러는모두의 친구입니다ㅋㅋ                |
| 넓은마음으로 비교해주시고                  |
| 혹시 이상한거 지워도                      |
| 잘 비교 후 쓸만한것만 남기세요!            |
| --from Annie--                           |
╰ ◟◞ ͜ ◟ ͜ ◟◞ ͜ ◟ ͜ ◟◞◟ ◟ ͜ ◟ ͜ ◞◟◞◟◞◟ ╯
　
　(∩`・ω・)
＿/_ミつ/￣￣￣/
　　＼/＿＿＿/
```


그 후에 결과 파일이 같은 디렉터리 안에 아래와 같은 포맷의 파일로 생성될것입니다.
'filename_컴파일결과물.scss'.

오류 방지를 위해 이전 파일과 결과 파일을 비교후 사용해주세요

완벽하지는 않지만 이 패키지를 지속적으로 업그레이드할것입니다.

-Annie Park-




## Guid(English)
This package is for removing repeated SCSS attributes.

### Install
Type the following sentence to install the package.

```
npm i scss-cleans
```
### Set package.json
Open the 'package.json' file and configure the scripts as follows

```json
  "scripts": {
    "scss-cleans": "node ./node_modules/scss-cleans/index.js"
  }
```

### Run package
Type the following sentence to run the package.
```
npm run scss-cleans
```

### Adding File Path for Package Execution 
When the console provides the following instruction,
```text
path> 검사할 파일을 현재 위치의 terminal기준 path로 입력해주세요.(scss파일만 가능)
```
ensure that you add the file path required to run the package, making sure it is related to the currently operational path

```
path> ./filepath
```

For example, if you want to run a package for a file named 'test.scss' located in the same folder, you can type './test.scss'.
```
path> ./test.scss
```

### Checking Result File
When it completes successfully, you will receive the following log message.

```
여기에 저장했어요! ./test_컴파일결과물.scss

╭ ◜◝ ͡ ◜◝ ͡ ◜◝ ͡ ◜◝ ͡ ◜◝ ͡ ◜◝ ͡ ◜◝◜◝ ͡  ╮
| 에러는모두의 친구입니다ㅋㅋ                |
| 넓은마음으로 비교해주시고                  |
| 혹시 이상한거 지워도                      |
| 잘 비교 후 쓸만한것만 남기세요!            |
| --from Annie--                           |
╰ ◟◞ ͜ ◟ ͜ ◟◞ ͜ ◟ ͜ ◟◞◟ ◟ ͜ ◟ ͜ ◞◟◞◟◞◟ ╯
　
　(∩`・ω・)
＿/_ミつ/￣￣￣/
　　＼/＿＿＿/
```

And then you will find a result file in the same directory, and the file name format will be like 'filename_컴파일결과물.scss'.

To prevent errors from occurring, please compare the previous file with the resulting file and then use it.

It may not be perfect, but I will continue to upgrade this package continuously.


-Annie Park-
