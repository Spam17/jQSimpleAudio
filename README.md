# jQSimpleAudio
A jQuery audio player plugin that is responsive and touch-friendly. The UI is css-only, no images used.  

This repo is a redesign of <a title="Osvaldas Valutis' work" href="https://tympanus.net/codrops/2012/12/04/responsive-touch-friendly-audio-player/">Osvaldas Valutis' work</a>  

![jQSimpleAudio demo image](https://raw.githubusercontent.com/Spam17/jQSimpleAudio/master/img/cover.jpg)

I redesigned the UI to fit morden flat design, you can modify the css(such as color,height,width...) to fit your own website style.  

## How it works
The plugin replaces targeted `<audio>` elements with some HTML and JavaScript events attached to it.  
You can use it to your website or blog, Makrdown supported.  

## How to use it
Nothing special, just the typical usage of the `<audio>` tag.  
`<audio src="your-audio.mp3" preload="auto" controls></audio>`  
`<audio src="audio.wav" preload="auto" controls autoplay loop></audio>` autoplay&loop  

## How to install it
Place the  
`<link rel="stylesheet" href="css/audioplayer.css" />`  
`<script src="js/jquery.js"></script>`  
`<script src="js/audioplayer.min.js"></script>`   
into your header or footer.  

Place  
`<script>$( function() { $( 'audio' ).audioPlayer(); } );</script>`  
into your footer.  

call `<audio>` tag when you need attach a audio to your web page.  
`<audio src="audio.wav" preload="auto" controls></audio>`  


## How to install it using CDN jsdelivr 
Paste the following html code into your page: 

`<audio id="audio0" preload="auto" controls>`
`	<source src="https://img.imgsmail.ru/static.promo/sounds/notifier/bell.mp3"/>`
`</audio>`
`<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/spam17/jqsimpleaudio@1.0.1/css/audioplayer.css" />`
`<script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.min.js"></script>`
`<script src="https://cdn.jsdelivr.net/gh/spam17/jqsimpleaudio@1.0.1/js/audioplayer.min.js"></script>`
`<script>$( function() { $( '#audio0' ).audioPlayer(); } );</script>`

And adjust the display styles you need.


<a title="License" href="https://creativecommons.org/licenses/by-nc-sa/3.0/">License</a>  

