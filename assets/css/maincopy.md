---
---

/*
 *    Minimal Mistakes Jekyll Theme
 *
 *  - Michael Rose
 *  - mademistakes.com
 *  - https://twitter.com/mmistakes
 *
*/

@import "vendor/breakpoint/breakpoint"; // media query mixins
@import "variables";
@import "mixins";
@import "vendor/susy/susy";

@import "reset";
@import "base";
body::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('d2.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    z-index: -1;
}
.publication {
    color: #333; /* 更深的颜色 */
}
.publication-block {
    background-color: #f0f8ff; /* 淡蓝色背景 */
    padding: 20px; /* 添加一些内边距使文本不会太贴近边缘 */
    margin-bottom: 20px; /* 如果有多个块，每个块之间添加一些间隔 */
    border-radius: 8px; /* 可选，为块添加圆角边框 */
}
.archive__item {
    background-color: #ffffff; /* 白色背景 */
    border: 1px solid #dddddd; /* 灰色边框 */
    border-radius: 8px; /* 圆角边框 */
    padding: 15px; /* 内边距 */
    margin-bottom: 20px; /* 底部外边距，保持出版物之间有间隔 */
    box-shadow: 0 2px 5px rgba(0,0,0,0.1); 
}

@import "utilities";
@import "animations";
@import "tables";
@import "buttons";
@import "notices";
@import "masthead";
@import "navigation";
@import "footer";
@import "syntax";

@import "forms";

@import "page";
@import "archive";
/* 修改整个 archive__item 区域的字体样式 */
.archive__item {
    font-family: 'Arial', sans-serif; /* 修改字体 */
    font-size: 14px; /* 修改字体大小 */
    color: #333333; /* 修改字体颜色 */
}

/* 特别修改标题的样式 */
.archive__item-title {
    font-family: 'Georgia', serif;
    font-size: 16px;
    color: #0056b3; /* 深蓝色 */
}

/* 修改摘要的字体和颜色 */
.archive__item-excerpt {
    font-size: 12px;
    color: #666666; /* 淡灰色 */
}

/* 修改链接颜色 */
.archive__item a {
    color: #1a0dab; /* 蓝色链接 */
}

/* 修改图片描述文本的样式 */
.wordwrap {
    font-family: 'Great Vibes', cursive; /* 设置花体字体 */
    font-size: 14px;
    color: #333333; 
}

@import "sidebar";

@import "vendor/font-awesome/fontawesome";
@import "vendor/font-awesome/solid";
@import "vendor/font-awesome/brands";
@import "vendor/magnific-popup/magnific-popup";
@import "print";