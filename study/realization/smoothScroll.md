
# gsap丝滑滚动的实现推测
如果一个元素长宽铺满了屏幕，且有fixed属性，那么zindex更小的任何元素都无法滚动，除了body/document.documentElement
那么此时如果把要根据滚动来动画的元素放在fixed的元素里，就可以实现看上去滚动导致了动画，且此时元素可交互
而动画包括了上下移动，也就是看起来的滚动
要丝滑滚动的东西放在fixed里，然后靠计算body的scrollTop来得出使用tween的translate3d值，就实现了丝滑滚动