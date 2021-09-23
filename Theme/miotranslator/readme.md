# MioTranslator.com Custom
## Vì có người muốn white theme và người thì muốn dark theme

- Để dùng cái này cần 1 extension gọi là  [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en) (lưu ý [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en) không phải [Stylish](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en) mà dùng cái đó cũng được)
- Vì có lẽ Admin [Tsuki Ga Michibiku Isekai Douchuu VN-Fansub](https://miotranslator.com/) đã mệt nên mình nghỉ không nên làm phiền kêu tạo thêm switch mode qua white hoặc dark nên mình làm cái này để các bạn có thể tự chỉnh màu mình thích
- Để có [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en) thì các bạn click vào chữ "[Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en)" bất kỳ
- Cái này rất đơn giản và ai cũng có thể làm được và mọi người có thể chỉnh sửa nếu thích
## Installation
- Xem cách setup ở đây: https://streamable.com/yj1jrb
- Nguồn: https://github.com/Irilith/irisproject/tree/main/Theme/miotranslator
- [Raw](https://irilith.github.io/irisproject/Theme/miotranslator/miotranslatorcustomcolor.css): https://irilith.github.io/irisproject/Theme/miotranslator/miotranslatorcustomcolor.css
```css
/* ==UserStyle==
@name         miotranslator.com custom color picker
@namespace    https://github.com/Irilith/irisproject.github.io
@version      1.0.0
@author       Lilith Iris#7707
==/UserStyle== */

:root {
 /*
Để chọn color (Hex code): https://g.co/kgs/HWCNDd
*/
    --background: #1b1e2f;
    --textcolor: #f2f2f2;
    --textsize: 25px; /* chổ này chỉnh sửa độ lớn của chữ https://irilith.github.io/irisproject/Theme/miotranslator/Preview/textsize.gif */
}
 
body {
    color: var(--textcolor);
    background-color: var(--background);
    font-size: var(--textsize);
}

.has-foreground-color {
    color: var(--textcolor);
}
.main-navigation a:link, .main-navigation a:visited {
    color: var(--textcolor);
}
.main-navigation {
    color: var(--textcolor);
}
.site-info {
    color: var(--textcolor);
}
.site-info a:link, .site-info a:visited {
    color: var(--textcolor);
}
```
