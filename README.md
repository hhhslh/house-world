# house-world
#### 房天下页面
* 自动轮播---定时器方法
```
function exportTimer(){
   timer = setInterval(function(){
         goLeft();
   },2000);
}
exportTimer();
```
* 选项卡---jQuery效果（隐藏/显示）
```
$(".bottom-child li").hover(function(){
	    $(this).addClass("selected").siblings().removeClass("selected");
	    var index = $(this).index();
	    $(".bottom-box").eq(index).show().siblings().hide();
});
 ```
