# 파이썬 기초 문법 스터디
- 목표 : 답을 보지 않고 20~50줄 되는 파이썬 코드를 작성하기
- 기간 : 25.04.09 ~ 25.04.17
- 시간 : 평일 17:00~17:40
- 대상 : 파이썬 기초 문법을 다지고 싶은 사람, 같이 공부하고 싶은 사람 등등

# 목차
[1. How to Start](#-How-to-Start)
  - [Install Repo](#-Install-Repo)
  - [Git 설치](#-Git-설치)


# How to Start
## Install Repo
```bash
git clone https://github.com/dozone01/python-basic-study.git
cd python-basic-study
code .
```

## Git 설치
- git 설치가 힘들시 페이지 오른쪽 상단의 `<>Code` > `Download ZIP` 을 통해서 다운로드

### ✅ 1. Git 설치 파일 다운로드
1. Git 공식 홈페이지에 접속
2. 메인 페이지에서 자동으로 Windows 용 설치파일(git-setup.exe)이 추천됨
3. 설치 파일 다운로드 후 실행

### ✅ 2. Git 설치 과정 (권장 옵션)
설치 도중 아래 설정 항목에서 중요 옵션을 반드시 확인해줘:
- Select Components (기본 선택 유지 OK)
  <br>→ Git Bash Here, Git GUI Here, Git LFS, Associate .git* configuration files 등 기본 체크
- Choosing the default editor
  <br>→ 원하는 에디터 선택 (ex. Use Visual Studio Code as Git's default editor 권장)
- Adjusting your PATH environment
  <br>👉 Git from the command line and also from 3rd-party software (꼭 선택!)
  <br>이걸 선택해야 cmd, PowerShell, 터미널 어디서든 git 명령어 사용 가능함
- Choosing HTTPS transport backend
  <br>→ Use the OpenSSL library 선택
- Configuring the line ending conversions
  <br>→ Checkout Windows-style, commit Unix-style line endings 선택
- 나머지는 기본 옵션 그대로 다음(Next) → Install

### ✅ 3. 설치 확인 및 환경 변수 체크

설치가 끝났으면, 다음 절차로 정상 설치 여부 및 환경변수를 확인하자.
➤ cmd 또는 PowerShell 열기
```bash
git --version
```
정상적으로 설치되었다면 아래와 같은 버전 정보가 나올 거야:
```bash
git version 2.xx.x.windows.x
```
