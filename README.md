# 9xd SVG Study Works

## 최민석(@curzy)
1. [어떻게 SVG를 시작했고 무엇을 공부할건가](http://curzy95.tumblr.com/post/155863963256/9xd-svg-%EC%8A%A4%ED%84%B0%EB%94%94-1%EC%A3%BC%EC%B0%A8)

2. [서울 지하철 9호선](http://codepen.io/Curzy/pen/dNvNmW)
  - SVG로만 그리기
  - 처음엔 각각 선들을 <line>으로 그리다 <polyline>으로 포인트만 주어 그림
  - <g>로 줄 수 있는 공통 속성들

3. [Racer](http://codepen.io/Curzy/pen/PWOvqO)
  - SVG로 간단한 오브젝트를 만들고 CSS로 애니메이션 먹이기
  - HTML에서의 <div>로 만든 그룹뿐만 아니라 <g>로도 CSS애니메이션 활용이 가능함

4. [Seoul Subway Map](http://codepen.io/Curzy/pen/jyXBaa?editors=1100)
  - [서울 월세 노선도](http://curzy.xyz/)에서 사용하던 SVG노선도 리팩토링: <g>의 각 하위요소가 가지던 공통 속성은 그룹에 부여, 컨트롤을 위한 class추가
  - line부분 ![line](/static/line.png)
  - text부분 ![text](/static/text.png)
  - 특정 라인 hover 액션 -> 그 외의 라인 블러로 처리하려고 했는데 JS가 필요할 것 같다.
