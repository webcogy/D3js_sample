# D3js

#### 데이터 시각화 라이브러리 (주로 차트에 이용)

- svg + jQuery 체이닝문법

참고 사이트 : https://www.dashingd3js.com/d3-tutorial

```
// 기본 svg
<!--직사각형-->
<svg width="50" height="50">
    <rect x="0" y="0" width="50" height="50" fill="green" >
    </rect>
</svg>

<!--원-->
<svg width="50" height="50">
    <circle cx="25" cy="25" r="25" fill="purple">
    </circle>
</svg>

<!--타원-->
<svg width="50" height="50">
    <ellipse cx="25" cy="25" rx="15" ry="10" fill="red">
    </ellipse>
</svg>

<!--직선-->
<svg width="50" height="50">
    <line x1="5" y1="5" x2="40" y2="40" stroke="gray" stroke-width="5">
    </line>
</svg>

<!--폴리라인-->
<svg width="50" height="50">
    <polyline fill="none" stroke="blue" stroke-width="2"
        points="05,30
                15,30
                15,20
                25,20
                25,10
                35,10">
    </polyline>
</svg>

<!--다각형 -->
<svg width="50" height="50">
    <polygon fill="yellow" stroke="blue" stroke-width="2"
        points="05,30
                15,10
                25,30">
    </polygon>
</svg>
```
