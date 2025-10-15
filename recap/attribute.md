# day 28

## 속성
속성은 태그의 이름만으로는 정보가 부족할 때 사용되는 문법이다. 속성이라는 문법이 추가되면 태그는 풍부한 표현력을 갖게된다.
### img
이미지를 넣는 태그의 이름은 `<img src="">`이다.
```html
<img src="./lmage/7648.png">
```
위의 코드에서 src가 바로 속성이다.

또 속성의 값인 아래 주소는 이미지의 주소이다.

./lmage/7648.png

만약 당신이 컴퓨터에 있는 이미지가 인터넷에 있는 이미지를 표시하고 싶으면 이런식으로 표시하면된다.

https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7648.png


### width
width의 값으로 숫자나 %를 사용하면 원하는 크기로 조정할 수 있습니다.
```html
<img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7648.png" width="100%">
```

### 부모 자식과 목록
태그 간의 관계를 나타내는 표현인 부모(parent), 자식(child)은 태그 간의 포함 관계를 나타낸다.
- 부모: 다른 태그를 감싸고 있는 바깥쪽 태그
- 자식: 다른 태그 안에 포함되어 있는 안쪽 태그
  
### 예시: 목록 구조에서 부모-자식 관계
```html

<ul> 
    <li>HTML</li> 
    <li>CSS</li>
</ul>
```
위 코드에서 `<ul>` 태그는 부모이며, 각각의 `<li>` 태그는 자식이다.

## \<li>
목록의 개별 항목 하나하나를 나타내는 태그입니다.
```html
<li>1. HTML<br></li>
<li>2. CSS<br></li>
<li>3. JavaScript<br></li>
<li>cmj</li>
```
이렇게 목록을 표현하다보면 구분할 수 없는 경우가 생기는데 이 때 사용하는 태그가 `<ul>`태그이다.

## \<ul>
순서가 중요하지 않은 목록을 만들 때 사용하는 태그이다.  항목들을 점(•) 모양으로 자동 표시해줍니다.
```html
<ul>
    <li>1. HTML<br></li>
    <li>2. CSS<br></li>
    <li>3. JavaScript<br></li>
</ul>
<ul>
    <li>cmj</li>
</ul>
```

`<li>` 코드를 실행해보고 `<ul>`코드를 실행해보면 둘은 밀접한 관계인 것을 알 수 있다.

## \<ol>
순서가 중요한 목록을 만들 때 사용하는 태그이다. 항목 앞에 순서 번호(1., 2., 3.)가 자동 생성됩니다.
```html
<ol>
    <li>1. HTML<br></li>
    <li>2. CSS<br></li>
    <li>3. JavaScript<br></li>
</ol>
```
