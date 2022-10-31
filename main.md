# Bookmarklet Collection
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

> ## Portable Snake Game
#### Game window appears on your page that you can play snake on.

`javascript:Q=32;m=b=Q*Q;a=[P=l=u=d=p=S=w=0];u=8;f=(h=j=t=(b+Q)/2)-1;(B=(D=document).body).appendChild(x=D.createElement("p"));(X=x.style).position="fixed";X.left=X.top=0;X.background="#FFF%22;x.innerHTML=%22%3Cp%3E%3C/p%3E%3Ccanvas%3E%22;v=(s=x.childNodes)[0];(s=s[1]).width=s.height=5*Q;c=s.getContext(%222d%22);%20onkeydown=onblur=F=function(e,g){g?a[f]?(w+=m,f=Math.random(l+=8)*(R=Q-2)*R|(u=0),F(f+=Q+1+2*(f/R|0),g)):F(f):0%3Ee?(l?--l:(y=t,t=a[t]-2,F(y)),S+=(w*=0.8)/4,m=999/(u++%20+10),a[h+=[-1,-Q,1,Q][d=p]]?B.removeChild(x,alert(%22Game%20Over!\nThe%20game%20window%20will%20now%20be%20closed.\n\nMade%20by%203kh0%22)):(F(h),F(e,j=h),v.innerHTML=P?(setTimeout(F,50,e,0),S|0):%22Press%20P%20to%20play!%20Made%20by%203kh0%22)):-e?(y=(a[e]=e%3CQ|e%3E=Q*Q-Q|!(e%Q)|e%Q==Q-1|2*(e==h))+(e==f),e==h&&(a[j]=2+h),c.fillStyle=%22hsl(%22+99*!a[e]+%22,%22+2*m+%22%,%22+50*y+%22%)%22,c.fillRect(e%Q*5,5*(e/Q|0),5,5)):isNaN(y=e.keyCode-37)|43==y?(P=y&&!P)&&F(-1):%20p=!P|y&-4|!(y^2^d)?p:y;return!1};for(;--b;F(b));void%20F(-1);`
