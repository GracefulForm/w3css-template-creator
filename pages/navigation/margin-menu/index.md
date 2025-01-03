# Margined Menu
<!-- position: 3 -->

### Sample Image

![](https://raw.githubusercontent.com/GracefulForm/w3css-template-creator/refs/heads/master/pages/images/menu3.png)

### Code

```html
<nav class="w3-container w3-black"><!-- Change the color of your menu bar here. -->
    <div id="largeNav" class="w3-bar w3-content">
        <a href="#" class="w3-bar-item w3-button">Home</a>
        <a href="#" class="w3-bar-item w3-button w3-hide-small w3-right">Link 3</a>
        <a href="#" class="w3-bar-item w3-button w3-hide-small w3-right">Link 2</a>
        <a href="#" class="w3-bar-item w3-button w3-hide-small w3-right">Link 1</a>
        <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="myFunction()"><i class="ri-menu-line"></i></a>        
    </div>
    <div id="miniNav" class="w3-bar-block w3-hide w3-hide-large w3-hide-medium  w3-black"><!-- Change the color of your small screen menu here. -->
        <a href="#" class="w3-bar-item w3-button">Link 1</a>
        <a href="#" class="w3-bar-item w3-button">Link 2</a>
        <a href="#" class="w3-bar-item w3-button">Link 3</a>
    </div>
</nav>
```

### More Information

* The menu items have margins on each side.
* This menu will resize for small screens.
* Don't forget to put the links in both the "largeNav" menu and the "miniNav" menu.
* You can quickly use [word colors](https://www.w3schools.com/w3css/w3css_colors.asp) to change your menu bar. It will automatically change the text color to light or dark, depending on the menu bar's background color.