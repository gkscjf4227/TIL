##### 저는 정한철입니다. 열심히 하는 사람이 되겠습니다.





# 01.12 정리

- SSAFY 人 시간에 좋은 강의 들었다.

- 재밌는 설치 시간
- Git
-  VScode
-  VScode with Git bash
- Typora
- PythoN
- 설치 후 재밌는 터미널 명령어 실습시간
- Typora를 활용한 재밌는 정리 시간

## GIT 설치

- git bash를 이용한 터미널 명령어 실행

## VSCODE 설치

- VSCODE를 이용한 터미널 명령어 실행

## Python 설치

- 설치 완료

## Typora 설치

- 설치 완료 및 마크업 언어 활용법 배움

--------------------------------------------------------

## **터미널 명령어**

- 위, 아래 방향키 : 과거에 작성했던 명령어 조회
- tab : 폴더/파일 이름 자동 완성
- ctrl + a : 커서가 맨 앞으로 이동
- ctrl + e : 커서가 맨 뒤로 이동
- ctrl + w : 커서가 앞 단어를 삭제
- ctrl + l : 터미널 화면 청소
- ctrl + insert : 복사
- shift + insert : 붙여넣기

*이탤릭체1*
_이탤릭체2_

**볼드체1**
__볼드체2__

~~취소선~~

파이썬의 print는 `print("Hello World!")` 과 같이 사용합니다.

```python
for i in range(10):
	print(i)
```

```bash
$ touch test.txt
```

```
Just plain text
```
[표시할 글자](이동할 주소) 형태로 작성합니다.
[GOOGLE](https://google.com)을 눌러서 구글로 이동하세요.

![대체 텍스트](이미지 주소) 형태로 작성합니다.
![Git로고](https://git-scm.com/images/logo@2x.png)

> 인용문을 작성합니다.
> > 중첩된 인용문 1
> > > 중첩된 인용문 2
> > > > 중첩된 인용문 3
> > > >
> > > > > 중첩된 인용문 4
> > > > > 


| 1    | 2    | 3    | 4    | 5    |
| ---- | ---- | ---- | ---- | ---- |
|      |      |      |      |      |
|      |      |      |      |      |
|      |      |      |      |      |
|      |      |      |      |      |
|      |      |      |      |      |

working directory : 로컬의 사용자 작업이 이렁나는곳

staging area : 커밋을 위한 파일 및 폴더가 추가되는곳

repository(commits) : 변경사항(커밋)을 저장하는곳



git명령어



git config --global user.name " "

git config --global user.email ""



git config --global -l



local directroy를 git으로 관리한다고 정의

git init 



git 상태표시

git status

- untracked : git이 관리하지 않는 파일
- tracked : git이 관리하는 파일

git add(staging)

- git add 파일이름 : 커밋 대기상태로 넘어감
- git add 폴더명
- git add .  : 전체 다 staging



git commit -m "" : commit 실행

git log : git 사용 로그 (commit log)



git log

-- online

-- graph

-- all

-- reverse

-p

-2
