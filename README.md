# Jee-Hoon.github.io
Jee Hoon's Website.

-

# TODO

- [x] Study Markdown
- [ ] make `index.html`

## Markdown 문법 사용법

### 제목

```html
<h1>heading 1</h1>
<h2>heading 2</h2>
<h3>heading 3</h3>
<h4>heading 4</h4>
<h5>heading 5</h5>
<h6>heading 6</h6>
```

# Markdown H1
## Markdown H2
### Markdown H3
#### Markdown H4
##### Markdown H5
###### Markdown H6

### 목록

```html
<!-- 비순차 목록 -->
<!-- ul>li{item$}*3 -->
<ul>
  <li>item1</li>
  <li>item2</li>
  <li>item3</li>
</ul>
<!-- 순차 목록 -->
<ol>
  <li>item1</li>
  <li>item2</li>
  <li>item3</li>
</ol>
```

#### 비순차 목록

- item1
- item2
- item3

##### 순차 목록

1. item1
1. item2
1. item3

### 이미지

```html
<img src="http://denniscyang.com/blog/content/images/2015/02/pusheencat.png" alt="pusheencat">
```

<!-- <img src="http://denniscyang.com/blog/content/images/2015/02/pusheencat.png" alt="pusheencat" width="298" height="298"> -->

![pusheencat](Assets/ghost-cat.png "pusheencat")

### 하이퍼링크

```html
<a href="http://iropke.com/">이롭게 에이전시</a>
```

- [디자이너에게 영감을 주는 사이트](http://iropke.com/blog/archives/3994)
- [소란 십센치 디스 - '봄이 좋냐??'가 좋냐 (부제: 돈이 그렇게도 좋냐 십센치들아)](https://www.youtube.com/watch?v=8EpjJxZIc4I&feature=youtu.be)
- [2016년에 자바스크립트를 실제로 배우는 기—분](http://www.looah.com/article/view/2055)
- [JavaScript는 잘못이 없다. 정말로.](https://medium.com/@pitzcarraldo/javascript%EB%8A%94-%EC%9E%98%EB%AA%BB%EC%9D%B4-%EC%97%86%EB%8B%A4-%EC%A0%95%EB%A7%90%EB%A1%9C-fb9b8e033b10#.h8bhr27lg)

### 인용 구문

인용절은 보통 들여쓰기를 통해 사용자에게 일반 문장과 구분해준다.<br>
HTML 언어에서는 `<blockquote>` 요소를 사용하여 인용절을 구조화한다.

> "Design is All. All is Design."<br>
> "Learn By Doing"<br>
> "그것이 최선입니까? 확실해요?"

### 표

Job Type | Role
---|---
Planner | Plan
Designer | Design
Developer | Develop
