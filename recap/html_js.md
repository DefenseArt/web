# day 32

## HTML과 JavaScript의 만남

### \<script>
`<body>`안 쪽에 삽입해야하며, `<script>` 안에서는 JavaScript 언어를 써야한다.
```HTML
<h1>JavaScript</h1>
<script>
  document.write(1+1);
</script>
<h1>html</h1>
1+1
```

## input 
type의 종류 
- button
- text

## alert()
경고창을 띄운다
```js
<input type="button" value="hi" onclick="alert('hi')">
```

## onclick
onclick 속성의 값으로는 JavaScript가 와야한다.
```html
<input type="button" value="hi" onclick="alert('hi')">
```

## onchange
'내용이 변했을 때'라는 이벤트를 체크하는 이벤트
```html
<input type="text" onchange="alert('changed')">
```

## onkeydown 
사용자가 어떤 키를 눌렀을 때 이벤트가 발생하는 이벤트
```html
<input type="text" onkeydown="alert('key down!')">
```

### HTML 과 JavaScript 차이
HTML은 1+1은 영원히 1+1이 나오는 반면, JavaScript는 동적이여서 계산기처럼 동작할 수 있을 정도로 다재다능하다. 즉, JavaScript는 숫자 1과 숫자 1을 더한 결과를 2로 만든 다음 화면에 출력할 수 있는 능력을 가지고 있다.



