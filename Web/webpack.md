### Webpack

- 파일을 하나로 합쳐주는 대표적인 번들러
- 왜 합치는 걸까?

  - http 요청이 비효율적이기 때문에
  - 웹페이지의 많은 데이터 (js, css, 이미지 등) 수많은 파일을 요청해야된다
  - http/2.0의 경우 하나의 커넥션에 여러 요청을 넣고 server push도 있지만 그래도 요청 횟수가 더 적은 것이 좋다
  - 요청 수를 줄이는 법 :이미지 스프라이트, js, css 파일 압축
  - 웹팩은 파일을 하나로 합쳐주면서 크로스 브라우징 대응도 하고 압축도 해준다

- js 파일들의 의존성
  - js도 모듈 개념이 생겼다. import나 require로 서로 간에 의존을 한다.
  - 하나의 파일이 크면 chunkSize도 지정하여 분할할 수 있다.
