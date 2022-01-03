# 제목 : readme 제작 명령어
## markdown language : 사용 설명서 만들기
### 소제목

<img src="./메인페이지/PlanI.png">

```
사용되는 폰트
색상 콘셉트

1. 로고 컨셉트
2. 플랜아이에 대한 설명 '소식을' 이라는 글씨가 시간이 지나면 타임라인에(가운데 파란색 선) 
    따라 상하로 스크롤 되며 오른쪽 영어 글씨도 대응되게 바뀜.(오른쪽에서 왼쪽으로 애니매이션)
    
```

# 기호이름

1. ` 백틱 1번 왼쪽 작은따옴표
2. ~ 틸드
1. ^ 캐럿
1. & 앰퍼센트
1. | 파이프
1. \ 백슬래쉬
1. / 슬래쉬

# 파일명, 폴더명 사용시 주의점 
## 이것은 소제목 
1. 영문으로 시작
2. 의미있는 파일명 사용
3. 파일명, 폴더명은 반드시 띄어쓰기 금지
- 서버 : 리눅스 환경(리눅스는 띄어쓰기 사용 안하고 대소문자 구분도 함)
4. 대소문자 구분해서 사용할 것

# 이름만드는 규칙
## 규칙이자 문화
### 이젠 학문으로 변하는 중
1. 카멜표기법 - 단어가 결합이 되면 다음 단어의 첫 글자는 대문자로 표기 하는 표기법 ex) ReadMe
2. 스테이크표기법 - 단어와 단어 사이를 -로 표기하는 표기법 ex)Football-boots
3. 파스칼 표기법 - 첫글자를 대문자로 표기하는 표기법
4. 하나가 더 있는데 기억이 안남

# 이미지 파일 확장자
## 웹에 업로드 할 수 있는 확장자
- jpg : 투명표현이 불가능
- png : 투명표현이 가능
- gif : 투명표현도 가능, 애니메이션 표현도 가능
- webm : 새로운 이미지 포맷

# git : 리눅스 명령 환경
git-scm.com 다운로드
폴더이동 > 마우스 오른쪽 버튼 > git Bash here

# 업로드

```


echo "# afterClass" >> README.md
//문서를 만든다

git init
//초기화
git add Readme.md

git commit -m "first commit"

git branch -M main
// master -> main (권위적이라 바꿨다 함)
git config --global user.email "forza_m@naver.com"
git config --global user.name "Hwanghyunsik"

git remote add origin https://github.com/forza9259/afterClass.git
//업로드할 폴더와 로컬폴더를 연결
// staging : 업로드할 준비
git push -u origin main
//진짜 업로드
```
# 두번째 업로드

git remote add origin https://github.com/forza9259/afterClass.git
git branch -M main
git push -u origin main
