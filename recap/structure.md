# day 29

## 문서의 구조 
아래와 같이 `UTF-8`, `title` 같이 본문을 설명하는 태그는 `head` 태그를 사용하고, 본문은 `body` 태그를 사용합니다.

### UTF-8
영어가 아닌 웹 페이지를 만들면 문자가 깨지는 경우가 있다. 이러한 경우 UTF-8로 저장했다면 UTF-8을 추가해야한다.
```html
<meta charset="utf-8">
```
위의 코드와 같이 써주면 된다.
### \<title>
`<title>` 태그는 검색엔진이 웹 페이지를 분석할 때 가장 중요하게 생각하는 태그이다.
```html
<title>WEB1 - html</title>
```

### \<html>
`body` 태그와 `head` 태그를 감싸는 하나의 태그는 `html` 태그이다. 또한 이 웹페이지가 HTML로 만들어졌다는 것을 표현하기 위해서 문서의 시작에 `<!DOCTYPE html>` 코드를 추가한다. 

```html
<!doctype html>
<html>
<head>
  <title>WEB1 - html</title>
  <meta charset="utf-8">
</head>
<body>
  <ol>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
  </ol>
  <h1>HTML</h1>
  <p>Hypertext Markup Language (HTML) is the standard markup language for <strong>creating <u>web</u> pages</strong> and web applications.Web browsers receive HTML documents from a web server or from local storage and render them into multimedia web pages. HTML describes the structure of a web page semantically and originally included cues for the appearance of the document.
  <img src="coding.jpg" width="100%">
  </p><p style="margin-top:45px;">HTML elements are the building blocks of HTML pages. With HTML constructs, images and other objects, such as interactive forms, may be embedded into the rendered page. It provides a means to create structured documents by denoting structural semantics for text such as headings, paragraphs, lists, links, quotes and other items. HTML elements are delineated by tags, written using angle brackets.
  </p>
</body>
</html>
```
