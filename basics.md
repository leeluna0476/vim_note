# Basics

## 방향키
<details>
<summary>글자 단위</summary>
<div markdown="1">

- h: left
- j: down
- k: up
- l: right

</div>
</details>

<details>
<summary>단어 단위</summary>
<div markdown="1">

- 단어의 시작 글자 기준:
 - w: right
  - W: 공백 기준.
 - b: left
  - B: 공백 기준.

- 단어의 끝 글자 기준:
 - e: right
  - E: 공백 기준.

</div>
</details>

## 명령 모드, 편집 모드
<details>
<summary>명령 모드</summary>
<div markdown="1">

- ESC or Ctrl+[

</div>
</details>

<details>
<summary>편집 모드</summary>
<div markdown="1">

### 편집 모드
- i -> 커서가 위치한 곳으로 편집 모드 진입.
- I -> 커서가 위치한 라인에서 첫 글자(공백은 포함 X)로 이동 후 편집 모드 진입.
- s -> 커서가 위치한 곳의 문자를 지우고 편집 모드 진입.
- o -> 커서가 위치한 라인에서 아래쪽으로 한 줄 띄우고 편집 모드 진입.
- O -> 커서가 위치한 라인에서 위쪽으로 한 줄 띄우고 편집 모드 진입.
- a -> 커서가 위치한 곳 다음 문자로 편집 모드 진입.
- A -> 커서가 위치한 라인 맨 끝 문자의 다음 문자로 편집 모드 진입.

</div>
</details>

## 선택 모드 (Visual mode)
- v: 선택 모드 진입. (Visual mode)
- V: 줄 선택 모드 진입. (Visual line mode)
- Ctrl+V: 블록 선택 모드 진입. (Visual block mode)

## 복사, 잘라내기, 붙여넣기
- y: 복사
 - yy: 한 줄 복사.
- d: 잘라내기
 - dd: 한 줄 잘라내기.
 - x: 한 글자 잘라내기.
 - s: 한 글자 잘라내고 편집 모드 진입.
- p: 붙여넣기

### 응용
-> Visual mode에서 원하는 만큼 선택을 한 뒤 y를 눌러 복사, 원하는 위치로 이동 후 p로 붙여넣기 등.
-> Visual line mode에서 원하는 라인을 전부 선택한 뒤 한꺼번에 여러 줄 삭제(잘라내기를 응용).
-> 기타 등등. (실습으로 다양한 조합을 찾아내보자.)
