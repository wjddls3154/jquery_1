# jQuery 정리 모음

![image](https://user-images.githubusercontent.com/37132897/158531264-6056a017-1074-470c-8323-4f42ed03284e.png)


## jQuery
- 라이브러리 : 자주 사용하는 코드를 재사용 할 수 있는 형태로 가공하여 효율을 높여주는 코드 
- jsp의 가장 유명한 라이브러리 : jQuery - 빠르고,작고, 기능이 많은 jsp 라이브러리

jQuery에 대해 참고할 수 있는 사이트
- http://jquery.com/
- http://www.jqueryrain.com/

jQuery 사용방법 : 1.jQuery CDN, 2.다운로드
- 구글에 jQuery CDN 쳐서 들어가서, 코드 복사해서 body 안에 붙여주면 사용가능

jQuery 필터
- eq - equal(=)
- ne - not equal(<>)
- lt - little (<)
- le - little or equal (<=)
- gt - greater (>)
- ge - greater or equal (>=)

기본 필터 (index 는 음수도 허락한다.)
- eq(index)
- even - 짝수
- odd - 홀수
- first
- last
- :gt(index) - index 보다, 큰 숫자 선택
- :lt(index) - index 보다, 작은 숫자 선택
- :not(filter)

속성 필터
- attributeContains - input[name*='man']
- attributeEquals - input[name*='newsletter']

차일드(몇번째 자식인지) 필터
- :first-child, :last-child
- :nth-child(2)
- :nth-child(even), :nth-child(odd)
- :nth-child(3n)

컨텐츠 필터
- :contains(text)
- :empty
- :has(selector)

기타
- Jquery 어떻게 사용되는지 궁금하면, jquery 사이트에서 해당 기능 검색하면 코드와 예시를 볼수있다.
- 이벤트 : 사용자가 버튼을 클릭하거나, 마우스를 스크롤하거나, 필드의 내용을 바꾸는 등의 행동같은 것

jQuery 플러그인
- jQuery UI (progressbar, selectmenu, etc)
- jQuery validation (유효성 검사)
- jQuery lightbox (모달 창처럼 만들어줌)
- etc

