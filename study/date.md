
# history
- 5.19: 
    - detail: 本想从源码开始突破，问了百度的ai之后发现应该先学习gsap怎么用，然后看gsap官网，被丝滑的横向滚动吸住，想起来showmebug那个网站，发现两者用的是一样的，然后回顾之前的attempt里的sticky，总结sticky现存的问题，然后看gsap官网时有一些showcase，点进去几个发现一个网站用了反色圈，学习了mix-blend-mode属性
    - abstract: 回顾sticky；学习mix-blend-mode
    - tomorrow: 学习gsap使用
- 5.20:
    - detail: 最简单的使用方法，在html里通过esm/cdn来使用gsap，如果需要在react中使用，需要用@gsap/react的usegsap钩子，且有些坑，之后用的时候详细学一下，然后又被gsap的丝滑滚动吸住，历经千辛万苦终于知道了body的特殊性，也就是fix不阻止body滚动，借此契机把之前的横向滚动原理给搞清楚了，再把kilalabest的stikcy的bug修了，坑爹的overflow-x-hidden阻止我的sticky🤬
    - abstract: 学习gsap最基本使用；领悟gsap丝滑滚动原理；彻悟sticky；修复kilalabest中sticky相关
    - tomorrow: 学习gsap使用