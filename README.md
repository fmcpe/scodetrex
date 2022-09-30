# scodetrex
def normal dead:var original = Runner.prototype.gameOver;

Some code to help dino game easier:
Dino Can't Die (A.k.a Immortal of anything xD):Runner.prototype.gameOver = function(){}

UnInmortal:Runner.prototype.gameOver = original

Set Speed For Dino:Runner.instance_.setSpeed(1000)

Jump more high:Runner.instance_.tRex.setJumpVelocity(10)

Set Gravity (can make u flying):Runner.instance_.tRex.config.GRAVITY = 0.1

Set High Score:Runner.instance_.distanceRan = *scorenum* / Runner.instance_.distanceMeter.config.COEFFICIENT

Auto Jump go brrr: eval(function(p,a,c,k,e,r){e=function(c){return c.toString(a)};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('0 2=d(){0 9=e;0 a=f;0 3=g.h.i;0 1=3.1;b(1.j){4(2);k}0 5=1.6;0 7=3.l.7;0 8=7.m(c=>c.6>5);b(8&&(8.6-5)<=a){1.n(9)};4(2)};4(2);',24,24,'const|tRex|autoPlayLoop|instance|requestAnimationFrame|tRexPos|xPos|obstacles|nextObstacle|JUMP_SPEED|DISTANCE_BEFORE_JUMP|if|o|function|50|120|window|Runner|instance_|jumping|return|horizon|find|startJump'.split('|'),0,{}))
