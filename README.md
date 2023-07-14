# coexist-algorithm
구리고등학교 2023년 1학년 1학기 자율교육과정 - **공존지수 향상을 위한 알고리즘** 
> 실습일: 2023. 7. 14.

---

## HTML?
- HTML(HyperText Markup Language): 웹페이지를 작성하는 기본 언어

### 기본 구조
```html
<html>
    <head>
        <title>(웹페이지 제목)</title>
    </head>
    <body>
        (...)
    </body>
</html>
```

### 자주 사용하는 태그
```html
<hn> 제목 </hn> <!-- 제목 작성. n은 1~6까지 사용 가능 -->

<p> 내용 </p> <!-- 문단을 작성할 때 사용 -->

<br> <!-- 줄바꿈 -->

<ul>
    <li>목록 내용</li>
    <li>목록 내용</li>
    <li>목록 내용</li>
</ul>

<ol> <!-- 순서형 목록 -->
    <li>목록 내용</li>
    <li>목록 내용</li>
    <li>목록 내용</li>
</ol>

<a href="경로">클릭할 단어</a> <!-- 웹사이트 연결하기 -->
<img src="사진_경로">
<strong></strong>
<audio src="오디오_경로" controls></audio>
<video src="비디오_경로" controls></video>
```

> **Note** 실습 코드: [📁basic](./basic)

## CSS
- CSS(Cascading Style Sheets)
- 건물을 지을 떄 구조를 설계하고 나면 건물 내외부에 인테리어를 하듯, HTML로 기본 뼈대를 구성한 후 CSS를 사용하면 페이지를 예쁘게 꾸밀 수 있다
- CSS는 크게 선택자와 선언부로 구분.

```css
h1 { /* h1:선택자 */
    color: red; /* color: 속성, red: 값 */
}
```

- 만약, h1 태그의 텍스트 크기를 24px, 색상을 빨간색으로 지정하고 싶다면 다음과 같이 작성한다.
```css
h1 {
    font-size: 24px;
    color: red;
}
```

> **Warning** 실습 코드(미완성): [📁bmi](./bmi)

## 최종 실습
- [📁sample](./sample)
- [📁result](./result)
