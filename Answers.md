If you had to teach someone with basic CSS knowledge what a preprocessor was, how would you describe it?
Preprocessing is simply a more robust syntax for CSS written in a different language. That language is then compiled into normal CSS
Pre-processors, with their advanced features, helped to achieve writing reusable, maintainable and extensible codes in CSS. By using a pre-processor, you can easily increase your productivity, and decrease the amount of code you are writing in a project.


What is the command in node package manager (npm) to install LESS globally on your computer?
npm install -g less

Please provide an example of a mixin you have used in a project this week
.border(@width){
    border:with solid #ddd;
    &:hover{
        boder-color:#999;
    }
}
h1{
    .border(5px)
}


What is the difference between fixed layout, adaptive layout, and fluid layout?

Fixed (aka static) layout has a fixed width in pixels. The ‘container’ of the website is programmed to not move (that’s where the name ‘static’ comes from).

With fluid layout you specify sizes not in pixels, but in percentages. Meaning, if the screen size changes, the proportion of elements will stay the same.

Adaptive layout means that there are several versions of the layout which are displayed based on the screen size of the viewer. Think of it as several fixed layout designs, layout A is displayed when the screen size is within size range 


Why do we need to use the CSS property max-width in a responsive website?

Using max-width will improve the browser's handling of small windows. This is important when making a site usable on small devices: