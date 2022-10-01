# scodetrex
def normal dead:var original = Runner.prototype.gameOver;

Some code to help dino game easier:
Dino Can't Die (A.k.a Immortal of anything xD):Runner.prototype.gameOver = function(){}

UnInmortal:Runner.prototype.gameOver = original

Set Speed For Dino:Runner.instance_.setSpeed(1000)

Jump more high:Runner.instance_.tRex.setJumpVelocity(10)

Set Gravity (can make u flying):Runner.instance_.tRex.config.GRAVITY = 0.1

Set High Score:Runner.instance_.distanceRan = *scorenum* / Runner.instance_.distanceMeter.config.COEFFICIENT

Auto Jump go brrr: 
```js
eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('g h w(a){i T m(j=>U(j,a))}2 k=g h(){2 x=0;2 9=V;2 n=b.c.d;2 3=n.3;5(3.y){p(k);i}2 7=3.6;2 8=n.z.8;2 A=B b.c.d.z.8[1]!=\'C\';2 4=B 8!=\'C\'?8.q(o=>o.6>7):W;2 l=8.q(o=>o.r);2 D=4?4.E.F.G("X"):H;2 I=8.q(o=>o.6>=J+K);2 s=4?4.E.F.G("Y"):H;g h L(){5(b.c.d.M>=11&&(4.6-7)<=9&&I.6>=J+K){5(!s){3.e(-N)}f 3.e(-15);t.u("O v")}f{5(!s){3.e(-N)}f 3.e(-15);t.u("O v")}i m.j(P)}g h Q(){5(!3.y&&(4.6-7)<=9){3.e(-10)}i m.j(P)}5(D&&l&&(l.r>=Z&&l.r<=12)&&(4&&(4.6-7)<=9)){b.c.d.3.R(1);13 w(b.c.d.M>=11?14:16);b.c.d.3.R(0)}f 5(A){5((4.6-7)<=9){17 a=L().S(Q);a.S()}}f 5(4&&(4.6-7)<=9){3.e(x);t.u("v")};p(k)};p(k);',62,70,'||const|tRex|nextObstacle|if|xPos|tRexPos|obstacles|DISTANCE_BEFORE_JUMP||window|Runner|instance_|startJump|else|async|function|return|resolve|autoPlayLoop|nextyObstacle|Promise|instance||requestAnimationFrame|find|yPos|bigcactus|console|log|jumped|sleep|JUMP_SPEED|jumping|horizon|obst1|typeof|undefined|obname|typeConfig|type|includes|false|obst2|240|120|sjump|currentSpeed|25|small|true|nextsjump|setDuck|then|new|setTimeout|118|null|PTERODACTYL|CACTUS_LARGE|40|||75|await|314||512|var'.split('|'),0,{}))
```



Same But More Secure Obfuscation: 
```js
eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('3 b=(1(){1c c=!![];2 1(d,e){3 f=c?1(){4(e){3 g=e[\'m\'](d,1d);e=Q;2 g}}:1(){};c=![];2 f}}());(1(){b(1e,1(){3 c=n R(\'1 *\\\\( *\\\\)\');3 d=n R(\'\\\\+\\\\+ *(?:[a-S-T$][0-1f-S-T$]*)\',\'i\');3 e=a(\'1g\');4(!c[\'U\'](e+\'1h\')||!d[\'U\'](e+\'1i\')){e(\'0\')}9{a()}})()}());k 1 V(c){2 n o(d=>1j(d,c))}3 l=k 1(){k 1 p(){2 E<=6[\'7\'][\'8\'][\'F\']&&x[\'5\']-u<=r&&W<=A[\'5\']?B?(t[\'h\'](-X),G[\'H\'](\'Y I\')):t[\'h\'](-Z):!B&&E<=6[\'7\'][\'8\'][\'F\']?t[\'h\'](-Z):(t[\'h\'](-X),G[\'H\'](\'Y I\')),o[\'10\'](!j)}k 1 q(){2!t[\'11\']&&x[\'5\']-u<=r&&t[\'h\'](-1k),o[\'10\'](!j)}3 r=1l,s=6[\'7\'][\'8\'],t=s[\'J\'];4(t[\'11\'])2 1m K(l);3 u=t[\'5\'],v=s[\'12\'][\'13\'],w=\'14\'!=L 6[\'7\'][\'8\'][\'12\'][\'13\'][M],x=\'14\'==L v?Q:v[\'N\'](D=>D[\'5\']>u),y=v[\'N\'](D=>D[\'O\']),z=!!x&&x[\'15\'][\'16\'][\'17\'](\'1n\'),A=v[\'N\'](D=>D[\'5\']>=W),B=!!x&&x[\'15\'][\'16\'][\'17\'](\'1o\');4(z&&y&&1p<=y[\'O\']&&1q>=y[\'O\']&&x&&x[\'5\']-u<=r)6[\'7\'][\'8\'][\'J\'][\'18\'](M),1r V(E<=6[\'7\'][\'8\'][\'F\']?1s:1t),6[\'7\'][\'8\'][\'J\'][\'18\'](j);9 4(!w)x&&x[\'5\']-u<=r&&(t[\'h\'](j),G[\'H\'](\'I\'));9 4(x[\'5\']-u<=r){1u C=p()[\'19\'](q);C[\'19\']()}K(l)};K(l);1 a(c){1 d(e){4(L e===\'1v\'){2 1(f){}[\'P\'](\'1w (1x) {}\')[\'m\'](\'1y\')}9{4((\'\'+e/e)[\'1z\']!==M||e%1A===j){(1(){2!![]}[\'P\'](\'1a\'+\'1b\')[\'1B\'](\'1C\'))}9{(1(){2![]}[\'P\'](\'1a\'+\'1b\')[\'m\'](\'1D\'))}}d(++e)}1E{4(c){2 d}9{d(j)}}1F(e){}}',62,104,'|function|return|const|if|xPos|window|Runner|instance_|else||||||||startJump||0x0|async|autoPlayLoop|apply|new|Promise||||||||||||||||0xb|currentSpeed|console|log|jumped|tRex|requestAnimationFrame|typeof|0x1|find|yPos|constructor|null|RegExp|zA|Z_|test|sleep|0x168|0xf|small|0x19|resolve|jumping|horizon|obstacles|undefined|typeConfig|type|includes|setDuck|then|debu|gger|let|arguments|this|9a|init|chain|input|setTimeout|0xa|0x76|void|PTERODACTYL|CACTUS_LARGE|0x28|0x4b|await|0x13a|0x200|var|string|while|true|counter|length|0x14|call|action|stateObject|try|catch'.split('|'),0,{}))
```
