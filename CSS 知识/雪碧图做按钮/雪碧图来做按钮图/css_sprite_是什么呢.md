### CSS Sprite 是什么呢？
一堆小图合并到一张大图上，再利用CSS的background-image,background-repeat,background-position进行精确定位所需的小图位置，将其展现出来，我感觉就像是，图片的容器相当于一个小窗口，里面是一整张图片，然后通过background-position来挪动后面的大图位置，然后让需要的小区域的小图展现出来
主要作用：
可以大量减少页面的http请求，提升页面性能；
减少图片的字节，貌似3张图片合并成1张图片的字节总是小于这3张图片的字节总和；
解决了网页设计师在图片命名上的困扰，只需对一张集合的图片上命名就可以了，不需要对每一个小元素进行命名，从而提高了网页的制作效率