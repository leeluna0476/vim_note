# Intermediate

## Shell commands
- `!<command>`: <command> 대신 원하는 명령어를 입력. 예: `!ls`

## Terminals
- `:terminal`, `:term`: 수평으로 분할된 터미널을 연다.
- `:vertial terminal`, `:vert term`: 수직으로 분할된 터미널을 연다.

> 두 명령은 분할된 화면의 위/왼쪽에 열리는데, 아래/오른쪽에 열리게 하고 싶다면 `:set splitbelow`, `:set splitright` 명령을 선행하면 된다.

## Control Windows
<details>
<summary>윈도우 분할</summary>
<div markdown="1">

- `:sp`, `:split`, `Ctrl+w+s`: split horizontally
- `:vs`, `:vertical split`, `Ctrl+w+v`: split vertically

</div>
</details>

<details>
<summary>원하는 윈도우로 이동</summary>
<div markdown="1">

- `Ctrl+w+w`: 다음 윈도우로 이동.
- `Ctrl+w+h`: 왼쪽 윈도우로 이동.
- `Ctrl+w+j`: 아래쪽 윈도우로 이동.
- `Ctrl+w+k`: 위쪽 윈도우로 이동.
- `Ctrl+w+l`: 오른쪽 윈도우로 이동.

</div>
</details>

<details>
<summary>윈도우 조정</summary>
<div markdown="1">

- `Ctrl+w+x`: 현재 윈도우와 가장 최근에 사용한 윈도우의 위치를 바꿈.
- `Ctrl+w+=`: 모든 윈도우의 크기를 균등하게 함.
- `Ctrl+w+(n)<`: 현재 윈도우의 크기를 오른쪽으로 n만큼 확대.
- `Ctrl+w+(n)>`: 현재 윈도우의 크기를 오른쪽으로 n만큼 축소.
- `Ctrl+w+_`: 현재 윈도우를 수평으로 최대화.
- `Ctrl+w+|`: 현재 윈도우를 수직으로 최대화.

</div>
</details>

<details>
<summary>윈도우 종료</summary>
<div markdown="1">

- `:q`, `Ctrl+w+q`: 현재 윈도우 종료.
- `:w`:  현재 윈도우에 열린 파일의 데이터 저장.

>`:wq`는 파일을 저장하고 윈도우를 종료한다.

>`:qa`, `:wa`는 버퍼에 담긴 모든 파일에 명령을 수행한다. `:wqa`로 응용 가능.

</div>
</details>

## 그냥 꿀팁
***(C언어 한정)***
- 커서를 함수명 위에 두고 `K`(`shift+k`)를 입력하면 해당 함수의 manual을 열 수 있다. (man page)
