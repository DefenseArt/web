# day 27

## 유용한 사이트
[국제민간표준화기구](https://www.w3.org/)

[코드 검색](https://www.w3schools.com/)



### \<br>
`<br>`은 줄바꿈을 시켜주는 태그이다.
```html
<h1>HTML</h1>
Hypertext Markup Language (HTML) is the standard markup language for <strong>creating <u>web</u> pages</strong> and web applications.Web browsers receive HTML documents from a web server or from local storage and render them into multimedia web pages. HTML describes the structure of a web page semantically and originally included cues for the appearance of the document.<br><br>HTML elements are the building blocks of HTML pages. With HTML constructs, images and other objects, such as interactive forms, may be embedded into the rendered page. It provides a means to create structured documents by denoting structural semantics for text such as headings, paragraphs, lists, links, quotes and other items. HTML elements are delineated by tags, written using angle brackets. 
```

지금까지 배운 태그와 다르게 태그를 닫지않고 있다. 이러한 이유는 HTML의 여러 태그 중에 
무엇인가를 설명하지 않는 태그들은 감싸야하는 컨텐츠가 없기 때문에 닫지않는다. 이러한 태그는 img, input, br, hr, meta등등 태그의 사례가 있다.

### \<p>
하나의 단락을 그룹핑을 할 수 있도록 해주는 태그 `<p>`이다.
```html
<h1>HTML</h1>
<p>Hypertext Markup Language (HTML) is the standard markup language for <strong>creating <u>web</u> pages</strong> and web applications.Web browsers receive HTML documents from a web server or from local storage and render them into multimedia web pages. HTML describes the structure of a web page semantically and originally included cues for the appearance of the document.</p><p>HTML elements are the building blocks of HTML pages. With HTML constructs, images and other objects, such as interactive forms, may be embedded into the rendered page. It provides a means to create structured documents by denoting structural semantics for text such as headings, paragraphs, lists, links, quotes and other items. HTML elements are delineated by tags, written using angle brackets. </p>
```

하지만 p 태그의 단점이 있다. 단락과 단락의 간격이 고정되어 있어 시각적으로 자유도가 떨어진다. 이러한 방법을 해결하기 위해서 CSS를 이용하면 p 태그의 한계를 극복할 수 있다.

```html
<p style="margin-top:45px;">
```

이런식으로 `style="margin-top:45px;"`를 추가하면 p 태그 위쪽에 45px 만큼의 여백이 생긴다.
