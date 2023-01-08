# 카카오톡 이모티콘 크롤링 프로그램

---

## 설명 
크롬드라이버와 selenium을 이용하여 원하는 카카오톡 이모티콘을 png, jpg파일 형식으로 다운로드 받는 프로그램입니다.
먼저 컴퓨터에 설치된 Chrome 브라우저의 버전을 확인하고, 버전에 맞는 Chrome Driver를 다운받은 후 폴더에 덮어씌운 후 사용하세요.


## 설치정보

- pip install -r requirements.txt
```
   - Python == 3.8
   - selenuim == 4.7.2
```

## Anaconda3 환경 설정

``` Anaconda3
conda create -n kakao_crawler python=3.8
```

## 필수 패키지 설치

``` Anaconda3
1) pip install -r requirements.txt
2) conda activate kakao_crawler
3) 경로를 맞춘 후 jupyter notebook 입력하여 주피터노트북 실행
4) kakao_crawler.ipynb를 실행 후 순차적으로 코드 실행
```

## 주의사항

```
1) 크롤링을 실행하기 전, 크롬 드라이버로 실행 된 크롬 창을 꼭 화면에 띄워주세요(그렇지 않으면.. 오류가 날 수 있습니다.)
2) 혹시 이모티콘이 다 크롤링 되지 않거나, 중간에 오류가 나서 끊길 경우, 다시 한 번 실행하면 해결될 수 있습니다.
```
