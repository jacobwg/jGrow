jGrow is a [jQuery](http://jquery.com) [plugin](http://plugins.jquery.com) that allows for auto-growing textareas that adjust size according to the length of the text.
        
It works smoothly with **jQuery 1.2.x** and **1.3.x**. It was tested on IE6+, Firefox 2+, Opera 9.x+ (including 10.00 beta), Safari 3.x+ (including 4 Public Beta), Google Chrome 2.x (including developer release) and no bugs have spotted yet.
        
[jQuery page](http://plugins.jquery.com/project/jGrow)

[![Click here to lend your support to: jGrow and make a donation at www.pledgie.com!](http://www.pledgie.com/campaigns/7333.png)](http://www.pledgie.com/campaigns/7333)

## Installation

jGrow requires jQuery, so be sure that jQuery is installed on your webpage:

    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.3/jquery.min.js" type="text/javascript"></script>
        
Include the jGrow include tag *after* jQuery:

    <script src="jquery.jgrow-0.6.js" type="text/javascript"></script>
        
##Usage

Usage is simple:

    $("textarea#sample1").jGrow();
        
And jGrow is ready to use!  If you want to specify a maximum height, use the following syntax:

    $("textarea#sample2").jGrow({
      max_height: "300px"
    });
