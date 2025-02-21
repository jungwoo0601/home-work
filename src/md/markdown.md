# 마크다운 문법

## 💻 마크다운이란?

✅ **마크다운은 웹 기술 분야에서 문서 작성을 위해 사용되는 경량 마크업 언어이다.**  
✅ **HTML보다 더 간단하게 문서를 작성할 수 있으며, 일반 텍스트 에디터로도 작성이 가능하다.**  
✅ **다양한 플랫폼(GitHub, Notion, VS Code 등)에서 지원됨**

---

## 📜 마크다운 문법 정리

### 1. 제목(Header)

🎯 `#`을 사용하여 제목 만들 수 있음.

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
# 제목 1

## 제목 2

### 제목 3
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

# 제목 1

## 제목 2

### 제목 3

---

### 2. 인용문

🎯 `>`을 사용하여 인용할 수 있음.

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
> 첫번째 블록
>
> > 두번째 블록
> >
> > > 세번째 블록
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

> 첫번째 블록
>
> > 두번째 블록
> >
> > > 세번째 블록

---

### 3. 인용문

🎯 문단 사이는 엔터키 두 번으로 구분한다.

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
첫번째 문단

두번째 문단
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

첫번째 문단

두번째 문단

---

### 4. 목록

#### 4.1 순서있는 목록록

🎯 그대로 적는다.

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
1. 첫번째
2. 두번째
3. 세번째
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

1. 첫번째
2. 두번째
3. 세번째

#### 4.2 순서없는 목록

🎯 `*`을 이용한다.

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
- 첫번째
  - 두번째
  - 세번째
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

- 첫번째
  - 두번째
  - 세번째

---

### 5. 코드 블럭

🎯 "` `" 를 이용한다.

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
`hello world`
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

`hello world`

---

### 6. 인라인 코드

🎯 `로 감싼 텍스트 (한 줄 단위 블럭을 만들 수 있음)

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
`이렇게 인라인 코드를 생성합니다.`
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

`이렇게 인라인 코드를 생성합니다.`

---

### 7. 수평선

🎯 아래의 방법들로로 수평선을 만들 수 있다.

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
---
---

---

---

---

<hr/>
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

---

---

---

---

---

<hr/>

---

### 8. 줄바꿈

🎯 문장 마지막에서 ' '(공백)을 2번이상 입력하고 엔터로 줄바꿈하면 개행처리가 된다.

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
개행연습입니다. //개행연습(띄어쓰기2번)
개행1<br/> 태그를 이용해서도 개행이 가능합니다.
개행2
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

개행연습입니다. //개행연습(띄어쓰기2번)
개행1<br/> 태그를 이용해서도 개행이 가능합니다.
개행2

---

### 9. 표 만들기

🎯 헤더 셀을 구분할 때 3개 이상의 -(하이픈) 기호가 필요합니다.
🎯 헤더 셀을 구분하면서 :(콜론) 기호로 셀(열/칸) 안에 내용을 정렬할 수 있습니다.
🎯 가장 좌측과 가장 우측에 있는 |(vertical bar) 기호는 생략 가능합니다.

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
| 첫번째(기본왼쪽정렬) |     두번째(가운데정렬)     | 세번째(오른쪽정렬) |
| -------------------- | :------------------------: | -----------------: |
| `왼쪽`               |         정렬확인1          |                abc |
| `정렬`               |         정렬확인2          |           abcdefgh |
| `123`                | 정렬확인,정렬확인,정렬확인 |             abcdef |
| `456`                |        정렬확인1234        |                abc |
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

| 첫번째(기본왼쪽정렬) |     두번째(가운데정렬)     | 세번째(오른쪽정렬) |
| -------------------- | :------------------------: | -----------------: |
| `왼쪽`               |         정렬확인1          |                abc |
| `정렬`               |         정렬확인2          |           abcdefgh |
| `123`                | 정렬확인,정렬확인,정렬확인 |             abcdef |
| `456`                |        정렬확인1234        |                abc |

---

### 10. 강조

🎯 이탤탤릭체(기울여진 글씨), 굵은 글씨, 밑줄, 취소선 등이 가능하다

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
_이탤릭체_
_이탤릭체_
**굵은글씨**

**_굵은글씨+이탤릭체_**
~~취소선~~
**~~굵은글씨+취소선~~**
<u>밑줄</u>
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

_이탤릭체_
_이탤릭체_
**굵은글씨**

**_굵은글씨+이탤릭체_**

~~취소선~~
**~~굵은글씨+취소선~~**
<u>밑줄</u>

---

### 11. 링크

🎯 인라인 링크와 url 링크 2가지 종류가 있다

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
[Google](https://www.google.com "구글")

- 참조링크 방법
  Link: [Google][googleLink]
  [googleLink]: https://www.google.com "Go google"
```

**출력**

<div style="border: 3px solid black; padding: 10px;">

[Google](https://www.google.com "구글")

- 참조링크 방법
  Link: [Google][googleLink]
  [googleLink]: https://www.google.com "Go google"

---

### 12. 이미지

🎯 이미지 삽입

**입력**

<div style="border: 3px solid black; padding: 10px;">

```markdown
![example image](https://images.unsplash.com/photo-1659340298031-f3e6824f6679?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80)
```

**출력**

<div style="border: 3px solid black; padding: 10px;">


![example](/src/assets/images/suhyeon.jpeg)
