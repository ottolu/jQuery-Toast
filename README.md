jQuery-Toast
=

##Introduction
<hr>
A Simple Android Style MessageBox(Toast).

Rely on jQuery.

##Quick Start
<hr>
Remember to call `init` function in order to insert the style

    Toast.init();
    
Then You can try

    Toast("hello, world").show();
    
Further

    Toast({
       text: "hello, world", 
       time: 2000, 
       autoPos: false, 
       x: function(){ return 100;},
       y: 200 
    }).show();
    
##Tips
<hr>
The default position is calculated automaticly.

If you want to control by yourself, please set `autoPos` to false, then input the `x` and `y` as you want ( **function can be accept, too** ) .

