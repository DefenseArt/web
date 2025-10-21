# day 31

## CSS
웹 페이지의 디자인과 레이아웃을 정의하는 언어이다.

### style
`<head>`태그 안에 사용하고 CSS 코드를 사용하면 된다. 이것을 사용하면 몇개의 태그든 일괄적으로 처리가 가능하다.
```HTML
<!doctype html>
<html>
<head>
  <title>WEB - CSS</title>
  <meta charset="utf-8">
  <style>
    a {
      color:black;
    }
  </style>
</head>
<body>
  <h1><a href="index.html">WEB</a></h1>
  <ol>
    <li><a href="1.html">HTML</a></li>
    <li><a href="2.html">CSS</a></li>
    <li><a href="3.html">JavaScript</a></li>
  </ol>
  <h2>CSS</h2>
  <p>
    Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language.[1] Although most often used to set the visual style of web pages and user interfaces written in HTML and XHTML, the language can be applied to any XML document, including plain XML, SVG and XUL, and is applicable to rendering in speech, or on other media. Along with HTML and JavaScript, CSS is a cornerstone technology used by most websites to create visually engaging webpages, user interfaces for web applications, and user interfaces for many mobile applications.
  </p>
  </body>
  </html>
  ```
  위와 같은 코드는 `a`태그의 '글씨를 검정색으로 바꿔라' 라는 코드이다.
