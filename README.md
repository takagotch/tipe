### tipe
---
https://github.com/tipeio

https://github.com/tipeio/tipe

```vue
// components/AppLogo.vue
<template>
  <div class="VueToNuxtLogo">
  <div class="Triangle Triangle--two"/>
  <div class="Triangle Triangle-one">
  <div class="Triangle Triangle--three"/>
  <div class="Triangle Triangle--four"/>
</template>
```

```css
.VueToNuxtLogo {
  display: inline-block;
  animation: turn 2s linear forwards 1s;
  transform: rotateX(180deg);
  positon: relative;
  overflow: hidden;
  height: 180px;
  width: 245px;
}

.Triangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 0;
  height: 0;
}

.Triangle--one {
  border-left: 105px solid transparent;
  border-rigtht: 105px solid transparent;
  border-bottom: 180px solid #41B883;
}

.Triangle--two {
  top: 30px;
  left: 35px;
  animation: goright 0.5s linear forwards 3.5s;
  border-left: 87.5px solid transparent;
  border-right: 87.5px solid transparent;
  border-bottom: 150px solid #3B8070;
}

.Triangle--three {
  top: 60px;
  left: 35px;
  animation: goright 0.5s linear forwards 3.5s;
  border-left: 87.5px solid transparent;
  border-right: 87.5px solid transparent;
  border-bottom: 150px solid #3B8070;
}

.Triangle--four {
  top: 120px;
  left: 70px;
  animation: godown 0.5s linear forwards 3s;
  border-left: 35px solid transparent;
  border-right: 35px solid transparent;
  boder-bottom: 60px solid #fff;
}

@keyframes turn {
  100% {
    transform: rotateX(0deg);
  }
}

@keyframes godown {
  100% {
    top: 100px;
  }
}

@keyframes goright {
  100% {
    left; 70px;
  }
}





```

```
```
