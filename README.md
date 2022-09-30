# scodetrex
def normal dead:var original = Runner.prototype.gameOver
Some code to help dino game easier
Dino Can't Die (A.k.a Immortal of anything xD):Runner.prototype.gameOver = function(){}
UnInmortal:Runner.prototype.gameOver = original
Set Speed For Dino:Runner.instance_.setSpeed(1000)
Jump more high:Runner.instance_.tRex.setJumpVelocity(10)
Set Gravity (can make u flying):Runner.instance_.tRex.config.GRAVITY = 0.1
Set High Score:Runner.instance_.distanceRan = *scorenum* / Runner.instance_.distanceMeter.config.COEFFICIENT
Auto Jump go brrr:

const autoPlayLoop = function() {
	const JUMP_SPEED = 50;
	const DISTANCE_BEFORE_JUMP = 120;

	const instance = window.Runner.instance_;
	const tRex = instance.tRex;

	if( tRex.jumping ) {
		requestAnimationFrame(autoPlayLoop);
		return;
	}

	const tRexPos = tRex.xPos;
	const obstacles = instance.horizon.obstacles;

	const nextObstacle = obstacles.find(o => o.xPos > tRexPos);

	if( nextObstacle && ( nextObstacle.xPos - tRexPos ) <= DISTANCE_BEFORE_JUMP ) {
		tRex.startJump(JUMP_SPEED)
	}

	requestAnimationFrame(autoPlayLoop);
}

requestAnimationFrame(autoPlayLoop);

