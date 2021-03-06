#jsonp 란?

전통적인 웹 브라우져에서는 same-origin policy (SOP) 정책에 따라 다른 도메인간의 request을 제한하고 있다. 
그러나 ```<script/>``` 태그는 same-origin-policy (SOP) 정책에 속하지 않는다는 사실을 근거로, 서로 다른 도메인간의 
javascript 호출을 위하여 jsonp (또는 json with padding) 이 사용되었다.

jsonp 와 ajax 비교:
![jsonp 와 ajax 비교](http://dev.epiloum.net/wp-content/uploads/2015/03/comparison_between_ajax_and_jsonp.png)

즉 일반적인 get  방식은 차단되므로 cdn방식처럼 ```<script></script>```로 감싸서 데이터를 가져온다.
그후 callback함수를 통해서 data를 파싱하게 된다.
```javascript
<script type="text/javascript" src="http://seotest.com/result.json"></script>
<script>
function callback( data ) {
    // data 는 result.json 의 데이터가 들어오게 된다.
}
</script>
```
위의 소스처럼 callback 이라는 함수를 만들면, seotest.com/result.json 는 선언된 callback 함수를 호출하게 될것이다. 
다른 도메인이라고 할지라도 문제 없이 json 데이터를 사용하게 되는 것이다.
