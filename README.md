# mobiCarousel
移动端幻灯片插件
1.说明
  1.1 此插件基于jquery
  1.2 为了减少不必要的代码，只适用于移动端，只支持滑动事件
2.使用方法
  2.1 可以配置四个参数，参数的配置方式为在div标签上设置自定义属性data-setting='{"autoplay":true,"duration":700,"delay":4000,"nav":true}'
      "autoplay"是否自动播放，接受true或false；"duration"动画持续时间，毫秒值；"delay"播放的间隔时间，毫秒值；"nav"是否显示图片导航，接受true或false。
  2.2 调用方式为： Carousel.init($('.carousel')); 。carousel为容器的类名，页面中可以同时拥有多个幻灯片，而只需要使用这一句代码即可实现，因为每个幻灯片的参数全部是在自定义属性上面设置的，互不影响。      
