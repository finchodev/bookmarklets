# Bookmarklet COllection
### I do not condone any illegal/immoral use of these bookmarklets, these are listed strictly for educational purposes!

> ## Edit+
#### Edit+ is a toggleable way to edit any text on the page that the bookmarklet is used on, this is client side and does not cause damage to the site, will reset or reload.
`javascript:if(document.body.contentEditable != 'true')void(document.body.contentEditable = 'true');else void(document.body.contentEditable = 'false');`

> ## Calculator
#### Calculator is a popup box that can solve any simple math equation on any page you choose!
`javascript:eval('function calc(){_o=prompt(_t,_z);if(_o!=\'\'&&_o!=null&&_o.toUpperCase()==_o.toLowerCase())_z=eval(_o);}');_t='JAVASCRIPTER.NET Calculator - Input the expression to be calculated:';_z='';calc();while(_o!=''&&_o!=null&&_o.toUpperCase()==_o.toLowerCase())calc()`

> ## History Flooder
#### Have something to hide? Use this bookmarklet to spam your history with your input of websites!
`javascript:var num=prompt("History flood amount: "); done = false; x = window.location.href; for (var i=1; i<=num; i++) {history.pushState(0, 0, i==num?x:i.toString()); if(i==num){done=true}}if(done===true){alert("History flood successful! "+window.location.href+" now appears in your history "+num+(num==1?" time.":" times."))}`

> ## X-Ray Googles
#### This lets you edit the raw HTMl of a page (Client-Sided)
`javascript:(function () {var script=document.createElement('script');script.src='https://x-ray-goggles.mouse.org/webxray.js';script.className='webxray';script.setAttribute('data-lang','en-US');script.setAttribute('data-baseuri','https://x-ray-goggles.mouse.org');document.body.appendChild(script);}())`

> ## Portable Minecraft
#### Play a mock minecraft on any webpage! Recovered by luphoria.
`javascript:(function(){window.mcbmRootURI='https://luphoria.com/MCanywhere/';window.mcbmScriptURI='mcbm.min.js';window.mcbmLang='eng';var s,ss=window.mcbmRootURI+'js/mcbm-load.min.js';s=document.createElement('script');s.src=ss;document.body.appendChild(s);})();`

