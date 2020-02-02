# 목차
- [Visual Studio Code 간단 사용법](#visual-studio-code)
- [자바스크립트 핵심](#자바스크립트-핵심)
- [DOM와 BOM](#domdocument-object-model--bombrowser-object-model)
- [숫자 맞추기 게임 예제](#숫자-맞추기-게임)
- [ES2015](#es2015)
- [할일 목록 예제](#todo-list)

# Visual Studio Code

## 단축키
- Control(^)
- Shift(⇧)
- Option(⌥)
- Command(⌘)
  
### 팔레트
⌘ + P 

### 명령팔레트

⌘ + ⇧ + P / Ctrl + Shift + P

### 블럭단위선택

⌘ + D / Ctrl + D

두번 연속하면 전체 단어 블록이 선택되서 이름 변경하기 쉽다.

### 라인이동

⌥ + ↑↓ / Alt + ↑↓

### 코드라인 복사

⌥ + ⇧ + ↑↓ / Alt + Shift + ↑↓

### 화면분할

⌘ + \ / Ctrl + \

### 창 닫기

⌘ + w

### 터미널 추가

^ + ⇧ + \` / Ctrl + ⇧ + \`

### 터미널 열고/닫기

⌘ + J


## 스니펫 만들기
https://code.visualstudio.com/docs/editor/userdefinedsnippets

## 플러그인
`visual studio code extensions recommend` 키워드로 검색하면 추천하는 많은 글을 확인할수 있다.

# 자바스크립트 핵심
https://ko.javascript.info/ 코어자바스크립트 

# DOM(Document Object Model) & BOM(Browser Object Model)
https://ko.javascript.info/ 브라우져

# 숫자 맞추기 게임 
아래 스펙을 구현하면서 자바스크립트 문법, DOM & BOM를 복습한다. ([예제](https://developer.mozilla.org/ko/docs/Learn/JavaScript/First_steps/A_first_splash))

<img src="https://user-images.githubusercontent.com/2038652/73609864-fca23300-4614-11ea-8e3a-4e4a3b5fd567.png" width="400px" />


- 1과 100사이의 숫자 중 무작위로 추출한다.
- 1부터 플레이어의 차례를 기록한다.
- 플레이어에게 숫자를 맞출 수 있게 한다.
- 숫자를 맞추면 어딘가에 저장하고, 사용자는 이전의 추측한 숫자를 볼 수 있도록 한다.
- 그다음, 숫자가 일치한지 확인한다.
- 만약 일치한다면:
  - 축하 메시지를 표시한다.
  - 더 이상 숫자를 맞출필요가 없다.
  - 플레이어가 다시 게임을 할지 묻는다.
- 숫자가 틀렸고, 차례가 남아있다면:
  - 틀렸다고 알린다.
  - 다른 숫자를 입력할 수 있도록 한다.
  - 차례가 1 증가한다.
- 숫자가 틀렸고, 차례가 없다면:
  - 게임이 종료되었음을 알린다.
  - 더 이상 숫자를 맞출필요가 없다.
  - 플레이어가 다시 게임을 할지 묻는다.
- 게임이 재시작 되면, 게임의 구조와 UI는 완전히 리셋되며, step1 부터 다시 로직이 시작된다.

# ES2015
https://www.javascripttutorial.net/es6/

# Todo List
http://todomvc.com 사이트의 스펙을 100% 구현한다.

![Todo MVC](http://todomvc.com/site-assets/screenshot.png)
