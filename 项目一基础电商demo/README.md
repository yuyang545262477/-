##效果图
![效果图](catone.png)
![效果图](cattwo.png)

### 知识点
    1.基础的页面搭建 html构架
    2.基础的样式增势 css 使用
    3.jQuery的日常使用。

>如何获取屏幕高度


    (function($){
        $(document).ready(function(){
            $(window).scrollTop(function(){
                var screenHeight = $(document).scrollTop();
            })
        })
    }(jQuery);

>如何获取元素偏移量


     (function($){
        $(document).ready(function(){
            $(window).scrollTop(function(){
                var ElementOffSet = $('div').offset().top;
            })
        })
    }(jQuery);


>使用jQuery基础的dom操作。

    增:addClass 删:removeClass 改:attr('element','value') 查:attr('element')。