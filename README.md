# KOFIH 이종욱체

[배포처 바로가기](https://www.koddi.or.kr/ud/sub1_2)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `KOFIH DrLEEJW`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/KOFIHDrLEEJW.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/KOFIHDrLEEJW.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'KOFIH DrLEEJW';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/KOFIHDrLEEJW-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/KOFIHDrLEEJW-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/KOFIHDrLEEJW-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/KOFIHDrLEEJW-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'KOFIH DrLEEJW';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/KOFIHDrLEEJW-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/KOFIHDrLEEJW-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/KOFIHDrLEEJW-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/KOFIHDrLEEJW-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/subsets/KOFIHDrLEEJW-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KOFIHDrLEEJW/subsets/KOFIHDrLEEJW-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "KOFIH DrLEEJW", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
KOFIH 이종욱체의 지적 재산권은 한국국제보건의료재단에 있습니다. KOFIH 이종욱체는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 인쇄물, 광고물, 온라인 등 상업적 목적으로 사용할 수 있습니다. 또한 사용자들도 다른 이에게 자유롭게 배포하실 수 있습니다. 
 
단, 한국국제보건의료재단의 허락 없이는 KOFIH 이종욱체를 사용자가 임의로 수정 및 재배포할 수 없으며, 배포되는 모양 그대로 사용해야 됩니다. 또한 글꼴 자체를 유료로 판매하는 것은 금지하며 KOFIH 이종욱체를 사용한 인쇄물, 광고물(온라인 포함)의 이미지는 한국국제보건의료재단의 프로모션을 위해 활용될 수 있습니다. 이를 원치 않는 사용자는 언제든지 본 기관에 요청하실 수 있습니다.
```
