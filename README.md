# AJAX (asynchronous javascript and xml)

+ status 200은 성공
+ status 404는 실패

```javascript
 <a href="#!html"onclick="fetchPage('html')">HTML</a>
 // #html은 해쉬라고한다. 위와 같이 #! 하는 이유는, 비동기 링크태그일경우 관습적으로 #!로 한다.  해쉬뱅이라고 칭한다.  
 
```

## SPA, ajax시 seo 대응으로는 pjax가 있다.

## fetch로 ie 하위대응하려면, fetch polyfill 검색한다
+ fetch polyfill은 ie10부터 적용된다.
+ https://github.com/github/fetch