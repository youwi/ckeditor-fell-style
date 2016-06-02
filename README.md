    ckeditor 的插件,
    可以出bootsrop一样的标签
    可以做出标签,如下图,注意不是button.
    样式是内联的,如字体大小颜色一样.

![image](http://fribly.com/wp-content/uploads/2014/01/Bootstrap-3-Vector-UI-Kit.png)
![image](http://www.myexception.cn/img/2015/07/11/060416181.png)

    配置如下:
    CKEDITOR.editorConfig = function( config ) {
    	config.extraPlugins = 'fellstyle';
    	config.enterMode = CKEDITOR.ENTER_BR;
    };

    关于维护:实在没有时间,能用就行,bug很多.