# HTML, CSS, ES5, jQuery 에서 복습 및 배울 것
    1. css FlexModel
    2. css Bootstrap
    3. Swiper Plugin
    4. Javascript 심도 있게
    5. jQuery 리뷰

# jQuery 리뷰
## jQuery 는 함수(메서드)로 만들어져 있다.
```js
$(document).ready(function(){});
$(".wrap").hide(); //$도 함수명임, var $ = jQuery

//다음 중 올바른 표현은?
$(".a").hasClass("b").hide();
$(".a").append('<div>A</div>').hide();
$(".a").width().hide();
$(".a").attr("id").hide();

//다음의 문장을 Javascript로 변환하세요.
$("#sample")
document.getElementById("sample");
```
0. Selector (선택자)
```js
// 태그나 객체를 $()로 실행하면 jQuery객체가 리턴된다.
$(".a")
$("div")
$(".a > div")
$(document.getElementById('sample'))
$('<div>A</div>')

//$()[0] => 자바스크립트가 된다
$("sample")[0] // 자바스크립트(제이쿼리 객체 0번에 자바스크립트 있음)
```


1. Animation
```js
//제이쿼리객체($)가 있어야 쓸 수 있음
hide()
show()
fadeIn()
fadeOut()
slideUp()
slideDown()
toggle()
fadeToggle()
slideToggle()
animate()
```
2. DOM(Document Object Model)

3. Attribute (html 속성 조작)

4. CSS

5. Dimension (단위, 즉 scrolltop, width 등)

6. Event

7. getter/setter
    -html(), text(), css(), attr()