# hello-world
@charset "UTF-8";
/*
Animate.css - http://daneden.me/animate
Licensed under the MIT license

Copyright (c) 2013 Daniel Eden

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
*/
body { /* Addresses a small issue in webkit: http://bit.ly/NEdoDq */
	-webkit-backface-visibility: hidden;
}
.animated {
	-webkit-animation-duration: 1s;
	   -moz-animation-duration: 1s;
	     -o-animation-duration: 1s;
	        animation-duration: 1s;
	-webkit-animation-fill-mode: both;
	   -moz-animation-fill-mode: both;
	     -o-animation-fill-mode: both;
	        animation-fill-mode: both;
}

.animated.hinge {
	-webkit-animation-duration: 2s;
	   -moz-animation-duration: 2s;
	     -o-animation-duration: 2s;
	        animation-duration: 2s;
}

@-webkit-keyframes flash {
	0%, 50%, 100% {opacity: 1;}	
	25%, 75% {opacity: 0;}
}

@-moz-keyframes flash {
	0%, 50%, 100% {opacity: 1;}	
	25%, 75% {opacity: 0;}
}

@-o-keyframes flash {
	0%, 50%, 100% {opacity: 1;}	
	25%, 75% {opacity: 0;}
}

@keyframes flash {
	0%, 50%, 100% {opacity: 1;}	
	25%, 75% {opacity: 0;}
}

.flash {
	-webkit-animation-name: flash;
	-moz-animation-name: flash;
	-o-animation-name: flash;
	animation-name: flash;
}
@-webkit-keyframes shake {
	0%, 100% {-webkit-transform: translateX(0);}
	10%, 30%, 50%, 70%, 90% {-webkit-transform: translateX(-10px);}
	20%, 40%, 60%, 80% {-webkit-transform: translateX(10px);}
}

@-moz-keyframes shake {
	0%, 100% {-moz-transform: translateX(0);}
	10%, 30%, 50%, 70%, 90% {-moz-transform: translateX(-10px);}
	20%, 40%, 60%, 80% {-moz-transform: translateX(10px);}
}

@-o-keyframes shake {
	0%, 100% {-o-transform: translateX(0);}
	10%, 30%, 50%, 70%, 90% {-o-transform: translateX(-10px);}
	20%, 40%, 60%, 80% {-o-transform: translateX(10px);}
}

@keyframes shake {
	0%, 100% {transform: translateX(0);}
	10%, 30%, 50%, 70%, 90% {transform: translateX(-10px);}
	20%, 40%, 60%, 80% {transform: translateX(10px);}
}

.shake {
	-webkit-animation-name: shake;
	-moz-animation-name: shake;
	-o-animation-name: shake;
	animation-name: shake;
}
@-webkit-keyframes bounce {
	0%, 20%, 50%, 80%, 100% {-webkit-transform: translateY(0);}
	40% {-webkit-transform: translateY(-30px);}
	60% {-webkit-transform: translateY(-15px);}
}

@-moz-keyframes bounce {
	0%, 20%, 50%, 80%, 100% {-moz-transform: translateY(0);}
	40% {-moz-transform: translateY(-30px);}
	60% {-moz-transform: translateY(-15px);}
}

@-o-keyframes bounce {
	0%, 20%, 50%, 80%, 100% {-o-transform: translateY(0);}
	40% {-o-transform: translateY(-30px);}
	60% {-o-transform: translateY(-15px);}
}
@keyframes bounce {
	0%, 20%, 50%, 80%, 100% {transform: translateY(0);}
	40% {transform: translateY(-30px);}
	60% {transform: translateY(-15px);}
}

.bounce {
	-webkit-animation-name: bounce;
	-moz-animation-name: bounce;
	-o-animation-name: bounce;
	animation-name: bounce;
}
@-webkit-keyframes tada {
	0% {-webkit-transform: scale(1);}	
	10%, 20% {-webkit-transform: scale(0.9) rotate(-3deg);}
	30%, 50%, 70%, 90% {-webkit-transform: scale(1.1) rotate(3deg);}
	40%, 60%, 80% {-webkit-transform: scale(1.1) rotate(-3deg);}
	100% {-webkit-transform: scale(1) rotate(0);}
}

@-moz-keyframes tada {
	0% {-moz-transform: scale(1);}	
	10%, 20% {-moz-transform: scale(0.9) rotate(-3deg);}
	30%, 50%, 70%, 90% {-moz-transform: scale(1.1) rotate(3deg);}
	40%, 60%, 80% {-moz-transform: scale(1.1) rotate(-3deg);}
	100% {-moz-transform: scale(1) rotate(0);}
}

@-o-keyframes tada {
	0% {-o-transform: scale(1);}	
	10%, 20% {-o-transform: scale(0.9) rotate(-3deg);}
	30%, 50%, 70%, 90% {-o-transform: scale(1.1) rotate(3deg);}
	40%, 60%, 80% {-o-transform: scale(1.1) rotate(-3deg);}
	100% {-o-transform: scale(1) rotate(0);}
}

@keyframes tada {
	0% {transform: scale(1);}	
	10%, 20% {transform: scale(0.9) rotate(-3deg);}
	30%, 50%, 70%, 90% {transform: scale(1.1) rotate(3deg);}
	40%, 60%, 80% {transform: scale(1.1) rotate(-3deg);}
	100% {transform: scale(1) rotate(0);}
}

.tada {
	-webkit-animation-name: tada;
	-moz-animation-name: tada;
	-o-animation-name: tada;
	animation-name: tada;
}
@-webkit-keyframes swing {
	20%, 40%, 60%, 80%, 100% { -webkit-transform-origin: top center; }
	20% { -webkit-transform: rotate(15deg); }	
	40% { -webkit-transform: rotate(-10deg); }
	60% { -webkit-transform: rotate(5deg); }	
	80% { -webkit-transform: rotate(-5deg); }	
	100% { -webkit-transform: rotate(0deg); }
}

@-moz-keyframes swing {
	20% { -moz-transform: rotate(15deg); }	
	40% { -moz-transform: rotate(-10deg); }
	60% { -moz-transform: rotate(5deg); }	
	80% { -moz-transform: rotate(-5deg); }	
	100% { -moz-transform: rotate(0deg); }
}

@-o-keyframes swing {
	20% { -o-transform: rotate(15deg); }	
	40% { -o-transform: rotate(-10deg); }
	60% { -o-transform: rotate(5deg); }	
	80% { -o-transform: rotate(-5deg); }	
	100% { -o-transform: rotate(0deg); }
}

@keyframes swing {
	20% { transform: rotate(15deg); }	
	40% { transform: rotate(-10deg); }
	60% { transform: rotate(5deg); }	
	80% { transform: rotate(-5deg); }	
	100% { transform: rotate(0deg); }
}

.swing {
	-webkit-transform-origin: top center;
	-moz-transform-origin: top center;
	-o-transform-origin: top center;
	transform-origin: top center;
	-webkit-animation-name: swing;
	-moz-animation-name: swing;
	-o-animation-name: swing;
	animation-name: swing;
}
/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes wobble {
  0% { -webkit-transform: translateX(0%); }
  15% { -webkit-transform: translateX(-25%) rotate(-5deg); }
  30% { -webkit-transform: translateX(20%) rotate(3deg); }
  45% { -webkit-transform: translateX(-15%) rotate(-3deg); }
  60% { -webkit-transform: translateX(10%) rotate(2deg); }
  75% { -webkit-transform: translateX(-5%) rotate(-1deg); }
  100% { -webkit-transform: translateX(0%); }
}

@-moz-keyframes wobble {
  0% { -moz-transform: translateX(0%); }
  15% { -moz-transform: translateX(-25%) rotate(-5deg); }
  30% { -moz-transform: translateX(20%) rotate(3deg); }
  45% { -moz-transform: translateX(-15%) rotate(-3deg); }
  60% { -moz-transform: translateX(10%) rotate(2deg); }
  75% { -moz-transform: translateX(-5%) rotate(-1deg); }
  100% { -moz-transform: translateX(0%); }
}

@-o-keyframes wobble {
  0% { -o-transform: translateX(0%); }
  15% { -o-transform: translateX(-25%) rotate(-5deg); }
  30% { -o-transform: translateX(20%) rotate(3deg); }
  45% { -o-transform: translateX(-15%) rotate(-3deg); }
  60% { -o-transform: translateX(10%) rotate(2deg); }
  75% { -o-transform: translateX(-5%) rotate(-1deg); }
  100% { -o-transform: translateX(0%); }
}

@keyframes wobble {
  0% { transform: translateX(0%); }
  15% { transform: translateX(-25%) rotate(-5deg); }
  30% { transform: translateX(20%) rotate(3deg); }
  45% { transform: translateX(-15%) rotate(-3deg); }
  60% { transform: translateX(10%) rotate(2deg); }
  75% { transform: translateX(-5%) rotate(-1deg); }
  100% { transform: translateX(0%); }
}

.wobble {
	-webkit-animation-name: wobble;
	-moz-animation-name: wobble;
	-o-animation-name: wobble;
	animation-name: wobble;
}
/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes pulse {
    0% { -webkit-transform: scale(1); }	
	50% { -webkit-transform: scale(1.1); }
    100% { -webkit-transform: scale(1); }
}
@-moz-keyframes pulse {
    0% { -moz-transform: scale(1); }	
	50% { -moz-transform: scale(1.1); }
    100% { -moz-transform: scale(1); }
}
@-o-keyframes pulse {
    0% { -o-transform: scale(1); }	
	50% { -o-transform: scale(1.1); }
    100% { -o-transform: scale(1); }
}
@keyframes pulse {
    0% { transform: scale(1); }	
	50% { transform: scale(1.1); }
    100% { transform: scale(1); }
}

.pulse {
	-webkit-animation-name: pulse;
	-moz-animation-name: pulse;
	-o-animation-name: pulse;
	animation-name: pulse;
}
@-webkit-keyframes flip {
	0% {
		-webkit-transform: perspective(400px) rotateY(0);
		-webkit-animation-timing-function: ease-out;
	}
	40% {
		-webkit-transform: perspective(400px) translateZ(150px) rotateY(170deg);
		-webkit-animation-timing-function: ease-out;
	}
	50% {
		-webkit-transform: perspective(400px) translateZ(150px) rotateY(190deg) scale(1);
		-webkit-animation-timing-function: ease-in;
	}
	80% {
		-webkit-transform: perspective(400px) rotateY(360deg) scale(.95);
		-webkit-animation-timing-function: ease-in;
	}
	100% {
		-webkit-transform: perspective(400px) scale(1);
		-webkit-animation-timing-function: ease-in;
	}
}
@-moz-keyframes flip {
	0% {
		-moz-transform: perspective(400px) rotateY(0);
		-moz-animation-timing-function: ease-out;
	}
	40% {
		-moz-transform: perspective(400px) translateZ(150px) rotateY(170deg);
		-moz-animation-timing-function: ease-out;
	}
	50% {
		-moz-transform: perspective(400px) translateZ(150px) rotateY(190deg) scale(1);
		-moz-animation-timing-function: ease-in;
	}
	80% {
		-moz-transform: perspective(400px) rotateY(360deg) scale(.95);
		-moz-animation-timing-function: ease-in;
	}
	100% {
		-moz-transform: perspective(400px) scale(1);
		-moz-animation-timing-function: ease-in;
	}
}
@-o-keyframes flip {
	0% {
		-o-transform: perspective(400px) rotateY(0);
		-o-animation-timing-function: ease-out;
	}
	40% {
		-o-transform: perspective(400px) translateZ(150px) rotateY(170deg);
		-o-animation-timing-function: ease-out;
	}
	50% {
		-o-transform: perspective(400px) translateZ(150px) rotateY(190deg) scale(1);
		-o-animation-timing-function: ease-in;
	}
	80% {
		-o-transform: perspective(400px) rotateY(360deg) scale(.95);
		-o-animation-timing-function: ease-in;
	}
	100% {
		-o-transform: perspective(400px) scale(1);
		-o-animation-timing-function: ease-in;
	}
}
@keyframes flip {
	0% {
		transform: perspective(400px) rotateY(0);
		animation-timing-function: ease-out;
	}
	40% {
		transform: perspective(400px) translateZ(150px) rotateY(170deg);
		animation-timing-function: ease-out;
	}
	50% {
		transform: perspective(400px) translateZ(150px) rotateY(190deg) scale(1);
		animation-timing-function: ease-in;
	}
	80% {
		transform: perspective(400px) rotateY(360deg) scale(.95);
		animation-timing-function: ease-in;
	}
	100% {
		transform: perspective(400px) scale(1);
		animation-timing-function: ease-in;
	}
}

.flip {
	-webkit-backface-visibility: visible !important;
	-webkit-animation-name: flip;
	-moz-backface-visibility: visible !important;
	-moz-animation-name: flip;
	-o-backface-visibility: visible !important;
	-o-animation-name: flip;
	backface-visibility: visible !important;
	animation-name: flip;
}
@-webkit-keyframes flipInX {
    0% {
        -webkit-transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }
    
    40% {
        -webkit-transform: perspective(400px) rotateX(-10deg);
    }
    
    70% {
        -webkit-transform: perspective(400px) rotateX(10deg);
    }
    
    100% {
        -webkit-transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }
}
@-moz-keyframes flipInX {
    0% {
        -moz-transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }
    
    40% {
        -moz-transform: perspective(400px) rotateX(-10deg);
    }
    
    70% {
        -moz-transform: perspective(400px) rotateX(10deg);
    }
    
    100% {
        -moz-transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }
}
@-o-keyframes flipInX {
    0% {
        -o-transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }
    
    40% {
        -o-transform: perspective(400px) rotateX(-10deg);
    }
    
    70% {
        -o-transform: perspective(400px) rotateX(10deg);
    }
    
    100% {
        -o-transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }
}
@keyframes flipInX {
    0% {
        transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }
    
    40% {
        transform: perspective(400px) rotateX(-10deg);
    }
    
    70% {
        transform: perspective(400px) rotateX(10deg);
    }
    
    100% {
        transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }
}

.flipInX {
	-webkit-backface-visibility: visible !important;
	-webkit-animation-name: flipInX;
	-moz-backface-visibility: visible !important;
	-moz-animation-name: flipInX;
	-o-backface-visibility: visible !important;
	-o-animation-name: flipInX;
	backface-visibility: visible !important;
	animation-name: flipInX;
}
@-webkit-keyframes flipOutX {
    0% {
        -webkit-transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }
	100% {
        -webkit-transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }
}

@-moz-keyframes flipOutX {
    0% {
        -moz-transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }
	100% {
        -moz-transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }
}

@-o-keyframes flipOutX {
    0% {
        -o-transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }
	100% {
        -o-transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }
}

@keyframes flipOutX {
    0% {
        transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }
	100% {
        transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }
}

.flipOutX {
	-webkit-animation-name: flipOutX;
	-webkit-backface-visibility: visible !important;
	-moz-animation-name: flipOutX;
	-moz-backface-visibility: visible !important;
	-o-animation-name: flipOutX;
	-o-backface-visibility: visible !important;
	animation-name: flipOutX;
	backface-visibility: visible !important;
}
@-webkit-keyframes flipInY {
    0% {
        -webkit-transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }
    
    40% {
        -webkit-transform: perspective(400px) rotateY(-10deg);
    }
    
    70% {
        -webkit-transform: perspective(400px) rotateY(10deg);
    }
    
    100% {
        -webkit-transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }
}
@-moz-keyframes flipInY {
    0% {
        -moz-transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }
    
    40% {
        -moz-transform: perspective(400px) rotateY(-10deg);
    }
    
    70% {
        -moz-transform: perspective(400px) rotateY(10deg);
    }
    
    100% {
        -moz-transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }
}
@-o-keyframes flipInY {
    0% {
        -o-transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }
    
    40% {
        -o-transform: perspective(400px) rotateY(-10deg);
    }
    
    70% {
        -o-transform: perspective(400px) rotateY(10deg);
    }
    
    100% {
        -o-transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }
}
@keyframes flipInY {
    0% {
        transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }
    
    40% {
        transform: perspective(400px) rotateY(-10deg);
    }
    
    70% {
        transform: perspective(400px) rotateY(10deg);
    }
    
    100% {
        transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }
}

.flipInY {
	-webkit-backface-visibility: visible !important;
	-webkit-animation-name: flipInY;
	-moz-backface-visibility: visible !important;
	-moz-animation-name: flipInY;
	-o-backface-visibility: visible !important;
	-o-animation-name: flipInY;
	backface-visibility: visible !important;
	animation-name: flipInY;
}
@-webkit-keyframes flipOutY {
    0% {
        -webkit-transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }
	100% {
        -webkit-transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }
}
@-moz-keyframes flipOutY {
    0% {
        -moz-transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }
	100% {
        -moz-transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }
}
@-o-keyframes flipOutY {
    0% {
        -o-transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }
	100% {
        -o-transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }
}
@keyframes flipOutY {
    0% {
        transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }
	100% {
        transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }
}

.flipOutY {
	-webkit-backface-visibility: visible !important;
	-webkit-animation-name: flipOutY;
	-moz-backface-visibility: visible !important;
	-moz-animation-name: flipOutY;
	-o-backface-visibility: visible !important;
	-o-animation-name: flipOutY;
	backface-visibility: visible !important;
	animation-name: flipOutY;
}
@-webkit-keyframes fadeIn {
	0% {opacity: 0;}	
	100% {opacity: 1;}
}

@-moz-keyframes fadeIn {
	0% {opacity: 0;}	
	100% {opacity: 1;}
}

@-o-keyframes fadeIn {
	0% {opacity: 0;}	
	100% {opacity: 1;}
}

@keyframes fadeIn {
	0% {opacity: 0;}	
	100% {opacity: 1;}
}

.fadeIn {
	-webkit-animation-name: fadeIn;
	-moz-animation-name: fadeIn;
	-o-animation-name: fadeIn;
	animation-name: fadeIn;
}
@-webkit-keyframes fadeInUp {
	0% {
		opacity: 0;
		-webkit-transform: translateY(20px);
	}
	
	100% {
		opacity: 1;
		-webkit-transform: translateY(0);
	}
}

@-moz-keyframes fadeInUp {
	0% {
		opacity: 0;
		-moz-transform: translateY(20px);
	}
	
	100% {
		opacity: 1;
		-moz-transform: translateY(0);
	}
}

@-o-keyframes fadeInUp {
	0% {
		opacity: 0;
		-o-transform: translateY(20px);
	}
	
	100% {
		opacity: 1;
		-o-transform: translateY(0);
	}
}

@keyframes fadeInUp {
	0% {
		opacity: 0;
		transform: translateY(20px);
	}
	
	100% {
		opacity: 1;
		transform: translateY(0);
	}
}

.fadeInUp {
	-webkit-animation-name: fadeInUp;
	-moz-animation-name: fadeInUp;
	-o-animation-name: fadeInUp;
	animation-name: fadeInUp;
}
@-webkit-keyframes fadeInDown {
	0% {
		opacity: 0;
		-webkit-transform: translateY(-20px);
	}
	
	100% {
		opacity: 1;
		-webkit-transform: translateY(0);
	}
}

@-moz-keyframes fadeInDown {
	0% {
		opacity: 0;
		-moz-transform: translateY(-20px);
	}
	
	100% {
		opacity: 1;
		-moz-transform: translateY(0);
	}
}

@-o-keyframes fadeInDown {
	0% {
		opacity: 0;
		-o-transform: translateY(-20px);
	}
	
	100% {
		opacity: 1;
		-o-transform: translateY(0);
	}
}

@keyframes fadeInDown {
	0% {
		opacity: 0;
		transform: translateY(-20px);
	}
	
	100% {
		opacity: 1;
		transform: translateY(0);
	}
}

.fadeInDown {
	-webkit-animation-name: fadeInDown;
	-moz-animation-name: fadeInDown;
	-o-animation-name: fadeInDown;
	animation-name: fadeInDown;
}
@-webkit-keyframes fadeInLeft {
	0% {
		opacity: 0;
		-webkit-transform: translateX(-20px);
	}
	
	100% {
		opacity: 1;
		-webkit-transform: translateX(0);
	}
}

@-moz-keyframes fadeInLeft {
	0% {
		opacity: 0;
		-moz-transform: translateX(-20px);
	}
	
	100% {
		opacity: 1;
		-moz-transform: translateX(0);
	}
}

@-o-keyframes fadeInLeft {
	0% {
		opacity: 0;
		-o-transform: translateX(-20px);
	}
	
	100% {
		opacity: 1;
		-o-transform: translateX(0);
	}
}

@keyframes fadeInLeft {
	0% {
		opacity: 0;
		transform: translateX(-20px);
	}
	
	100% {
		opacity: 1;
		transform: translateX(0);
	}
}

.fadeInLeft {
	-webkit-animation-name: fadeInLeft;
	-moz-animation-name: fadeInLeft;
	-o-animation-name: fadeInLeft;
	animation-name: fadeInLeft;
}
@-webkit-keyframes fadeInRight {
	0% {
		opacity: 0;
		-webkit-transform: translateX(20px);
	}
	
	100% {
		opacity: 1;
		-webkit-transform: translateX(0);
	}
}

@-moz-keyframes fadeInRight {
	0% {
		opacity: 0;
		-moz-transform: translateX(20px);
	}
	
	100% {
		opacity: 1;
		-moz-transform: translateX(0);
	}
}

@-o-keyframes fadeInRight {
	0% {
		opacity: 0;
		-o-transform: translateX(20px);
	}
	
	100% {
		opacity: 1;
		-o-transform: translateX(0);
	}
}

@keyframes fadeInRight {
	0% {
		opacity: 0;
		transform: translateX(20px);
	}
	
	100% {
		opacity: 1;
		transform: translateX(0);
	}
}

.fadeInRight {
	-webkit-animation-name: fadeInRight;
	-moz-animation-name: fadeInRight;
	-o-animation-name: fadeInRight;
	animation-name: fadeInRight;
}
@-webkit-keyframes fadeInUpBig {
	0% {
		opacity: 0;
		-webkit-transform: translateY(2000px);
	}
	
	100% {
		opacity: 1;
		-webkit-transform: translateY(0);
	}
}

@-moz-keyframes fadeInUpBig {
	0% {
		opacity: 0;
		-moz-transform: translateY(2000px);
	}
	
	100% {
		opacity: 1;
		-moz-transform: translateY(0);
	}
}

@-o-keyframes fadeInUpBig {
	0% {
		opacity: 0;
		-o-transform: translateY(2000px);
	}
	
	100% {
		opacity: 1;
		-o-transform: translateY(0);
	}
}

@keyframes fadeInUpBig {
	0% {
		opacity: 0;
		transform: translateY(2000px);
	}
	
	100% {
		opacity: 1;
		transform: translateY(0);
	}
}

.fadeInUpBig {
	-webkit-animation-name: fadeInUpBig;
	-moz-animation-name: fadeInUpBig;
	-o-animation-name: fadeInUpBig;
	animation-name: fadeInUpBig;
}
@-webkit-keyframes fadeInDownBig {
	0% {
		opacity: 0;
		-webkit-transform: translateY(-2000px);
	}
	
	100% {
		opacity: 1;
		-webkit-transform: translateY(0);
	}
}

@-moz-keyframes fadeInDownBig {
	0% {
		opacity: 0;
		-moz-transform: translateY(-2000px);
	}
	
	100% {
		opacity: 1;
		-moz-transform: translateY(0);
	}
}

@-o-keyframes fadeInDownBig {
	0% {
		opacity: 0;
		-o-transform: translateY(-2000px);
	}
	
	100% {
		opacity: 1;
		-o-transform: translateY(0);
	}
}

@keyframes fadeInDownBig {
	0% {
		opacity: 0;
		transform: translateY(-2000px);
	}
	
	100% {
		opacity: 1;
		transform: translateY(0);
	}
}

.fadeInDownBig {
	-webkit-animation-name: fadeInDownBig;
	-moz-animation-name: fadeInDownBig;
	-o-animation-name: fadeInDownBig;
	animation-name: fadeInDownBig;
}
@-webkit-keyframes fadeInLeftBig {
	0% {
		opacity: 0;
		-webkit-transform: translateX(-2000px);
	}
	
	100% {
		opacity: 1;
		-webkit-transform: translateX(0);
	}
}
@-moz-keyframes fadeInLeftBig {
	0% {
		opacity: 0;
		-moz-transform: translateX(-2000px);
	}
	
	100% {
		opacity: 1;
		-moz-transform: translateX(0);
	}
}
@-o-keyframes fadeInLeftBig {
	0% {
		opacity: 0;
		-o-transform: translateX(-2000px);
	}
	
	100% {
		opacity: 1;
		-o-transform: translateX(0);
	}
}
@keyframes fadeInLeftBig {
	0% {
		opacity: 0;
		transform: translateX(-2000px);
	}
	
	100% {
		opacity: 1;
		transform: translateX(0);
	}
}

.fadeInLeftBig {
	-webkit-animation-name: fadeInLeftBig;
	-moz-animation-name: fadeInLeftBig;
	-o-animation-name: fadeInLeftBig;
	animation-name: fadeInLeftBig;
}
@-webkit-keyframes fadeInRightBig {
	0% {
		opacity: 0;
		-webkit-transform: translateX(2000px);
	}
	
	100% {
		opacity: 1;
		-webkit-transform: translateX(0);
	}
}

@-moz-keyframes fadeInRightBig {
	0% {
		opacity: 0;
		-moz-transform: translateX(2000px);
	}
	
	100% {
		opacity: 1;
		-moz-transform: translateX(0);
	}
}

@-o-keyframes fadeInRightBig {
	0% {
		opacity: 0;
		-o-transform: translateX(2000px);
	}
	
	100% {
		opacity: 1;
		-o-transform: translateX(0);
	}
}

@keyframes fadeInRightBig {
	0% {
		opacity: 0;
		transform: translateX(2000px);
	}
	
	100% {
		opacity: 1;
		transform: translateX(0);
	}
}

.fadeInRightBig {
	-webkit-animation-name: fadeInRightBig;
	-moz-animation-name: fadeInRightBig;
	-o-animation-name: fadeInRightBig;
	animation-name: fadeInRightBig;
}
@-webkit-keyframes fadeOut {
	0% {opacity: 1;}
	100% {opacity: 0;}
}

@-moz-keyframes fadeOut {
	0% {opacity: 1;}
	100% {opacity: 0;}
}

@-o-keyframes fadeOut {
	0% {opacity: 1;}
	100% {opacity: 0;}
}

@keyframes fadeOut {
	0% {opacity: 1;}
	100% {opacity: 0;}
}

.fadeOut {
	-webkit-animation-name: fadeOut;
	-moz-animation-name: fadeOut;
	-o-animation-name: fadeOut;
	animation-name: fadeOut;
}
@-webkit-keyframes fadeOutUp {
	0% {
		opacity: 1;
		-webkit-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateY(-20px);
	}
}
@-moz-keyframes fadeOutUp {
	0% {
		opacity: 1;
		-moz-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateY(-20px);
	}
}
@-o-keyframes fadeOutUp {
	0% {
		opacity: 1;
		-o-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateY(-20px);
	}
}
@keyframes fadeOutUp {
	0% {
		opacity: 1;
		transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		transform: translateY(-20px);
	}
}

.fadeOutUp {
	-webkit-animation-name: fadeOutUp;
	-moz-animation-name: fadeOutUp;
	-o-animation-name: fadeOutUp;
	animation-name: fadeOutUp;
}
@-webkit-keyframes fadeOutDown {
	0% {
		opacity: 1;
		-webkit-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateY(20px);
	}
}

@-moz-keyframes fadeOutDown {
	0% {
		opacity: 1;
		-moz-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateY(20px);
	}
}

@-o-keyframes fadeOutDown {
	0% {
		opacity: 1;
		-o-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateY(20px);
	}
}

@keyframes fadeOutDown {
	0% {
		opacity: 1;
		transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		transform: translateY(20px);
	}
}

.fadeOutDown {
	-webkit-animation-name: fadeOutDown;
	-moz-animation-name: fadeOutDown;
	-o-animation-name: fadeOutDown;
	animation-name: fadeOutDown;
}
@-webkit-keyframes fadeOutLeft {
	0% {
		opacity: 1;
		-webkit-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateX(-20px);
	}
}

@-moz-keyframes fadeOutLeft {
	0% {
		opacity: 1;
		-moz-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateX(-20px);
	}
}

@-o-keyframes fadeOutLeft {
	0% {
		opacity: 1;
		-o-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateX(-20px);
	}
}

@keyframes fadeOutLeft {
	0% {
		opacity: 1;
		transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		transform: translateX(-20px);
	}
}

.fadeOutLeft {
	-webkit-animation-name: fadeOutLeft;
	-moz-animation-name: fadeOutLeft;
	-o-animation-name: fadeOutLeft;
	animation-name: fadeOutLeft;
}
@-webkit-keyframes fadeOutRight {
	0% {
		opacity: 1;
		-webkit-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateX(20px);
	}
}

@-moz-keyframes fadeOutRight {
	0% {
		opacity: 1;
		-moz-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateX(20px);
	}
}

@-o-keyframes fadeOutRight {
	0% {
		opacity: 1;
		-o-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateX(20px);
	}
}

@keyframes fadeOutRight {
	0% {
		opacity: 1;
		transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		transform: translateX(20px);
	}
}

.fadeOutRight {
	-webkit-animation-name: fadeOutRight;
	-moz-animation-name: fadeOutRight;
	-o-animation-name: fadeOutRight;
	animation-name: fadeOutRight;
}
@-webkit-keyframes fadeOutUpBig {
	0% {
		opacity: 1;
		-webkit-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateY(-2000px);
	}
}

@-moz-keyframes fadeOutUpBig {
	0% {
		opacity: 1;
		-moz-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateY(-2000px);
	}
}

@-o-keyframes fadeOutUpBig {
	0% {
		opacity: 1;
		-o-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateY(-2000px);
	}
}

@keyframes fadeOutUpBig {
	0% {
		opacity: 1;
		transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		transform: translateY(-2000px);
	}
}

.fadeOutUpBig {
	-webkit-animation-name: fadeOutUpBig;
	-moz-animation-name: fadeOutUpBig;
	-o-animation-name: fadeOutUpBig;
	animation-name: fadeOutUpBig;
}
@-webkit-keyframes fadeOutDownBig {
	0% {
		opacity: 1;
		-webkit-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateY(2000px);
	}
}

@-moz-keyframes fadeOutDownBig {
	0% {
		opacity: 1;
		-moz-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateY(2000px);
	}
}

@-o-keyframes fadeOutDownBig {
	0% {
		opacity: 1;
		-o-transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateY(2000px);
	}
}

@keyframes fadeOutDownBig {
	0% {
		opacity: 1;
		transform: translateY(0);
	}
	
	100% {
		opacity: 0;
		transform: translateY(2000px);
	}
}

.fadeOutDownBig {
	-webkit-animation-name: fadeOutDownBig;
	-moz-animation-name: fadeOutDownBig;
	-o-animation-name: fadeOutDownBig;
	animation-name: fadeOutDownBig;
}
@-webkit-keyframes fadeOutLeftBig {
	0% {
		opacity: 1;
		-webkit-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateX(-2000px);
	}
}

@-moz-keyframes fadeOutLeftBig {
	0% {
		opacity: 1;
		-moz-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateX(-2000px);
	}
}

@-o-keyframes fadeOutLeftBig {
	0% {
		opacity: 1;
		-o-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateX(-2000px);
	}
}

@keyframes fadeOutLeftBig {
	0% {
		opacity: 1;
		transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		transform: translateX(-2000px);
	}
}

.fadeOutLeftBig {
	-webkit-animation-name: fadeOutLeftBig;
	-moz-animation-name: fadeOutLeftBig;
	-o-animation-name: fadeOutLeftBig;
	animation-name: fadeOutLeftBig;
}
@-webkit-keyframes fadeOutRightBig {
	0% {
		opacity: 1;
		-webkit-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateX(2000px);
	}
}
@-moz-keyframes fadeOutRightBig {
	0% {
		opacity: 1;
		-moz-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateX(2000px);
	}
}
@-o-keyframes fadeOutRightBig {
	0% {
		opacity: 1;
		-o-transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateX(2000px);
	}
}
@keyframes fadeOutRightBig {
	0% {
		opacity: 1;
		transform: translateX(0);
	}
	
	100% {
		opacity: 0;
		transform: translateX(2000px);
	}
}

.fadeOutRightBig {
	-webkit-animation-name: fadeOutRightBig;
	-moz-animation-name: fadeOutRightBig;
	-o-animation-name: fadeOutRightBig;
	animation-name: fadeOutRightBig;
}
@-webkit-keyframes bounceIn {
	0% {
		opacity: 0;
		-webkit-transform: scale(.3);
	}
	
	50% {
		opacity: 1;
		-webkit-transform: scale(1.05);
	}
	
	70% {
		-webkit-transform: scale(.9);
	}
	
	100% {
		-webkit-transform: scale(1);
	}
}

@-moz-keyframes bounceIn {
	0% {
		opacity: 0;
		-moz-transform: scale(.3);
	}
	
	50% {
		opacity: 1;
		-moz-transform: scale(1.05);
	}
	
	70% {
		-moz-transform: scale(.9);
	}
	
	100% {
		-moz-transform: scale(1);
	}
}

@-o-keyframes bounceIn {
	0% {
		opacity: 0;
		-o-transform: scale(.3);
	}
	
	50% {
		opacity: 1;
		-o-transform: scale(1.05);
	}
	
	70% {
		-o-transform: scale(.9);
	}
	
	100% {
		-o-transform: scale(1);
	}
}

@keyframes bounceIn {
	0% {
		opacity: 0;
		transform: scale(.3);
	}
	
	50% {
		opacity: 1;
		transform: scale(1.05);
	}
	
	70% {
		transform: scale(.9);
	}
	
	100% {
		transform: scale(1);
	}
}

.bounceIn {
	-webkit-animation-name: bounceIn;
	-moz-animation-name: bounceIn;
	-o-animation-name: bounceIn;
	animation-name: bounceIn;
}
@-webkit-keyframes bounceInUp {
	0% {
		opacity: 0;
		-webkit-transform: translateY(2000px);
	}
	
	60% {
		opacity: 1;
		-webkit-transform: translateY(-30px);
	}
	
	80% {
		-webkit-transform: translateY(10px);
	}
	
	100% {
		-webkit-transform: translateY(0);
	}
}
@-moz-keyframes bounceInUp {
	0% {
		opacity: 0;
		-moz-transform: translateY(2000px);
	}
	
	60% {
		opacity: 1;
		-moz-transform: translateY(-30px);
	}
	
	80% {
		-moz-transform: translateY(10px);
	}
	
	100% {
		-moz-transform: translateY(0);
	}
}

@-o-keyframes bounceInUp {
	0% {
		opacity: 0;
		-o-transform: translateY(2000px);
	}
	
	60% {
		opacity: 1;
		-o-transform: translateY(-30px);
	}
	
	80% {
		-o-transform: translateY(10px);
	}
	
	100% {
		-o-transform: translateY(0);
	}
}

@keyframes bounceInUp {
	0% {
		opacity: 0;
		transform: translateY(2000px);
	}
	
	60% {
		opacity: 1;
		transform: translateY(-30px);
	}
	
	80% {
		transform: translateY(10px);
	}
	
	100% {
		transform: translateY(0);
	}
}

.bounceInUp {
	-webkit-animation-name: bounceInUp;
	-moz-animation-name: bounceInUp;
	-o-animation-name: bounceInUp;
	animation-name: bounceInUp;
}
@-webkit-keyframes bounceInDown {
	0% {
		opacity: 0;
		-webkit-transform: translateY(-2000px);
	}
	
	60% {
		opacity: 1;
		-webkit-transform: translateY(30px);
	}
	
	80% {
		-webkit-transform: translateY(-10px);
	}
	
	100% {
		-webkit-transform: translateY(0);
	}
}

@-moz-keyframes bounceInDown {
	0% {
		opacity: 0;
		-moz-transform: translateY(-2000px);
	}
	
	60% {
		opacity: 1;
		-moz-transform: translateY(30px);
	}
	
	80% {
		-moz-transform: translateY(-10px);
	}
	
	100% {
		-moz-transform: translateY(0);
	}
}

@-o-keyframes bounceInDown {
	0% {
		opacity: 0;
		-o-transform: translateY(-2000px);
	}
	
	60% {
		opacity: 1;
		-o-transform: translateY(30px);
	}
	
	80% {
		-o-transform: translateY(-10px);
	}
	
	100% {
		-o-transform: translateY(0);
	}
}

@keyframes bounceInDown {
	0% {
		opacity: 0;
		transform: translateY(-2000px);
	}
	
	60% {
		opacity: 1;
		transform: translateY(30px);
	}
	
	80% {
		transform: translateY(-10px);
	}
	
	100% {
		transform: translateY(0);
	}
}

.bounceInDown {
	-webkit-animation-name: bounceInDown;
	-moz-animation-name: bounceInDown;
	-o-animation-name: bounceInDown;
	animation-name: bounceInDown;
}
@-webkit-keyframes bounceInLeft {
	0% {
		opacity: 0;
		-webkit-transform: translateX(-2000px);
	}
	
	60% {
		opacity: 1;
		-webkit-transform: translateX(30px);
	}
	
	80% {
		-webkit-transform: translateX(-10px);
	}
	
	100% {
		-webkit-transform: translateX(0);
	}
}

@-moz-keyframes bounceInLeft {
	0% {
		opacity: 0;
		-moz-transform: translateX(-2000px);
	}
	
	60% {
		opacity: 1;
		-moz-transform: translateX(30px);
	}
	
	80% {
		-moz-transform: translateX(-10px);
	}
	
	100% {
		-moz-transform: translateX(0);
	}
}

@-o-keyframes bounceInLeft {
	0% {
		opacity: 0;
		-o-transform: translateX(-2000px);
	}
	
	60% {
		opacity: 1;
		-o-transform: translateX(30px);
	}
	
	80% {
		-o-transform: translateX(-10px);
	}
	
	100% {
		-o-transform: translateX(0);
	}
}

@keyframes bounceInLeft {
	0% {
		opacity: 0;
		transform: translateX(-2000px);
	}
	
	60% {
		opacity: 1;
		transform: translateX(30px);
	}
	
	80% {
		transform: translateX(-10px);
	}
	
	100% {
		transform: translateX(0);
	}
}

.bounceInLeft {
	-webkit-animation-name: bounceInLeft;
	-moz-animation-name: bounceInLeft;
	-o-animation-name: bounceInLeft;
	animation-name: bounceInLeft;
}
@-webkit-keyframes bounceInRight {
	0% {
		opacity: 0;
		-webkit-transform: translateX(2000px);
	}
	
	60% {
		opacity: 1;
		-webkit-transform: translateX(-30px);
	}
	
	80% {
		-webkit-transform: translateX(10px);
	}
	
	100% {
		-webkit-transform: translateX(0);
	}
}

@-moz-keyframes bounceInRight {
	0% {
		opacity: 0;
		-moz-transform: translateX(2000px);
	}
	
	60% {
		opacity: 1;
		-moz-transform: translateX(-30px);
	}
	
	80% {
		-moz-transform: translateX(10px);
	}
	
	100% {
		-moz-transform: translateX(0);
	}
}

@-o-keyframes bounceInRight {
	0% {
		opacity: 0;
		-o-transform: translateX(2000px);
	}
	
	60% {
		opacity: 1;
		-o-transform: translateX(-30px);
	}
	
	80% {
		-o-transform: translateX(10px);
	}
	
	100% {
		-o-transform: translateX(0);
	}
}

@keyframes bounceInRight {
	0% {
		opacity: 0;
		transform: translateX(2000px);
	}
	
	60% {
		opacity: 1;
		transform: translateX(-30px);
	}
	
	80% {
		transform: translateX(10px);
	}
	
	100% {
		transform: translateX(0);
	}
}

.bounceInRight {
	-webkit-animation-name: bounceInRight;
	-moz-animation-name: bounceInRight;
	-o-animation-name: bounceInRight;
	animation-name: bounceInRight;
}
@-webkit-keyframes bounceOut {
	0% {
		-webkit-transform: scale(1);
	}
	
	25% {
		-webkit-transform: scale(.95);
	}
	
	50% {
		opacity: 1;
		-webkit-transform: scale(1.1);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: scale(.3);
	}	
}

@-moz-keyframes bounceOut {
	0% {
		-moz-transform: scale(1);
	}
	
	25% {
		-moz-transform: scale(.95);
	}
	
	50% {
		opacity: 1;
		-moz-transform: scale(1.1);
	}
	
	100% {
		opacity: 0;
		-moz-transform: scale(.3);
	}	
}

@-o-keyframes bounceOut {
	0% {
		-o-transform: scale(1);
	}
	
	25% {
		-o-transform: scale(.95);
	}
	
	50% {
		opacity: 1;
		-o-transform: scale(1.1);
	}
	
	100% {
		opacity: 0;
		-o-transform: scale(.3);
	}	
}

@keyframes bounceOut {
	0% {
		transform: scale(1);
	}
	
	25% {
		transform: scale(.95);
	}
	
	50% {
		opacity: 1;
		transform: scale(1.1);
	}
	
	100% {
		opacity: 0;
		transform: scale(.3);
	}	
}

.bounceOut {
	-webkit-animation-name: bounceOut;
	-moz-animation-name: bounceOut;
	-o-animation-name: bounceOut;
	animation-name: bounceOut;
}
@-webkit-keyframes bounceOutUp {
	0% {
		-webkit-transform: translateY(0);
	}
	
	20% {
		opacity: 1;
		-webkit-transform: translateY(20px);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateY(-2000px);
	}
}

@-moz-keyframes bounceOutUp {
	0% {
		-moz-transform: translateY(0);
	}
	
	20% {
		opacity: 1;
		-moz-transform: translateY(20px);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateY(-2000px);
	}
}

@-o-keyframes bounceOutUp {
	0% {
		-o-transform: translateY(0);
	}
	
	20% {
		opacity: 1;
		-o-transform: translateY(20px);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateY(-2000px);
	}
}

@keyframes bounceOutUp {
	0% {
		transform: translateY(0);
	}
	
	20% {
		opacity: 1;
		transform: translateY(20px);
	}
	
	100% {
		opacity: 0;
		transform: translateY(-2000px);
	}
}

.bounceOutUp {
	-webkit-animation-name: bounceOutUp;
	-moz-animation-name: bounceOutUp;
	-o-animation-name: bounceOutUp;
	animation-name: bounceOutUp;
}
@-webkit-keyframes bounceOutDown {
	0% {
		-webkit-transform: translateY(0);
	}
	
	20% {
		opacity: 1;
		-webkit-transform: translateY(-20px);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateY(2000px);
	}
}

@-moz-keyframes bounceOutDown {
	0% {
		-moz-transform: translateY(0);
	}
	
	20% {
		opacity: 1;
		-moz-transform: translateY(-20px);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateY(2000px);
	}
}

@-o-keyframes bounceOutDown {
	0% {
		-o-transform: translateY(0);
	}
	
	20% {
		opacity: 1;
		-o-transform: translateY(-20px);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateY(2000px);
	}
}

@keyframes bounceOutDown {
	0% {
		transform: translateY(0);
	}
	
	20% {
		opacity: 1;
		transform: translateY(-20px);
	}
	
	100% {
		opacity: 0;
		transform: translateY(2000px);
	}
}

.bounceOutDown {
	-webkit-animation-name: bounceOutDown;
	-moz-animation-name: bounceOutDown;
	-o-animation-name: bounceOutDown;
	animation-name: bounceOutDown;
}
@-webkit-keyframes bounceOutLeft {
	0% {
		-webkit-transform: translateX(0);
	}
	
	20% {
		opacity: 1;
		-webkit-transform: translateX(20px);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateX(-2000px);
	}
}

@-moz-keyframes bounceOutLeft {
	0% {
		-moz-transform: translateX(0);
	}
	
	20% {
		opacity: 1;
		-moz-transform: translateX(20px);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateX(-2000px);
	}
}

@-o-keyframes bounceOutLeft {
	0% {
		-o-transform: translateX(0);
	}
	
	20% {
		opacity: 1;
		-o-transform: translateX(20px);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateX(-2000px);
	}
}

@keyframes bounceOutLeft {
	0% {
		transform: translateX(0);
	}
	
	20% {
		opacity: 1;
		transform: translateX(20px);
	}
	
	100% {
		opacity: 0;
		transform: translateX(-2000px);
	}
}

.bounceOutLeft {
	-webkit-animation-name: bounceOutLeft;
	-moz-animation-name: bounceOutLeft;
	-o-animation-name: bounceOutLeft;
	animation-name: bounceOutLeft;
}
@-webkit-keyframes bounceOutRight {
	0% {
		-webkit-transform: translateX(0);
	}
	
	20% {
		opacity: 1;
		-webkit-transform: translateX(-20px);
	}
	
	100% {
		opacity: 0;
		-webkit-transform: translateX(2000px);
	}
}

@-moz-keyframes bounceOutRight {
	0% {
		-moz-transform: translateX(0);
	}
	
	20% {
		opacity: 1;
		-moz-transform: translateX(-20px);
	}
	
	100% {
		opacity: 0;
		-moz-transform: translateX(2000px);
	}
}

@-o-keyframes bounceOutRight {
	0% {
		-o-transform: translateX(0);
	}
	
	20% {
		opacity: 1;
		-o-transform: translateX(-20px);
	}
	
	100% {
		opacity: 0;
		-o-transform: translateX(2000px);
	}
}

@keyframes bounceOutRight {
	0% {
		transform: translateX(0);
	}
	
	20% {
		opacity: 1;
		transform: translateX(-20px);
	}
	
	100% {
		opacity: 0;
		transform: translateX(2000px);
	}
}

.bounceOutRight {
	-webkit-animation-name: bounceOutRight;
	-moz-animation-name: bounceOutRight;
	-o-animation-name: bounceOutRight;
	animation-name: bounceOutRight;
}
@-webkit-keyframes rotateIn {
	0% {
		-webkit-transform-origin: center center;
		-webkit-transform: rotate(-200deg);
		opacity: 0;
	}
	
	100% {
		-webkit-transform-origin: center center;
		-webkit-transform: rotate(0);
		opacity: 1;
	}
}
@-moz-keyframes rotateIn {
	0% {
		-moz-transform-origin: center center;
		-moz-transform: rotate(-200deg);
		opacity: 0;
	}
	
	100% {
		-moz-transform-origin: center center;
		-moz-transform: rotate(0);
		opacity: 1;
	}
}
@-o-keyframes rotateIn {
	0% {
		-o-transform-origin: center center;
		-o-transform: rotate(-200deg);
		opacity: 0;
	}
	
	100% {
		-o-transform-origin: center center;
		-o-transform: rotate(0);
		opacity: 1;
	}
}
@keyframes rotateIn {
	0% {
		transform-origin: center center;
		transform: rotate(-200deg);
		opacity: 0;
	}
	
	100% {
		transform-origin: center center;
		transform: rotate(0);
		opacity: 1;
	}
}

.rotateIn {
	-webkit-animation-name: rotateIn;
	-moz-animation-name: rotateIn;
	-o-animation-name: rotateIn;
	animation-name: rotateIn;
}
@-webkit-keyframes rotateInUpLeft {
	0% {
		-webkit-transform-origin: left bottom;
		-webkit-transform: rotate(90deg);
		opacity: 0;
	}
	
	100% {
		-webkit-transform-origin: left bottom;
		-webkit-transform: rotate(0);
		opacity: 1;
	}
}

@-moz-keyframes rotateInUpLeft {
	0% {
		-moz-transform-origin: left bottom;
		-moz-transform: rotate(90deg);
		opacity: 0;
	}
	
	100% {
		-moz-transform-origin: left bottom;
		-moz-transform: rotate(0);
		opacity: 1;
	}
}

@-o-keyframes rotateInUpLeft {
	0% {
		-o-transform-origin: left bottom;
		-o-transform: rotate(90deg);
		opacity: 0;
	}
	
	100% {
		-o-transform-origin: left bottom;
		-o-transform: rotate(0);
		opacity: 1;
	}
}

@keyframes rotateInUpLeft {
	0% {
		transform-origin: left bottom;
		transform: rotate(90deg);
		opacity: 0;
	}
	
	100% {
		transform-origin: left bottom;
		transform: rotate(0);
		opacity: 1;
	}
}

.rotateInUpLeft {
	-webkit-animation-name: rotateInUpLeft;
	-moz-animation-name: rotateInUpLeft;
	-o-animation-name: rotateInUpLeft;
	animation-name: rotateInUpLeft;
}
@-webkit-keyframes rotateInDownLeft {
	0% {
		-webkit-transform-origin: left bottom;
		-webkit-transform: rotate(-90deg);
		opacity: 0;
	}
	
	100% {
		-webkit-transform-origin: left bottom;
		-webkit-transform: rotate(0);
		opacity: 1;
	}
}

@-moz-keyframes rotateInDownLeft {
	0% {
		-moz-transform-origin: left bottom;
		-moz-transform: rotate(-90deg);
		opacity: 0;
	}
	
	100% {
		-moz-transform-origin: left bottom;
		-moz-transform: rotate(0);
		opacity: 1;
	}
}

@-o-keyframes rotateInDownLeft {
	0% {
		-o-transform-origin: left bottom;
		-o-transform: rotate(-90deg);
		opacity: 0;
	}
	
	100% {
		-o-transform-origin: left bottom;
		-o-transform: rotate(0);
		opacity: 1;
	}
}

@keyframes rotateInDownLeft {
	0% {
		transform-origin: left bottom;
		transform: rotate(-90deg);
		opacity: 0;
	}
	
	100% {
		transform-origin: left bottom;
		transform: rotate(0);
		opacity: 1;
	}
}

.rotateInDownLeft {
	-webkit-animation-name: rotateInDownLeft;
	-moz-animation-name: rotateInDownLeft;
	-o-animation-name: rotateInDownLeft;
	animation-name: rotateInDownLeft;
}
@-webkit-keyframes rotateInUpRight {
	0% {
		-webkit-transform-origin: right bottom;
		-webkit-transform: rotate(-90deg);
		opacity: 0;
	}
	
	100% {
		-webkit-transform-origin: right bottom;
		-webkit-transform: rotate(0);
		opacity: 1;
	}
}

@-moz-keyframes rotateInUpRight {
	0% {
		-moz-transform-origin: right bottom;
		-moz-transform: rotate(-90deg);
		opacity: 0;
	}
	
	100% {
		-moz-transform-origin: right bottom;
		-moz-transform: rotate(0);
		opacity: 1;
	}
}

@-o-keyframes rotateInUpRight {
	0% {
		-o-transform-origin: right bottom;
		-o-transform: rotate(-90deg);
		opacity: 0;
	}
	
	100% {
		-o-transform-origin: right bottom;
		-o-transform: rotate(0);
		opacity: 1;
	}
}

@keyframes rotateInUpRight {
	0% {
		transform-origin: right bottom;
		transform: rotate(-90deg);
		opacity: 0;
	}
	
	100% {
		transform-origin: right bottom;
		transform: rotate(0);
		opacity: 1;
	}
}

.rotateInUpRight {
	-webkit-animation-name: rotateInUpRight;
	-moz-animation-name: rotateInUpRight;
	-o-animation-name: rotateInUpRight;
	animation-name: rotateInUpRight;
}
@-webkit-keyframes rotateInDownRight {
	0% {
		-webkit-transform-origin: right bottom;
		-webkit-transform: rotate(90deg);
		opacity: 0;
	}
	
	100% {
		-webkit-transform-origin: right bottom;
		-webkit-transform: rotate(0);
		opacity: 1;
	}
}

@-moz-keyframes rotateInDownRight {
	0% {
		-moz-transform-origin: right bottom;
		-moz-transform: rotate(90deg);
		opacity: 0;
	}
	
	100% {
		-moz-transform-origin: right bottom;
		-moz-transform: rotate(0);
		opacity: 1;
	}
}

@-o-keyframes rotateInDownRight {
	0% {
		-o-transform-origin: right bottom;
		-o-transform: rotate(90deg);
		opacity: 0;
	}
	
	100% {
		-o-transform-origin: right bottom;
		-o-transform: rotate(0);
		opacity: 1;
	}
}

@keyframes rotateInDownRight {
	0% {
		transform-origin: right bottom;
		transform: rotate(90deg);
		opacity: 0;
	}
	
	100% {
		transform-origin: right bottom;
		transform: rotate(0);
		opacity: 1;
	}
}

.rotateInDownRight {
	-webkit-animation-name: rotateInDownRight;
	-moz-animation-name: rotateInDownRight;
	-o-animation-name: rotateInDownRight;
	animation-name: rotateInDownRight;
}
@-webkit-keyframes rotateOut {
	0% {
		-webkit-transform-origin: center center;
		-webkit-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-webkit-transform-origin: center center;
		-webkit-transform: rotate(200deg);
		opacity: 0;
	}
}

@-moz-keyframes rotateOut {
	0% {
		-moz-transform-origin: center center;
		-moz-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-moz-transform-origin: center center;
		-moz-transform: rotate(200deg);
		opacity: 0;
	}
}

@-o-keyframes rotateOut {
	0% {
		-o-transform-origin: center center;
		-o-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-o-transform-origin: center center;
		-o-transform: rotate(200deg);
		opacity: 0;
	}
}

@keyframes rotateOut {
	0% {
		transform-origin: center center;
		transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		transform-origin: center center;
		transform: rotate(200deg);
		opacity: 0;
	}
}

.rotateOut {
	-webkit-animation-name: rotateOut;
	-moz-animation-name: rotateOut;
	-o-animation-name: rotateOut;
	animation-name: rotateOut;
}
@-webkit-keyframes rotateOutUpLeft {
	0% {
		-webkit-transform-origin: left bottom;
		-webkit-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-webkit-transform-origin: left bottom;
		-webkit-transform: rotate(-90deg);
		opacity: 0;
	}
}

@-moz-keyframes rotateOutUpLeft {
	0% {
		-moz-transform-origin: left bottom;
		-moz-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-moz-transform-origin: left bottom;
		-moz-transform: rotate(-90deg);
		opacity: 0;
	}
}

@-o-keyframes rotateOutUpLeft {
	0% {
		-o-transform-origin: left bottom;
		-o-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-o-transform-origin: left bottom;
		-o-transform: rotate(-90deg);
		opacity: 0;
	}
}

@keyframes rotateOutUpLeft {
	0% {
		transform-origin: left bottom;
		transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		transform-origin: left bottom;
		transform: rotate(-90deg);
		opacity: 0;
	}
}

.rotateOutUpLeft {
	-webkit-animation-name: rotateOutUpLeft;
	-moz-animation-name: rotateOutUpLeft;
	-o-animation-name: rotateOutUpLeft;
	animation-name: rotateOutUpLeft;
}
@-webkit-keyframes rotateOutDownLeft {
	0% {
		-webkit-transform-origin: left bottom;
		-webkit-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-webkit-transform-origin: left bottom;
		-webkit-transform: rotate(90deg);
		opacity: 0;
	}
}

@-moz-keyframes rotateOutDownLeft {
	0% {
		-moz-transform-origin: left bottom;
		-moz-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-moz-transform-origin: left bottom;
		-moz-transform: rotate(90deg);
		opacity: 0;
	}
}

@-o-keyframes rotateOutDownLeft {
	0% {
		-o-transform-origin: left bottom;
		-o-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-o-transform-origin: left bottom;
		-o-transform: rotate(90deg);
		opacity: 0;
	}
}

@keyframes rotateOutDownLeft {
	0% {
		transform-origin: left bottom;
		transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		transform-origin: left bottom;
		transform: rotate(90deg);
		opacity: 0;
	}
}

.rotateOutDownLeft {
	-webkit-animation-name: rotateOutDownLeft;
	-moz-animation-name: rotateOutDownLeft;
	-o-animation-name: rotateOutDownLeft;
	animation-name: rotateOutDownLeft;
}
@-webkit-keyframes rotateOutUpRight {
	0% {
		-webkit-transform-origin: right bottom;
		-webkit-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-webkit-transform-origin: right bottom;
		-webkit-transform: rotate(90deg);
		opacity: 0;
	}
}

@-moz-keyframes rotateOutUpRight {
	0% {
		-moz-transform-origin: right bottom;
		-moz-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-moz-transform-origin: right bottom;
		-moz-transform: rotate(90deg);
		opacity: 0;
	}
}

@-o-keyframes rotateOutUpRight {
	0% {
		-o-transform-origin: right bottom;
		-o-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-o-transform-origin: right bottom;
		-o-transform: rotate(90deg);
		opacity: 0;
	}
}

@keyframes rotateOutUpRight {
	0% {
		transform-origin: right bottom;
		transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		transform-origin: right bottom;
		transform: rotate(90deg);
		opacity: 0;
	}
}

.rotateOutUpRight {
	-webkit-animation-name: rotateOutUpRight;
	-moz-animation-name: rotateOutUpRight;
	-o-animation-name: rotateOutUpRight;
	animation-name: rotateOutUpRight;
}
@-webkit-keyframes rotateOutDownRight {
	0% {
		-webkit-transform-origin: right bottom;
		-webkit-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-webkit-transform-origin: right bottom;
		-webkit-transform: rotate(-90deg);
		opacity: 0;
	}
}

@-moz-keyframes rotateOutDownRight {
	0% {
		-moz-transform-origin: right bottom;
		-moz-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-moz-transform-origin: right bottom;
		-moz-transform: rotate(-90deg);
		opacity: 0;
	}
}

@-o-keyframes rotateOutDownRight {
	0% {
		-o-transform-origin: right bottom;
		-o-transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		-o-transform-origin: right bottom;
		-o-transform: rotate(-90deg);
		opacity: 0;
	}
}

@keyframes rotateOutDownRight {
	0% {
		transform-origin: right bottom;
		transform: rotate(0);
		opacity: 1;
	}
	
	100% {
		transform-origin: right bottom;
		transform: rotate(-90deg);
		opacity: 0;
	}
}

.rotateOutDownRight {
	-webkit-animation-name: rotateOutDownRight;
	-moz-animation-name: rotateOutDownRight;
	-o-animation-name: rotateOutDownRight;
	animation-name: rotateOutDownRight;
}
@-webkit-keyframes hinge {
	0% { -webkit-transform: rotate(0); -webkit-transform-origin: top left; -webkit-animation-timing-function: ease-in-out; }	
	20%, 60% { -webkit-transform: rotate(80deg); -webkit-transform-origin: top left; -webkit-animation-timing-function: ease-in-out; }	
	40% { -webkit-transform: rotate(60deg); -webkit-transform-origin: top left; -webkit-animation-timing-function: ease-in-out; }	
	80% { -webkit-transform: rotate(60deg) translateY(0); opacity: 1; -webkit-transform-origin: top left; -webkit-animation-timing-function: ease-in-out; }	
	100% { -webkit-transform: translateY(700px); opacity: 0; }
}

@-moz-keyframes hinge {
	0% { -moz-transform: rotate(0); -moz-transform-origin: top left; -moz-animation-timing-function: ease-in-out; }	
	20%, 60% { -moz-transform: rotate(80deg); -moz-transform-origin: top left; -moz-animation-timing-function: ease-in-out; }	
	40% { -moz-transform: rotate(60deg); -moz-transform-origin: top left; -moz-animation-timing-function: ease-in-out; }	
	80% { -moz-transform: rotate(60deg) translateY(0); opacity: 1; -moz-transform-origin: top left; -moz-animation-timing-function: ease-in-out; }	
	100% { -moz-transform: translateY(700px); opacity: 0; }
}

@-o-keyframes hinge {
	0% { -o-transform: rotate(0); -o-transform-origin: top left; -o-animation-timing-function: ease-in-out; }	
	20%, 60% { -o-transform: rotate(80deg); -o-transform-origin: top left; -o-animation-timing-function: ease-in-out; }	
	40% { -o-transform: rotate(60deg); -o-transform-origin: top left; -o-animation-timing-function: ease-in-out; }	
	80% { -o-transform: rotate(60deg) translateY(0); opacity: 1; -o-transform-origin: top left; -o-animation-timing-function: ease-in-out; }	
	100% { -o-transform: translateY(700px); opacity: 0; }
}

@keyframes hinge {
	0% { transform: rotate(0); transform-origin: top left; animation-timing-function: ease-in-out; }	
	20%, 60% { transform: rotate(80deg); transform-origin: top left; animation-timing-function: ease-in-out; }	
	40% { transform: rotate(60deg); transform-origin: top left; animation-timing-function: ease-in-out; }	
	80% { transform: rotate(60deg) translateY(0); opacity: 1; transform-origin: top left; animation-timing-function: ease-in-out; }	
	100% { transform: translateY(700px); opacity: 0; }
}

.hinge {
	-webkit-animation-name: hinge;
	-moz-animation-name: hinge;
	-o-animation-name: hinge;
	animation-name: hinge;
}
/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes rollIn {
	0% { opacity: 0; -webkit-transform: translateX(-100%) rotate(-120deg); }
	100% { opacity: 1; -webkit-transform: translateX(0px) rotate(0deg); }
}

@-moz-keyframes rollIn {
	0% { opacity: 0; -moz-transform: translateX(-100%) rotate(-120deg); }
	100% { opacity: 1; -moz-transform: translateX(0px) rotate(0deg); }
}

@-o-keyframes rollIn {
	0% { opacity: 0; -o-transform: translateX(-100%) rotate(-120deg); }
	100% { opacity: 1; -o-transform: translateX(0px) rotate(0deg); }
}

@keyframes rollIn {
	0% { opacity: 0; transform: translateX(-100%) rotate(-120deg); }
	100% { opacity: 1; transform: translateX(0px) rotate(0deg); }
}

.rollIn {
	-webkit-animation-name: rollIn;
	-moz-animation-name: rollIn;
	-o-animation-name: rollIn;
	animation-name: rollIn;
}
/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes rollOut {
    0% {
		opacity: 1;
		-webkit-transform: translateX(0px) rotate(0deg);
	}

    100% {
		opacity: 0;
		-webkit-transform: translateX(100%) rotate(120deg);
	}
}

@-moz-keyframes rollOut {
    0% {
		opacity: 1;
		-moz-transform: translateX(0px) rotate(0deg);
	}

    100% {
		opacity: 0;
		-moz-transform: translateX(100%) rotate(120deg);
	}
}

@-o-keyframes rollOut {
    0% {
		opacity: 1;
		-o-transform: translateX(0px) rotate(0deg);
	}

    100% {
		opacity: 0;
		-o-transform: translateX(100%) rotate(120deg);
	}
}

@keyframes rollOut {
    0% {
		opacity: 1;
		transform: translateX(0px) rotate(0deg);
	}

    100% {
		opacity: 0;
		transform: translateX(100%) rotate(120deg);
	}
}

.rollOut {
	-webkit-animation-name: rollOut;
	-moz-animation-name: rollOut;
	-o-animation-name: rollOut;
	animation-name: rollOut;
}

/* originally authored by Angelo Rohit - https://github.com/angelorohit */

@-webkit-keyframes lightSpeedIn {
	0% { -webkit-transform: translateX(100%) skewX(-30deg); opacity: 0; }
	60% { -webkit-transform: translateX(-20%) skewX(30deg); opacity: 1; }
	80% { -webkit-transform: translateX(0%) skewX(-15deg); opacity: 1; }
	100% { -webkit-transform: translateX(0%) skewX(0deg); opacity: 1; }
}

@-moz-keyframes lightSpeedIn {
	0% { -moz-transform: translateX(100%) skewX(-30deg); opacity: 0; }
	60% { -moz-transform: translateX(-20%) skewX(30deg); opacity: 1; }
	80% { -moz-transform: translateX(0%) skewX(-15deg); opacity: 1; }
	100% { -moz-transform: translateX(0%) skewX(0deg); opacity: 1; }
}

@-o-keyframes lightSpeedIn {
	0% { -o-transform: translateX(100%) skewX(-30deg); opacity: 0; }
	60% { -o-transform: translateX(-20%) skewX(30deg); opacity: 1; }
	80% { -o-transform: translateX(0%) skewX(-15deg); opacity: 1; }
	100% { -o-transform: translateX(0%) skewX(0deg); opacity: 1; }
}

@keyframes lightSpeedIn {
	0% { transform: translateX(100%) skewX(-30deg); opacity: 0; }
	60% { transform: translateX(-20%) skewX(30deg); opacity: 1; }
	80% { transform: translateX(0%) skewX(-15deg); opacity: 1; }
	100% { transform: translateX(0%) skewX(0deg); opacity: 1; }
}

.lightSpeedIn {
    -webkit-animation-name: lightSpeedIn;
    -moz-animation-name: lightSpeedIn;
    -o-animation-name: lightSpeedIn;
    animation-name: lightSpeedIn;

    -webkit-animation-timing-function: ease-out;
    -moz-animation-timing-function: ease-out;
    -o-animation-timing-function: ease-out;
    animation-timing-function: ease-out;
}

.animated.lightSpeedIn {
    -webkit-animation-duration: 0.5s;
    -moz-animation-duration: 0.5s;
    -o-animation-duration: 0.5s;
    animation-duration: 0.5s;
}

/* originally authored by Angelo Rohit - https://github.com/angelorohit */

@-webkit-keyframes lightSpeedOut {
    0% { -webkit-transform: translateX(0%) skewX(0deg); opacity: 1; }
	100% { -webkit-transform: translateX(100%) skewX(-30deg); opacity: 0; }
}

@-moz-keyframes lightSpeedOut {
	0% { -moz-transform: translateX(0%) skewX(0deg); opacity: 1; }
	100% { -moz-transform: translateX(100%) skewX(-30deg); opacity: 0; }
}

@-o-keyframes lightSpeedOut {
	0% { -o-transform: translateX(0%) skewX(0deg); opacity: 1; }
	100% { -o-transform: translateX(100%) skewX(-30deg); opacity: 0; }
}

@keyframes lightSpeedOut {
	0% { transform: translateX(0%) skewX(0deg); opacity: 1; }
	100% { transform: translateX(100%) skewX(-30deg); opacity: 0; }
}

.lightSpeedOut {
    -webkit-animation-name: lightSpeedOut;
    -moz-animation-name: lightSpeedOut;
    -o-animation-name: lightSpeedOut;
    animation-name: lightSpeedOut;

    -webkit-animation-timing-function: ease-in;
    -moz-animation-timing-function: ease-in;
    -o-animation-timing-function: ease-in;
    animation-timing-function: ease-in;
}

.animated.lightSpeedOut {
    -webkit-animation-duration: 0.25s;
    -moz-animation-duration: 0.25s;
    -o-animation-duration: 0.25s;
    animation-duration: 0.25s;
}

/* originally authored by Angelo Rohit - https://github.com/angelorohit */

@-webkit-keyframes wiggle {
    0% { -webkit-transform: skewX(9deg); }
    10% { -webkit-transform: skewX(-8deg); }
    20% { -webkit-transform: skewX(7deg); }
    30% { -webkit-transform: skewX(-6deg); }
    40% { -webkit-transform: skewX(5deg); }
    50% { -webkit-transform: skewX(-4deg); }
    60% { -webkit-transform: skewX(3deg); }
    70% { -webkit-transform: skewX(-2deg); }
    80% { -webkit-transform: skewX(1deg); }
    90% { -webkit-transform: skewX(0deg); }
	100% { -webkit-transform: skewX(0deg); }
}

@-moz-keyframes wiggle {
    0% { -moz-transform: skewX(9deg); }
    10% { -moz-transform: skewX(-8deg); }
    20% { -moz-transform: skewX(7deg); }
    30% { -moz-transform: skewX(-6deg); }
    40% { -moz-transform: skewX(5deg); }
    50% { -moz-transform: skewX(-4deg); }
    60% { -moz-transform: skewX(3deg); }
    70% { -moz-transform: skewX(-2deg); }
    80% { -moz-transform: skewX(1deg); }
    90% { -moz-transform: skewX(0deg); }
	100% { -moz-transform: skewX(0deg); }
}

@-o-keyframes wiggle {
    0% { -o-transform: skewX(9deg); }
    10% { -o-transform: skewX(-8deg); }
    20% { -o-transform: skewX(7deg); }
    30% { -o-transform: skewX(-6deg); }
    40% { -o-transform: skewX(5deg); }
    50% { -o-transform: skewX(-4deg); }
    60% { -o-transform: skewX(3deg); }
    70% { -o-transform: skewX(-2deg); }
    80% { -o-transform: skewX(1deg); }
    90% { -o-transform: skewX(0deg); }
	100% { -o-transform: skewX(0deg); }
}

@keyframes wiggle {
    0% { transform: skewX(9deg); }
    10% { transform: skewX(-8deg); }
    20% { transform: skewX(7deg); }
    30% { transform: skewX(-6deg); }
    40% { transform: skewX(5deg); }
    50% { transform: skewX(-4deg); }
    60% { transform: skewX(3deg); }
    70% { transform: skewX(-2deg); }
    80% { transform: skewX(1deg); }
    90% { transform: skewX(0deg); }
	100% { transform: skewX(0deg); }
}

.wiggle {
    -webkit-animation-name: wiggle;
    -moz-animation-name: wiggle;
    -o-animation-name: wiggle;
    animation-name: wiggle;

    -webkit-animation-timing-function: ease-in;
    -moz-animation-timing-function: ease-in;
    -o-animation-timing-function: ease-in;
    animation-timing-function: ease-in;
}

.animated.wiggle {
    -webkit-animation-duration: 0.75s;
    -moz-animation-duration: 0.75s;
    -o-animation-duration: 0.75s;
    animation-duration: 0.75s;
}

/* ==================================================
Font-Face Icons
================================================== */

@font-face {
	font-family: 'Icons';
	src:url('../fonts/customicon/Icons.eot');
	src:url('../fonts/customicon/Icons.eot?#iefix') format('embedded-opentype'),
		url('../fonts/customicon/Icons.woff') format('woff'),
		url('../fonts/customicon/Icons.ttf') format('truetype'),
		url('../fonts/customicon/Icons.svg#Icons') format('svg');
	font-weight: normal;
	font-style: normal;
}

/* Use the following CSS code if you want to use data attributes for inserting your icons */
[data-icon]:before {
	font-family: 'Icons';
	content: attr(data-icon);
	speak: none;
	font-weight: normal;
	font-variant: normal;
	text-transform: none;
	line-height: 1;
	-webkit-font-smoothing: antialiased;
}

[class^="font-"]:before, [class*=" font-"]:before {
	font-family: 'Icons';
	speak: none;
	font-style: normal;
	font-weight: normal;
	font-variant: normal;
	text-transform: none;
	-webkit-font-smoothing: antialiased;
}

[class^="font-"],
[class*=" font-"]{
	display:inline-block;
	line-height:1em;
}

/* Use the following CSS code if you want to have a class per icon */
/*
Instead of a list of all class selectors,
you can use the generic selector below, but it's slower:
[class*="font-icon-"] {
*/
.font-icon-zoom-out, .font-icon-zoom-in, .font-icon-wrench, .font-icon-waves, .font-icon-warning, .font-icon-volume-up, .font-icon-volume-off, .font-icon-volume-down, .font-icon-viewport, .font-icon-user, .font-icon-user-border, .font-icon-upload, .font-icon-upload-2, .font-icon-unlock, .font-icon-underline, .font-icon-tint, .font-icon-time, .font-icon-text, .font-icon-text-width, .font-icon-text-height, .font-icon-tags, .font-icon-tag, .font-icon-table, .font-icon-strikethrough, .font-icon-stop, .font-icon-step-forward, .font-icon-step-backward, .font-icon-stars, .font-icon-star, .font-icon-star-line, .font-icon-star-half, .font-icon-sort, .font-icon-sort-up, .font-icon-sort-down, .font-icon-social-zerply, .font-icon-social-youtube, .font-icon-social-yelp, .font-icon-social-yahoo, .font-icon-social-wordpress, .font-icon-social-virb, .font-icon-social-vimeo, .font-icon-social-viddler, .font-icon-social-twitter, .font-icon-social-tumblr, .font-icon-social-stumbleupon, .font-icon-social-soundcloud, .font-icon-social-skype, .font-icon-social-share-this, .font-icon-social-quora, .font-icon-social-pinterest, .font-icon-social-photobucket, .font-icon-social-paypal, .font-icon-social-myspace, .font-icon-social-linkedin, .font-icon-social-last-fm, .font-icon-social-grooveshark, .font-icon-social-google-plus, .font-icon-social-github, .font-icon-social-forrst, .font-icon-social-flickr, .font-icon-social-facebook, .font-icon-social-evernote, .font-icon-social-envato, .font-icon-social-email, .font-icon-social-dribbble, .font-icon-social-digg, .font-icon-social-deviant-art, .font-icon-social-blogger, .font-icon-social-behance, .font-icon-social-bebo, .font-icon-social-addthis, .font-icon-social-500px, .font-icon-sitemap, .font-icon-signout, .font-icon-signin, .font-icon-signal, .font-icon-shopping-cart, .font-icon-search, .font-icon-rss, .font-icon-road, .font-icon-retweet, .font-icon-resize-vertical, .font-icon-resize-vertical-2, .font-icon-resize-small, .font-icon-resize-horizontal, .font-icon-resize-horizontal-2, .font-icon-resize-fullscreen, .font-icon-resize-full, .font-icon-repeat, .font-icon-reorder, .font-icon-remove, .font-icon-remove-sign, .font-icon-remove-circle, .font-icon-read-more, .font-icon-random, .font-icon-question-sign, .font-icon-pushpin, .font-icon-pushpin-2, .font-icon-print, .font-icon-plus, .font-icon-plus-sign, .font-icon-play, .font-icon-picture, .font-icon-phone, .font-icon-phone-sign, .font-icon-phone-boxed, .font-icon-pause, .font-icon-paste, .font-icon-paper-clip, .font-icon-ok, .font-icon-ok-sign, .font-icon-ok-circle, .font-icon-music, .font-icon-move, .font-icon-money, .font-icon-minus, .font-icon-minus-sign, .font-icon-map, .font-icon-map-marker, .font-icon-map-marker-2, .font-icon-magnet, .font-icon-magic, .font-icon-lock, .font-icon-list, .font-icon-list-3, .font-icon-list-2, .font-icon-link, .font-icon-layer, .font-icon-key, .font-icon-italic, .font-icon-info, .font-icon-indent-right, .font-icon-indent-left, .font-icon-inbox, .font-icon-inbox-empty, .font-icon-home, .font-icon-heart, .font-icon-heart-line, .font-icon-headphones, .font-icon-headphones-line, .font-icon-headphones-line-2, .font-icon-headphones-2, .font-icon-hdd, .font-icon-group, .font-icon-grid, .font-icon-grid-large, .font-icon-globe_line, .font-icon-glass, .font-icon-glass_2, .font-icon-gift, .font-icon-forward, .font-icon-font, .font-icon-folder-open, .font-icon-folder-close, .font-icon-flag, .font-icon-fire, .font-icon-film, .font-icon-file, .font-icon-file-empty, .font-icon-fast-forward, .font-icon-fast-backward, .font-icon-facetime, .font-icon-eye, .font-icon-eye_disable, .font-icon-expand-view, .font-icon-expand-view-3, .font-icon-expand-view-2, .font-icon-expand-vertical, .font-icon-expand-horizontal, .font-icon-exclamation, .font-icon-email, .font-icon-email_2, .font-icon-eject, .font-icon-edit, .font-icon-edit-check, .font-icon-download, .font-icon-download_2, .font-icon-dashboard, .font-icon-credit-card, .font-icon-copy, .font-icon-comments, .font-icon-comments-line, .font-icon-comment, .font-icon-comment-line, .font-icon-columns, .font-icon-columns-2, .font-icon-cogs, .font-icon-cog, .font-icon-cloud, .font-icon-check, .font-icon-check-empty, .font-icon-certificate, .font-icon-camera, .font-icon-calendar, .font-icon-bullhorn, .font-icon-briefcase, .font-icon-bookmark, .font-icon-book, .font-icon-bolt, .font-icon-bold, .font-icon-blockquote, .font-icon-bell, .font-icon-beaker, .font-icon-barcode, .font-icon-ban-circle, .font-icon-ban-chart, .font-icon-ban-chart-2, .font-icon-backward, .font-icon-asterisk, .font-icon-arrow-simple-up, .font-icon-arrow-simple-up-circle, .font-icon-arrow-simple-right, .font-icon-arrow-simple-right-circle, .font-icon-arrow-simple-left, .font-icon-arrow-simple-left-circle, .font-icon-arrow-simple-down, .font-icon-arrow-simple-down-circle, .font-icon-arrow-round-up, .font-icon-arrow-round-up-circle, .font-icon-arrow-round-right, .font-icon-arrow-round-right-circle, .font-icon-arrow-round-left, .font-icon-arrow-round-left-circle, .font-icon-arrow-round-down, .font-icon-arrow-round-down-circle, .font-icon-arrow-light-up, .font-icon-arrow-light-round-up, .font-icon-arrow-light-round-up-circle, .font-icon-arrow-light-round-right, .font-icon-arrow-light-round-right-circle, .font-icon-arrow-light-round-left, .font-icon-arrow-light-round-left-circle, .font-icon-arrow-light-round-down, .font-icon-arrow-light-round-down-circle, .font-icon-arrow-light-right, .font-icon-arrow-light-left, .font-icon-arrow-light-down, .font-icon-align-right, .font-icon-align-left, .font-icon-align-justify, .font-icon-align-center, .font-icon-adjust {
	font-family: 'Icons';
	speak: none;
	font-style: normal;
	font-weight: normal;
	font-variant: normal;
	text-transform: none;
	line-height: 1;
	-webkit-font-smoothing: antialiased;
}
.font-icon-zoom-out:before {
	content: "\e000";
}
.font-icon-zoom-in:before {
	content: "\e001";
}
.font-icon-wrench:before {
	content: "\e002";
}
.font-icon-waves:before {
	content: "\e003";
}
.font-icon-warning:before {
	content: "\e004";
}
.font-icon-volume-up:before {
	content: "\e005";
}
.font-icon-volume-off:before {
	content: "\e006";
}
.font-icon-volume-down:before {
	content: "\e007";
}
.font-icon-viewport:before {
	content: "\e008";
}
.font-icon-user:before {
	content: "\e009";
}
.font-icon-user-border:before {
	content: "\e00a";
}
.font-icon-upload:before {
	content: "\e00b";
}
.font-icon-upload-2:before {
	content: "\e00c";
}
.font-icon-unlock:before {
	content: "\e00d";
}
.font-icon-underline:before {
	content: "\e00e";
}
.font-icon-tint:before {
	content: "\e00f";
}
.font-icon-time:before {
	content: "\e010";
}
.font-icon-text:before {
	content: "\e011";
}
.font-icon-text-width:before {
	content: "\e012";
}
.font-icon-text-height:before {
	content: "\e013";
}
.font-icon-tags:before {
	content: "\e014";
}
.font-icon-tag:before {
	content: "\e015";
}
.font-icon-table:before {
	content: "\e016";
}
.font-icon-strikethrough:before {
	content: "\e017";
}
.font-icon-stop:before {
	content: "\e018";
}
.font-icon-step-forward:before {
	content: "\e019";
}
.font-icon-step-backward:before {
	content: "\e01a";
}
.font-icon-stars:before {
	content: "\e01b";
}
.font-icon-star:before {
	content: "\e01c";
}
.font-icon-star-line:before {
	content: "\e01d";
}
.font-icon-star-half:before {
	content: "\e01e";
}
.font-icon-sort:before {
	content: "\e01f";
}
.font-icon-sort-up:before {
	content: "\e020";
}
.font-icon-sort-down:before {
	content: "\e021";
}
.font-icon-social-zerply:before {
	content: "\e022";
}
.font-icon-social-youtube:before {
	content: "\e023";
}
.font-icon-social-yelp:before {
	content: "\e024";
}
.font-icon-social-yahoo:before {
	content: "\e025";
}
.font-icon-social-wordpress:before {
	content: "\e026";
}
.font-icon-social-virb:before {
	content: "\e027";
}
.font-icon-social-vimeo:before {
	content: "\e028";
}
.font-icon-social-viddler:before {
	content: "\e029";
}
.font-icon-social-twitter:before {
	content: "\e02a";
}
.font-icon-social-tumblr:before {
	content: "\e02b";
}
.font-icon-social-stumbleupon:before {
	content: "\e02c";
}
.font-icon-social-soundcloud:before {
	content: "\e02d";
}
.font-icon-social-skype:before {
	content: "\e02e";
}
.font-icon-social-share-this:before {
	content: "\e02f";
}
.font-icon-social-quora:before {
	content: "\e030";
}
.font-icon-social-pinterest:before {
	content: "\e031";
}
.font-icon-social-photobucket:before {
	content: "\e032";
}
.font-icon-social-paypal:before {
	content: "\e033";
}
.font-icon-social-myspace:before {
	content: "\e034";
}
.font-icon-social-linkedin:before {
	content: "\e035";
}
.font-icon-social-last-fm:before {
	content: "\e036";
}
.font-icon-social-grooveshark:before {
	content: "\e037";
}
.font-icon-social-google-plus:before {
	content: "\e038";
}
.font-icon-social-github:before {
	content: "\e039";
}
.font-icon-social-forrst:before {
	content: "\e03a";
}
.font-icon-social-flickr:before {
	content: "\e03b";
}
.font-icon-social-facebook:before {
	content: "\e03c";
}
.font-icon-social-evernote:before {
	content: "\e03d";
}
.font-icon-social-envato:before {
	content: "\e03e";
}
.font-icon-social-email:before {
	content: "\e03f";
}
.font-icon-social-dribbble:before {
	content: "\e040";
}
.font-icon-social-digg:before {
	content: "\e041";
}
.font-icon-social-deviant-art:before {
	content: "\e042";
}
.font-icon-social-blogger:before {
	content: "\e043";
}
.font-icon-social-behance:before {
	content: "\e044";
}
.font-icon-social-bebo:before {
	content: "\e045";
}
.font-icon-social-addthis:before {
	content: "\e046";
}
.font-icon-social-500px:before {
	content: "\e047";
}
.font-icon-sitemap:before {
	content: "\e048";
}
.font-icon-signout:before {
	content: "\e049";
}
.font-icon-signin:before {
	content: "\e04a";
}
.font-icon-signal:before {
	content: "\e04b";
}
.font-icon-shopping-cart:before {
	content: "\e04c";
}
.font-icon-search:before {
	content: "\e04d";
}
.font-icon-rss:before {
	content: "\e04e";
}
.font-icon-road:before {
	content: "\e04f";
}
.font-icon-retweet:before {
	content: "\e050";
}
.font-icon-resize-vertical:before {
	content: "\e051";
}
.font-icon-resize-vertical-2:before {
	content: "\e052";
}
.font-icon-resize-small:before {
	content: "\e053";
}
.font-icon-resize-horizontal:before {
	content: "\e054";
}
.font-icon-resize-horizontal-2:before {
	content: "\e055";
}
.font-icon-resize-fullscreen:before {
	content: "\e056";
}
.font-icon-resize-full:before {
	content: "\e057";
}
.font-icon-repeat:before {
	content: "\e058";
}
.font-icon-reorder:before {
	content: "\e059";
}
.font-icon-remove:before {
	content: "\e05a";
}
.font-icon-remove-sign:before {
	content: "\e05b";
}
.font-icon-remove-circle:before {
	content: "\e05c";
}
.font-icon-read-more:before {
	content: "\e05d";
}
.font-icon-random:before {
	content: "\e05e";
}
.font-icon-question-sign:before {
	content: "\e05f";
}
.font-icon-pushpin:before {
	content: "\e060";
}
.font-icon-pushpin-2:before {
	content: "\e061";
}
.font-icon-print:before {
	content: "\e062";
}
.font-icon-plus:before {
	content: "\e063";
}
.font-icon-plus-sign:before {
	content: "\e064";
}
.font-icon-play:before {
	content: "\e065";
}
.font-icon-picture:before {
	content: "\e066";
}
.font-icon-phone:before {
	content: "\e067";
}
.font-icon-phone-sign:before {
	content: "\e068";
}
.font-icon-phone-boxed:before {
	content: "\e069";
}
.font-icon-pause:before {
	content: "\e06a";
}
.font-icon-paste:before {
	content: "\e06b";
}
.font-icon-paper-clip:before {
	content: "\e06c";
}
.font-icon-ok:before {
	content: "\e06d";
}
.font-icon-ok-sign:before {
	content: "\e06e";
}
.font-icon-ok-circle:before {
	content: "\e06f";
}
.font-icon-music:before {
	content: "\e070";
}
.font-icon-move:before {
	content: "\e071";
}
.font-icon-money:before {
	content: "\e072";
}
.font-icon-minus:before {
	content: "\e073";
}
.font-icon-minus-sign:before {
	content: "\e074";
}
.font-icon-map:before {
	content: "\e075";
}
.font-icon-map-marker:before {
	content: "\e076";
}
.font-icon-map-marker-2:before {
	content: "\e077";
}
.font-icon-magnet:before {
	content: "\e078";
}
.font-icon-magic:before {
	content: "\e079";
}
.font-icon-lock:before {
	content: "\e07a";
}
.font-icon-list:before {
	content: "\e07b";
}
.font-icon-list-3:before {
	content: "\e07c";
}
.font-icon-list-2:before {
	content: "\e07d";
}
.font-icon-link:before {
	content: "\e07e";
}
.font-icon-layer:before {
	content: "\e07f";
}
.font-icon-key:before {
	content: "\e080";
}
.font-icon-italic:before {
	content: "\e081";
}
.font-icon-info:before {
	content: "\e082";
}
.font-icon-indent-right:before {
	content: "\e083";
}
.font-icon-indent-left:before {
	content: "\e084";
}
.font-icon-inbox:before {
	content: "\e085";
}
.font-icon-inbox-empty:before {
	content: "\e086";
}
.font-icon-home:before {
	content: "\e087";
}
.font-icon-heart:before {
	content: "\e088";
}
.font-icon-heart-line:before {
	content: "\e089";
}
.font-icon-headphones:before {
	content: "\e08a";
}
.font-icon-headphones-line:before {
	content: "\e08b";
}
.font-icon-headphones-line-2:before {
	content: "\e08c";
}
.font-icon-headphones-2:before {
	content: "\e08d";
}
.font-icon-hdd:before {
	content: "\e08e";
}
.font-icon-group:before {
	content: "\e08f";
}
.font-icon-grid:before {
	content: "\e090";
}
.font-icon-grid-large:before {
	content: "\e091";
}
.font-icon-globe_line:before {
	content: "\e092";
}
.font-icon-glass:before {
	content: "\e093";
}
.font-icon-glass_2:before {
	content: "\e094";
}
.font-icon-gift:before {
	content: "\e095";
}
.font-icon-forward:before {
	content: "\e096";
}
.font-icon-font:before {
	content: "\e097";
}
.font-icon-folder-open:before {
	content: "\e098";
}
.font-icon-folder-close:before {
	content: "\e099";
}
.font-icon-flag:before {
	content: "\e09a";
}
.font-icon-fire:before {
	content: "\e09b";
}
.font-icon-film:before {
	content: "\e09c";
}
.font-icon-file:before {
	content: "\e09d";
}
.font-icon-file-empty:before {
	content: "\e09e";
}
.font-icon-fast-forward:before {
	content: "\e09f";
}
.font-icon-fast-backward:before {
	content: "\e0a0";
}
.font-icon-facetime:before {
	content: "\e0a1";
}
.font-icon-eye:before {
	content: "\e0a2";
}
.font-icon-eye_disable:before {
	content: "\e0a3";
}
.font-icon-expand-view:before {
	content: "\e0a4";
}
.font-icon-expand-view-3:before {
	content: "\e0a5";
}
.font-icon-expand-view-2:before {
	content: "\e0a6";
}
.font-icon-expand-vertical:before {
	content: "\e0a7";
}
.font-icon-expand-horizontal:before {
	content: "\e0a8";
}
.font-icon-exclamation:before {
	content: "\e0a9";
}
.font-icon-email:before {
	content: "\e0aa";
}
.font-icon-email_2:before {
	content: "\e0ab";
}
.font-icon-eject:before {
	content: "\e0ac";
}
.font-icon-edit:before {
	content: "\e0ad";
}
.font-icon-edit-check:before {
	content: "\e0ae";
}
.font-icon-download:before {
	content: "\e0af";
}
.font-icon-download_2:before {
	content: "\e0b0";
}
.font-icon-dashboard:before {
	content: "\e0b1";
}
.font-icon-credit-card:before {
	content: "\e0b2";
}
.font-icon-copy:before {
	content: "\e0b3";
}
.font-icon-comments:before {
	content: "\e0b4";
}
.font-icon-comments-line:before {
	content: "\e0b5";
}
.font-icon-comment:before {
	content: "\e0b6";
}
.font-icon-comment-line:before {
	content: "\e0b7";
}
.font-icon-columns:before {
	content: "\e0b8";
}
.font-icon-columns-2:before {
	content: "\e0b9";
}
.font-icon-cogs:before {
	content: "\e0ba";
}
.font-icon-cog:before {
	content: "\e0bb";
}
.font-icon-cloud:before {
	content: "\e0bc";
}
.font-icon-check:before {
	content: "\e0bd";
}
.font-icon-check-empty:before {
	content: "\e0be";
}
.font-icon-certificate:before {
	content: "\e0bf";
}
.font-icon-camera:before {
	content: "\e0c0";
}
.font-icon-calendar:before {
	content: "\e0c1";
}
.font-icon-bullhorn:before {
	content: "\e0c2";
}
.font-icon-briefcase:before {
	content: "\e0c3";
}
.font-icon-bookmark:before {
	content: "\e0c4";
}
.font-icon-book:before {
	content: "\e0c5";
}
.font-icon-bolt:before {
	content: "\e0c6";
}
.font-icon-bold:before {
	content: "\e0c7";
}
.font-icon-blockquote:before {
	content: "\e0c8";
}
.font-icon-bell:before {
	content: "\e0c9";
}
.font-icon-beaker:before {
	content: "\e0ca";
}
.font-icon-barcode:before {
	content: "\e0cb";
}
.font-icon-ban-circle:before {
	content: "\e0cc";
}
.font-icon-ban-chart:before {
	content: "\e0cd";
}
.font-icon-ban-chart-2:before {
	content: "\e0ce";
}
.font-icon-backward:before {
	content: "\e0cf";
}
.font-icon-asterisk:before {
	content: "\e0d0";
}
.font-icon-arrow-simple-up:before {
	content: "\e0d1";
}
.font-icon-arrow-simple-up-circle:before {
	content: "\e0d2";
}
.font-icon-arrow-simple-right:before {
	content: "\e0d3";
}
.font-icon-arrow-simple-right-circle:before {
	content: "\e0d4";
}
.font-icon-arrow-simple-left:before {
	content: "\e0d5";
}
.font-icon-arrow-simple-left-circle:before {
	content: "\e0d6";
}
.font-icon-arrow-simple-down:before {
	content: "\e0d7";
}
.font-icon-arrow-simple-down-circle:before {
	content: "\e0d8";
}
.font-icon-arrow-round-up:before {
	content: "\e0d9";
}
.font-icon-arrow-round-up-circle:before {
	content: "\e0da";
}
.font-icon-arrow-round-right:before {
	content: "\e0db";
}
.font-icon-arrow-round-right-circle:before {
	content: "\e0dc";
}
.font-icon-arrow-round-left:before {
	content: "\e0dd";
}
.font-icon-arrow-round-left-circle:before {
	content: "\e0de";
}
.font-icon-arrow-round-down:before {
	content: "\e0df";
}
.font-icon-arrow-round-down-circle:before {
	content: "\e0e0";
}
.font-icon-arrow-light-up:before {
	content: "\e0e1";
}
.font-icon-arrow-light-round-up:before {
	content: "\e0e2";
}
.font-icon-arrow-light-round-up-circle:before {
	content: "\e0e3";
}
.font-icon-arrow-light-round-right:before {
	content: "\e0e4";
}
.font-icon-arrow-light-round-right-circle:before {
	content: "\e0e5";
}
.font-icon-arrow-light-round-left:before {
	content: "\e0e6";
}
.font-icon-arrow-light-round-left-circle:before {
	content: "\e0e7";
}
.font-icon-arrow-light-round-down:before {
	content: "\e0e8";
}
.font-icon-arrow-light-round-down-circle:before {
	content: "\e0e9";
}
.font-icon-arrow-light-right:before {
	content: "\e0ea";
}
.font-icon-arrow-light-left:before {
	content: "\e0eb";
}
.font-icon-arrow-light-down:before {
	content: "\e0ec";
}
.font-icon-align-right:before {
	content: "\e0ed";
}
.font-icon-align-left:before {
	content: "\e0ee";
}
.font-icon-align-justify:before {
	content: "\e0ef";
}
.font-icon-align-center:before {
	content: "\e0f0";
}
.font-icon-adjust:before {
	content: "\e0f1";
}

/*
 * jQuery FlexSlider v2.0
 * http://www.woothemes.com/flexslider/
 *
 * Copyright 2012 WooThemes
 * Free to use under the GPLv2 license.
 * http://www.gnu.org/licenses/gpl-2.0.html
 *
 * Contributing author: Tyler Smith (@mbmufffin)
 */

 
/* Browser Resets */
.flex-container a:active,
.flexslider a:active,
.flex-container a:focus,
.flexslider a:focus  {outline: none;}
.slides,
.flex-control-nav,
.flex-direction-nav {margin: 0; padding: 0; list-style: none;} 

/* FlexSlider Necessary Styles
*********************************/ 
.flexslider { margin: 0; padding: 0;}
.flexslider .slides > li {display: none; -webkit-backface-visibility: hidden;} /* Hide the slides before the JS is loaded. Avoids image jumping */
.flexslider .slides img { width: 100%; display: block;}
.flex-pauseplay span {text-transform: capitalize;}

/* Clearfix for the .slides element */
.slides:after {content: "."; display: block; clear: both; visibility: hidden; line-height: 0; height: 0;} 
html[xmlns] .slides {display: block;} 
* html .slides {height: 1%;}

/* No JavaScript Fallback */
/* If you are not using another script, such as Modernizr, make sure you
 * include js that eliminates this class on page load */
.no-js .slides > li:first-child {display: block;}


/* FlexSlider Default Theme
*********************************/
.flexslider {background:none; position: relative; 
zoom: 1;}
.flex-viewport {max-height: 2000px; -webkit-transition: all 1s ease; -moz-transition: all 1s ease; transition: all 1s ease;}
.loading .flex-viewport {max-height: 300px;}
.flexslider .slides {zoom: 1;}

.carousel li {margin-right: 5px}

/* Caption style */

.flex-caption { background: rgba(0,0,0,.8); margin-left:5px;bottom:5px; position:absolute;padding:20px; z-index:99;}
.flex-caption p{ font-size: 14px !important; line-height: 22px; 
font-weight:300; color: #fff }
.flex-caption h2, .flex-caption h4 {
	color:#fff;
}

/* Direction Nav */
.flex-direction-nav {*height: 0;}
.flex-direction-nav a {width: 30px; height: 40px; margin:0; display: block; background: url(../img/bg_direction_nav.png) no-repeat 0 0; position: absolute; top: 45%; z-index: 10; cursor: pointer; text-indent: -9999px; opacity: 0; -webkit-transition: all .3s ease;}
.flex-direction-nav .flex-next {background-position: 100% 0; right: -36px; }
.flex-direction-nav .flex-prev {left: -36px;}
.flexslider:hover .flex-next {opacity: 0.8; right: 5px;}
.flexslider:hover .flex-prev {opacity: 0.8; left: 5px;}
.flexslider:hover .flex-next:hover, .flexslider:hover .flex-prev:hover {opacity: 1;}
.flex-direction-nav .flex-disabled {opacity: .3!important; filter:alpha(opacity=30); cursor: default;}

/* Control Nav */
.flex-control-nav {width: 100%; position: absolute; bottom: 0; text-align: center;}
.flex-control-nav li {margin: 0 6px; display: inline-block; zoom: 1; *display: inline;}
.flex-control-paging li a {width: 11px; height: 11px; display: block; background: #666; background: rgba(0,0,0,0.5); cursor: pointer; text-indent: -9999px; -webkit-border-radius: 20px; -moz-border-radius: 20px; -o-border-radius: 20px; border-radius: 20px; box-shadow: inset 0 0 3px rgba(0,0,0,0.3);}
.flex-control-paging li a:hover { background: #333; background: rgba(0,0,0,0.7); }
.flex-control-paging li a.flex-active { background: #000; background: rgba(0,0,0,0.9); cursor: default; }

.flex-control-thumbs {margin: 5px 0 0; position: static; overflow: hidden;}
.flex-control-thumbs li {width: 25%; float: left; margin: 0;}
.flex-control-thumbs img {width: 100%; display: block; opacity: .7; cursor: pointer;}
.flex-control-thumbs img:hover {opacity: 1;}
.flex-control-thumbs .flex-active {opacity: 1; cursor: default;}

@media screen and (max-width: 860px) {
  .flex-direction-nav .flex-prev {opacity: 1; left: 0;}
  .flex-direction-nav .flex-next {opacity: 1; right: 0;}
}

/*!
 *  Font Awesome 4.0.3 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
 @font-face {
    font-family: 'FontAwesome';
    src: url('../fonts/fontawesome-webfont.eot?v=4.0.3');
    src: url('../fonts/fontawesome-webfont.eot?#iefix&v=4.0.3') format('embedded-opentype'), url('../fonts/fontawesome-webfont.woff?v=4.0.3') format('woff'), url('../fonts/fontawesome-webfont.ttf?v=4.0.3') format('truetype'), url('../fonts/fontawesome-webfont.svg?v=4.0.3#fontawesomeregular') format('svg');
    font-weight: normal;
    font-style: normal;
  }
  .fa {
    display: inline-block;
    font-family: FontAwesome;
    font-style: normal;
    font-weight: normal;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
  /* makes the font 33% larger relative to the icon container */
  .fa-lg {
    font-size: 1.3333333333333333em;
    line-height: 0.75em;
    vertical-align: -15%;
  }
  .fa-2x {
    font-size: 2em;
  }
  .fa-3x {
    font-size: 3em;
  }
  .fa-4x {
    font-size: 4em;
  }
  .fa-5x {
    font-size: 5em;
  }
  .fa-fw {
    width: 1.2857142857142858em;
    text-align: center;
  }
  .fa-ul {
    padding-left: 0;
    margin-left: 2.142857142857143em;
    list-style-type: none;
  }
  .fa-ul > li {
    position: relative;
  }
  .fa-li {
    position: absolute;
    left: -2.142857142857143em;
    width: 2.142857142857143em;
    top: 0.14285714285714285em;
    text-align: center;
  }
  .fa-li.fa-lg {
    left: -1.8571428571428572em;
  }
  .fa-border {
    padding: .2em .25em .15em;
    border: solid 0.08em #eeeeee;
    border-radius: .1em;
  }
  .pull-right {
    float: right;
  }
  .pull-left {
    float: left;
  }
  .fa.pull-left {
    margin-right: .3em;
  }
  .fa.pull-right {
    margin-left: .3em;
  }
  .fa-spin {
    -webkit-animation: spin 2s infinite linear;
    -moz-animation: spin 2s infinite linear;
    -o-animation: spin 2s infinite linear;
    animation: spin 2s infinite linear;
  }
  @-moz-keyframes spin {
    0% {
      -moz-transform: rotate(0deg);
    }
    100% {
      -moz-transform: rotate(359deg);
    }
  }
  @-webkit-keyframes spin {
    0% {
      -webkit-transform: rotate(0deg);
    }
    100% {
      -webkit-transform: rotate(359deg);
    }
  }
  @-o-keyframes spin {
    0% {
      -o-transform: rotate(0deg);
    }
    100% {
      -o-transform: rotate(359deg);
    }
  }
  @-ms-keyframes spin {
    0% {
      -ms-transform: rotate(0deg);
    }
    100% {
      -ms-transform: rotate(359deg);
    }
  }
  @keyframes spin {
    0% {
      transform: rotate(0deg);
    }
    100% {
      transform: rotate(359deg);
    }
  }
  .fa-rotate-90 {
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
    -webkit-transform: rotate(90deg);
    -moz-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    -o-transform: rotate(90deg);
    transform: rotate(90deg);
  }
  .fa-rotate-180 {
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
    -webkit-transform: rotate(180deg);
    -moz-transform: rotate(180deg);
    -ms-transform: rotate(180deg);
    -o-transform: rotate(180deg);
    transform: rotate(180deg);
  }
  .fa-rotate-270 {
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
    -webkit-transform: rotate(270deg);
    -moz-transform: rotate(270deg);
    -ms-transform: rotate(270deg);
    -o-transform: rotate(270deg);
    transform: rotate(270deg);
  }
  .fa-flip-horizontal {
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
    -webkit-transform: scale(-1, 1);
    -moz-transform: scale(-1, 1);
    -ms-transform: scale(-1, 1);
    -o-transform: scale(-1, 1);
    transform: scale(-1, 1);
  }
  .fa-flip-vertical {
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
    -webkit-transform: scale(1, -1);
    -moz-transform: scale(1, -1);
    -ms-transform: scale(1, -1);
    -o-transform: scale(1, -1);
    transform: scale(1, -1);
  }
  .fa-stack {
    position: relative;
    display: inline-block;
    width: 2em;
    height: 2em;
    line-height: 2em;
    vertical-align: middle;
  }
  .fa-stack-1x,
  .fa-stack-2x {
    position: absolute;
    left: 0;
    width: 100%;
    text-align: center;
  }
  .fa-stack-1x {
    line-height: inherit;
  }
  .fa-stack-2x {
    font-size: 2em;
  }
  .fa-inverse {
    color: #ffffff;
  }
  /* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
     readers do not read off random characters that represent icons */
  .fa-glass:before {
    content: "\f000";
  }
  .fa-music:before {
    content: "\f001";
  }
  .fa-search:before {
    content: "\f002";
  }
  .fa-envelope-o:before {
    content: "\f003";
  }
  .fa-heart:before {
    content: "\f004";
  }
  .fa-star:before {
    content: "\f005";
  }
  .fa-star-o:before {
    content: "\f006";
  }
  .fa-user:before {
    content: "\f007";
  }
  .fa-film:before {
    content: "\f008";
  }
  .fa-th-large:before {
    content: "\f009";
  }
  .fa-th:before {
    content: "\f00a";
  }
  .fa-th-list:before {
    content: "\f00b";
  }
  .fa-check:before {
    content: "\f00c";
  }
  .fa-times:before {
    content: "\f00d";
  }
  .fa-search-plus:before {
    content: "\f00e";
  }
  .fa-search-minus:before {
    content: "\f010";
  }
  .fa-power-off:before {
    content: "\f011";
  }
  .fa-signal:before {
    content: "\f012";
  }
  .fa-gear:before,
  .fa-cog:before {
    content: "\f013";
  }
  .fa-trash-o:before {
    content: "\f014";
  }
  .fa-home:before {
    content: "\f015";
  }
  .fa-file-o:before {
    content: "\f016";
  }
  .fa-clock-o:before {
    content: "\f017";
  }
  .fa-road:before {
    content: "\f018";
  }
  .fa-download:before {
    content: "\f019";
  }
  .fa-arrow-circle-o-down:before {
    content: "\f01a";
  }
  .fa-arrow-circle-o-up:before {
    content: "\f01b";
  }
  .fa-inbox:before {
    content: "\f01c";
  }
  .fa-play-circle-o:before {
    content: "\f01d";
  }
  .fa-rotate-right:before,
  .fa-repeat:before {
    content: "\f01e";
  }
  .fa-refresh:before {
    content: "\f021";
  }
  .fa-list-alt:before {
    content: "\f022";
  }
  .fa-lock:before {
    content: "\f023";
  }
  .fa-flag:before {
    content: "\f024";
  }
  .fa-headphones:before {
    content: "\f025";
  }
  .fa-volume-off:before {
    content: "\f026";
  }
  .fa-volume-down:before {
    content: "\f027";
  }
  .fa-volume-up:before {
    content: "\f028";
  }
  .fa-qrcode:before {
    content: "\f029";
  }
  .fa-barcode:before {
    content: "\f02a";
  }
  .fa-tag:before {
    content: "\f02b";
  }
  .fa-tags:before {
    content: "\f02c";
  }
  .fa-book:before {
    content: "\f02d";
  }
  .fa-bookmark:before {
    content: "\f02e";
  }
  .fa-print:before {
    content: "\f02f";
  }
  .fa-camera:before {
    content: "\f030";
  }
  .fa-font:before {
    content: "\f031";
  }
  .fa-bold:before {
    content: "\f032";
  }
  .fa-italic:before {
    content: "\f033";
  }
  .fa-text-height:before {
    content: "\f034";
  }
  .fa-text-width:before {
    content: "\f035";
  }
  .fa-align-left:before {
    content: "\f036";
  }
  .fa-align-center:before {
    content: "\f037";
  }
  .fa-align-right:before {
    content: "\f038";
  }
  .fa-align-justify:before {
    content: "\f039";
  }
  .fa-list:before {
    content: "\f03a";
  }
  .fa-dedent:before,
  .fa-outdent:before {
    content: "\f03b";
  }
  .fa-indent:before {
    content: "\f03c";
  }
  .fa-video-camera:before {
    content: "\f03d";
  }
  .fa-picture-o:before {
    content: "\f03e";
  }
  .fa-pencil:before {
    content: "\f040";
  }
  .fa-map-marker:before {
    content: "\f041";
  }
  .fa-adjust:before {
    content: "\f042";
  }
  .fa-tint:before {
    content: "\f043";
  }
  .fa-edit:before,
  .fa-pencil-square-o:before {
    content: "\f044";
  }
  .fa-share-square-o:before {
    content: "\f045";
  }
  .fa-check-square-o:before {
    content: "\f046";
  }
  .fa-arrows:before {
    content: "\f047";
  }
  .fa-step-backward:before {
    content: "\f048";
  }
  .fa-fast-backward:before {
    content: "\f049";
  }
  .fa-backward:before {
    content: "\f04a";
  }
  .fa-play:before {
    content: "\f04b";
  }
  .fa-pause:before {
    content: "\f04c";
  }
  .fa-stop:before {
    content: "\f04d";
  }
  .fa-forward:before {
    content: "\f04e";
  }
  .fa-fast-forward:before {
    content: "\f050";
  }
  .fa-step-forward:before {
    content: "\f051";
  }
  .fa-eject:before {
    content: "\f052";
  }
  .fa-chevron-left:before {
    content: "\f053";
  }
  .fa-chevron-right:before {
    content: "\f054";
  }
  .fa-plus-circle:before {
    content: "\f055";
  }
  .fa-minus-circle:before {
    content: "\f056";
  }
  .fa-times-circle:before {
    content: "\f057";
  }
  .fa-check-circle:before {
    content: "\f058";
  }
  .fa-question-circle:before {
    content: "\f059";
  }
  .fa-info-circle:before {
    content: "\f05a";
  }
  .fa-crosshairs:before {
    content: "\f05b";
  }
  .fa-times-circle-o:before {
    content: "\f05c";
  }
  .fa-check-circle-o:before {
    content: "\f05d";
  }
  .fa-ban:before {
    content: "\f05e";
  }
  .fa-arrow-left:before {
    content: "\f060";
  }
  .fa-arrow-right:before {
    content: "\f061";
  }
  .fa-arrow-up:before {
    content: "\f062";
  }
  .fa-arrow-down:before {
    content: "\f063";
  }
  .fa-mail-forward:before,
  .fa-share:before {
    content: "\f064";
  }
  .fa-expand:before {
    content: "\f065";
  }
  .fa-compress:before {
    content: "\f066";
  }
  .fa-plus:before {
    content: "\f067";
  }
  .fa-minus:before {
    content: "\f068";
  }
  .fa-asterisk:before {
    content: "\f069";
  }
  .fa-exclamation-circle:before {
    content: "\f06a";
  }
  .fa-gift:before {
    content: "\f06b";
  }
  .fa-leaf:before {
    content: "\f06c";
  }
  .fa-fire:before {
    content: "\f06d";
  }
  .fa-eye:before {
    content: "\f06e";
  }
  .fa-eye-slash:before {
    content: "\f070";
  }
  .fa-warning:before,
  .fa-exclamation-triangle:before {
    content: "\f071";
  }
  .fa-plane:before {
    content: "\f072";
  }
  .fa-calendar:before {
    content: "\f073";
  }
  .fa-random:before {
    content: "\f074";
  }
  .fa-comment:before {
    content: "\f075";
  }
  .fa-magnet:before {
    content: "\f076";
  }
  .fa-chevron-up:before {
    content: "\f077";
  }
  .fa-chevron-down:before {
    content: "\f078";
  }
  .fa-retweet:before {
    content: "\f079";
  }
  .fa-shopping-cart:before {
    content: "\f07a";
  }
  .fa-folder:before {
    content: "\f07b";
  }
  .fa-folder-open:before {
    content: "\f07c";
  }
  .fa-arrows-v:before {
    content: "\f07d";
  }
  .fa-arrows-h:before {
    content: "\f07e";
  }
  .fa-bar-chart-o:before {
    content: "\f080";
  }
  .fa-twitter-square:before {
    content: "\f081";
  }
  .fa-facebook-square:before {
    content: "\f082";
  }
  .fa-camera-retro:before {
    content: "\f083";
  }
  .fa-key:before {
    content: "\f084";
  }
  .fa-gears:before,
  .fa-cogs:before {
    content: "\f085";
  }
  .fa-comments:before {
    content: "\f086";
  }
  .fa-thumbs-o-up:before {
    content: "\f087";
  }
  .fa-thumbs-o-down:before {
    content: "\f088";
  }
  .fa-star-half:before {
    content: "\f089";
  }
  .fa-heart-o:before {
    content: "\f08a";
  }
  .fa-sign-out:before {
    content: "\f08b";
  }
  .fa-linkedin-square:before {
    content: "\f08c";
  }
  .fa-thumb-tack:before {
    content: "\f08d";
  }
  .fa-external-link:before {
    content: "\f08e";
  }
  .fa-sign-in:before {
    content: "\f090";
  }
  .fa-trophy:before {
    content: "\f091";
  }
  .fa-github-square:before {
    content: "\f092";
  }
  .fa-upload:before {
    content: "\f093";
  }
  .fa-lemon-o:before {
    content: "\f094";
  }
  .fa-phone:before {
    content: "\f095";
  }
  .fa-square-o:before {
    content: "\f096";
  }
  .fa-bookmark-o:before {
    content: "\f097";
  }
  .fa-phone-square:before {
    content: "\f098";
  }
  .fa-twitter:before {
    content: "\f099";
  }
  .fa-facebook:before {
    content: "\f09a";
  }
  .fa-github:before {
    content: "\f09b";
  }
  .fa-unlock:before {
    content: "\f09c";
  }
  .fa-credit-card:before {
    content: "\f09d";
  }
  .fa-rss:before {
    content: "\f09e";
  }
  .fa-hdd-o:before {
    content: "\f0a0";
  }
  .fa-bullhorn:before {
    content: "\f0a1";
  }
  .fa-bell:before {
    content: "\f0f3";
  }
  .fa-certificate:before {
    content: "\f0a3";
  }
  .fa-hand-o-right:before {
    content: "\f0a4";
  }
  .fa-hand-o-left:before {
    content: "\f0a5";
  }
  .fa-hand-o-up:before {
    content: "\f0a6";
  }
  .fa-hand-o-down:before {
    content: "\f0a7";
  }
  .fa-arrow-circle-left:before {
    content: "\f0a8";
  }
  .fa-arrow-circle-right:before {
    content: "\f0a9";
  }
  .fa-arrow-circle-up:before {
    content: "\f0aa";
  }
  .fa-arrow-circle-down:before {
    content: "\f0ab";
  }
  .fa-globe:before {
    content: "\f0ac";
  }
  .fa-wrench:before {
    content: "\f0ad";
  }
  .fa-tasks:before {
    content: "\f0ae";
  }
  .fa-filter:before {
    content: "\f0b0";
  }
  .fa-briefcase:before {
    content: "\f0b1";
  }
  .fa-arrows-alt:before {
    content: "\f0b2";
  }
  .fa-group:before,
  .fa-users:before {
    content: "\f0c0";
  }
  .fa-chain:before,
  .fa-link:before {
    content: "\f0c1";
  }
  .fa-cloud:before {
    content: "\f0c2";
  }
  .fa-flask:before {
    content: "\f0c3";
  }
  .fa-cut:before,
  .fa-scissors:before {
    content: "\f0c4";
  }
  .fa-copy:before,
  .fa-files-o:before {
    content: "\f0c5";
  }
  .fa-paperclip:before {
    content: "\f0c6";
  }
  .fa-save:before,
  .fa-floppy-o:before {
    content: "\f0c7";
  }
  .fa-square:before {
    content: "\f0c8";
  }
  .fa-bars:before {
    content: "\f0c9";
  }
  .fa-list-ul:before {
    content: "\f0ca";
  }
  .fa-list-ol:before {
    content: "\f0cb";
  }
  .fa-strikethrough:before {
    content: "\f0cc";
  }
  .fa-underline:before {
    content: "\f0cd";
  }
  .fa-table:before {
    content: "\f0ce";
  }
  .fa-magic:before {
    content: "\f0d0";
  }
  .fa-truck:before {
    content: "\f0d1";
  }
  .fa-pinterest:before {
    content: "\f0d2";
  }
  .fa-pinterest-square:before {
    content: "\f0d3";
  }
  .fa-google-plus-square:before {
    content: "\f0d4";
  }
  .fa-google-plus:before {
    content: "\f0d5";
  }
  .fa-money:before {
    content: "\f0d6";
  }
  .fa-caret-down:before {
    content: "\f0d7";
  }
  .fa-caret-up:before {
    content: "\f0d8";
  }
  .fa-caret-left:before {
    content: "\f0d9";
  }
  .fa-caret-right:before {
    content: "\f0da";
  }
  .fa-columns:before {
    content: "\f0db";
  }
  .fa-unsorted:before,
  .fa-sort:before {
    content: "\f0dc";
  }
  .fa-sort-down:before,
  .fa-sort-asc:before {
    content: "\f0dd";
  }
  .fa-sort-up:before,
  .fa-sort-desc:before {
    content: "\f0de";
  }
  .fa-envelope:before {
    content: "\f0e0";
  }
  .fa-linkedin:before {
    content: "\f0e1";
  }
  .fa-rotate-left:before,
  .fa-undo:before {
    content: "\f0e2";
  }
  .fa-legal:before,
  .fa-gavel:before {
    content: "\f0e3";
  }
  .fa-dashboard:before,
  .fa-tachometer:before {
    content: "\f0e4";
  }
  .fa-comment-o:before {
    content: "\f0e5";
  }
  .fa-comments-o:before {
    content: "\f0e6";
  }
  .fa-flash:before,
  .fa-bolt:before {
    content: "\f0e7";
  }
  .fa-sitemap:before {
    content: "\f0e8";
  }
  .fa-umbrella:before {
    content: "\f0e9";
  }
  .fa-paste:before,
  .fa-clipboard:before {
    content: "\f0ea";
  }
  .fa-lightbulb-o:before {
    content: "\f0eb";
  }
  .fa-exchange:before {
    content: "\f0ec";
  }
  .fa-cloud-download:before {
    content: "\f0ed";
  }
  .fa-cloud-upload:before {
    content: "\f0ee";
  }
  .fa-user-md:before {
    content: "\f0f0";
  }
  .fa-stethoscope:before {
    content: "\f0f1";
  }
  .fa-suitcase:before {
    content: "\f0f2";
  }
  .fa-bell-o:before {
    content: "\f0a2";
  }
  .fa-coffee:before {
    content: "\f0f4";
  }
  .fa-cutlery:before {
    content: "\f0f5";
  }
  .fa-file-text-o:before {
    content: "\f0f6";
  }
  .fa-building-o:before {
    content: "\f0f7";
  }
  .fa-hospital-o:before {
    content: "\f0f8";
  }
  .fa-ambulance:before {
    content: "\f0f9";
  }
  .fa-medkit:before {
    content: "\f0fa";
  }
  .fa-fighter-jet:before {
    content: "\f0fb";
  }
  .fa-beer:before {
    content: "\f0fc";
  }
  .fa-h-square:before {
    content: "\f0fd";
  }
  .fa-plus-square:before {
    content: "\f0fe";
  }
  .fa-angle-double-left:before {
    content: "\f100";
  }
  .fa-angle-double-right:before {
    content: "\f101";
  }
  .fa-angle-double-up:before {
    content: "\f102";
  }
  .fa-angle-double-down:before {
    content: "\f103";
  }
  .fa-angle-left:before {
    content: "\f104";
  }
  .fa-angle-right:before {
    content: "\f105";
  }
  .fa-angle-up:before {
    content: "\f106";
  }
  .fa-angle-down:before {
    content: "\f107";
  }
  .fa-desktop:before {
    content: "\f108";
  }
  .fa-laptop:before {
    content: "\f109";
  }
  .fa-tablet:before {
    content: "\f10a";
  }
  .fa-mobile-phone:before,
  .fa-mobile:before {
    content: "\f10b";
  }
  .fa-circle-o:before {
    content: "\f10c";
  }
  .fa-quote-left:before {
    content: "\f10d";
  }
  .fa-quote-right:before {
    content: "\f10e";
  }
  .fa-spinner:before {
    content: "\f110";
  }
  .fa-circle:before {
    content: "\f111";
  }
  .fa-mail-reply:before,
  .fa-reply:before {
    content: "\f112";
  }
  .fa-github-alt:before {
    content: "\f113";
  }
  .fa-folder-o:before {
    content: "\f114";
  }
  .fa-folder-open-o:before {
    content: "\f115";
  }
  .fa-smile-o:before {
    content: "\f118";
  }
  .fa-frown-o:before {
    content: "\f119";
  }
  .fa-meh-o:before {
    content: "\f11a";
  }
  .fa-gamepad:before {
    content: "\f11b";
  }
  .fa-keyboard-o:before {
    content: "\f11c";
  }
  .fa-flag-o:before {
    content: "\f11d";
  }
  .fa-flag-checkered:before {
    content: "\f11e";
  }
  .fa-terminal:before {
    content: "\f120";
  }
  .fa-code:before {
    content: "\f121";
  }
  .fa-reply-all:before {
    content: "\f122";
  }
  .fa-mail-reply-all:before {
    content: "\f122";
  }
  .fa-star-half-empty:before,
  .fa-star-half-full:before,
  .fa-star-half-o:before {
    content: "\f123";
  }
  .fa-location-arrow:before {
    content: "\f124";
  }
  .fa-crop:before {
    content: "\f125";
  }
  .fa-code-fork:before {
    content: "\f126";
  }
  .fa-unlink:before,
  .fa-chain-broken:before {
    content: "\f127";
  }
  .fa-question:before {
    content: "\f128";
  }
  .fa-info:before {
    content: "\f129";
  }
  .fa-exclamation:before {
    content: "\f12a";
  }
  .fa-superscript:before {
    content: "\f12b";
  }
  .fa-subscript:before {
    content: "\f12c";
  }
  .fa-eraser:before {
    content: "\f12d";
  }
  .fa-puzzle-piece:before {
    content: "\f12e";
  }
  .fa-microphone:before {
    content: "\f130";
  }
  .fa-microphone-slash:before {
    content: "\f131";
  }
  .fa-shield:before {
    content: "\f132";
  }
  .fa-calendar-o:before {
    content: "\f133";
  }
  .fa-fire-extinguisher:before {
    content: "\f134";
  }
  .fa-rocket:before {
    content: "\f135";
  }
  .fa-maxcdn:before {
    content: "\f136";
  }
  .fa-chevron-circle-left:before {
    content: "\f137";
  }
  .fa-chevron-circle-right:before {
    content: "\f138";
  }
  .fa-chevron-circle-up:before {
    content: "\f139";
  }
  .fa-chevron-circle-down:before {
    content: "\f13a";
  }
  .fa-html5:before {
    content: "\f13b";
  }
  .fa-css3:before {
    content: "\f13c";
  }
  .fa-anchor:before {
    content: "\f13d";
  }
  .fa-unlock-alt:before {
    content: "\f13e";
  }
  .fa-bullseye:before {
    content: "\f140";
  }
  .fa-ellipsis-h:before {
    content: "\f141";
  }
  .fa-ellipsis-v:before {
    content: "\f142";
  }
  .fa-rss-square:before {
    content: "\f143";
  }
  .fa-play-circle:before {
    content: "\f144";
  }
  .fa-ticket:before {
    content: "\f145";
  }
  .fa-minus-square:before {
    content: "\f146";
  }
  .fa-minus-square-o:before {
    content: "\f147";
  }
  .fa-level-up:before {
    content: "\f148";
  }
  .fa-level-down:before {
    content: "\f149";
  }
  .fa-check-square:before {
    content: "\f14a";
  }
  .fa-pencil-square:before {
    content: "\f14b";
  }
  .fa-external-link-square:before {
    content: "\f14c";
  }
  .fa-share-square:before {
    content: "\f14d";
  }
  .fa-compass:before {
    content: "\f14e";
  }
  .fa-toggle-down:before,
  .fa-caret-square-o-down:before {
    content: "\f150";
  }
  .fa-toggle-up:before,
  .fa-caret-square-o-up:before {
    content: "\f151";
  }
  .fa-toggle-right:before,
  .fa-caret-square-o-right:before {
    content: "\f152";
  }
  .fa-euro:before,
  .fa-eur:before {
    content: "\f153";
  }
  .fa-gbp:before {
    content: "\f154";
  }
  .fa-dollar:before,
  .fa-usd:before {
    content: "\f155";
  }
  .fa-rupee:before,
  .fa-inr:before {
    content: "\f156";
  }
  .fa-cny:before,
  .fa-rmb:before,
  .fa-yen:before,
  .fa-jpy:before {
    content: "\f157";
  }
  .fa-ruble:before,
  .fa-rouble:before,
  .fa-rub:before {
    content: "\f158";
  }
  .fa-won:before,
  .fa-krw:before {
    content: "\f159";
  }
  .fa-bitcoin:before,
  .fa-btc:before {
    content: "\f15a";
  }
  .fa-file:before {
    content: "\f15b";
  }
  .fa-file-text:before {
    content: "\f15c";
  }
  .fa-sort-alpha-asc:before {
    content: "\f15d";
  }
  .fa-sort-alpha-desc:before {
    content: "\f15e";
  }
  .fa-sort-amount-asc:before {
    content: "\f160";
  }
  .fa-sort-amount-desc:before {
    content: "\f161";
  }
  .fa-sort-numeric-asc:before {
    content: "\f162";
  }
  .fa-sort-numeric-desc:before {
    content: "\f163";
  }
  .fa-thumbs-up:before {
    content: "\f164";
  }
  .fa-thumbs-down:before {
    content: "\f165";
  }
  .fa-youtube-square:before {
    content: "\f166";
  }
  .fa-youtube:before {
    content: "\f167";
  }
  .fa-xing:before {
    content: "\f168";
  }
  .fa-xing-square:before {
    content: "\f169";
  }
  .fa-youtube-play:before {
    content: "\f16a";
  }
  .fa-dropbox:before {
    content: "\f16b";
  }
  .fa-stack-overflow:before {
    content: "\f16c";
  }
  .fa-instagram:before {
    content: "\f16d";
  }
  .fa-flickr:before {
    content: "\f16e";
  }
  .fa-adn:before {
    content: "\f170";
  }
  .fa-bitbucket:before {
    content: "\f171";
  }
  .fa-bitbucket-square:before {
    content: "\f172";
  }
  .fa-tumblr:before {
    content: "\f173";
  }
  .fa-tumblr-square:before {
    content: "\f174";
  }
  .fa-long-arrow-down:before {
    content: "\f175";
  }
  .fa-long-arrow-up:before {
    content: "\f176";
  }
  .fa-long-arrow-left:before {
    content: "\f177";
  }
  .fa-long-arrow-right:before {
    content: "\f178";
  }
  .fa-apple:before {
    content: "\f179";
  }
  .fa-windows:before {
    content: "\f17a";
  }
  .fa-android:before {
    content: "\f17b";
  }
  .fa-linux:before {
    content: "\f17c";
  }
  .fa-dribbble:before {
    content: "\f17d";
  }
  .fa-skype:before {
    content: "\f17e";
  }
  .fa-foursquare:before {
    content: "\f180";
  }
  .fa-trello:before {
    content: "\f181";
  }
  .fa-female:before {
    content: "\f182";
  }
  .fa-male:before {
    content: "\f183";
  }
  .fa-gittip:before {
    content: "\f184";
  }
  .fa-sun-o:before {
    content: "\f185";
  }
  .fa-moon-o:before {
    content: "\f186";
  }
  .fa-archive:before {
    content: "\f187";
  }
  .fa-bug:before {
    content: "\f188";
  }
  .fa-vk:before {
    content: "\f189";
  }
  .fa-weibo:before {
    content: "\f18a";
  }
  .fa-renren:before {
    content: "\f18b";
  }
  .fa-pagelines:before {
    content: "\f18c";
  }
  .fa-stack-exchange:before {
    content: "\f18d";
  }
  .fa-arrow-circle-o-right:before {
    content: "\f18e";
  }
  .fa-arrow-circle-o-left:before {
    content: "\f190";
  }
  .fa-toggle-left:before,
  .fa-caret-square-o-left:before {
    content: "\f191";
  }
  .fa-dot-circle-o:before {
    content: "\f192";
  }
  .fa-wheelchair:before {
    content: "\f193";
  }
  .fa-vimeo-square:before {
    content: "\f194";
  }
  .fa-turkish-lira:before,
  .fa-try:before {
    content: "\f195";
  }
  .fa-plus-square-o:before {
    content: "\f196";
  }
  
 
@import url('http://fonts.googleapis.com/css?family=Noto+Serif:400,400italic,700|Open+Sans:400,600,700'); 
@import url('font-awesome.css');  
@import url('animate.css');

body {
	font-family:'Open Sans', Arial, sans-serif;
	font-size:14px;
	font-weight:300;
	line-height:1.6em;
	color:#656565;
}

a:active {
	outline:0;
}

.clear {
	clear:both;
}

h1,h2, h3, h4, h5, h6 {
	font-family:'Open Sans', Arial, sans-serif;
	font-weight:700;
	line-height:1.1em;
	color:#333;
	margin-bottom: 20px;
}
 
.container {
	padding:0 20px 0 20px;
	position:relative;
}

#wrapper{
	width:100%;
	margin:0;	
	padding:0;
}

.row,.row-fluid {
	margin-bottom:30px;
}

.row .row,.row-fluid .row-fluid{
	margin-bottom:30px;
}

.row.nomargin,.row-fluid.nomargin {
	margin-bottom:0;
}

img.img-polaroid {
	margin:0 0 20px 0;
}
.img-box {
	max-width:100%;
}
/*  Header
==================================== */
 
header .navbar {
    margin-bottom: 0;
}

.navbar-default {
    border: none;
}

.navbar-brand {
    color: #222;
	text-transform: uppercase;
    font-size: 24px;
    font-weight: 700;
    line-height: 1em;
	letter-spacing: -1px;
    margin-top: 13px;
    padding: 0 0 0 15px;
}
.navbar-default .navbar-brand{
color: #61B331;
}

header .navbar-collapse  ul.navbar-nav {
    float: right;
    margin-right: 0;
}

header .navbar-default{
    background-color: #FFFFFF;
}

header .nav li a:hover,
header .nav li a:focus,
header .nav li.active a,
header .nav li.active a:hover,
header .nav li a.dropdown-toggle:hover,
header .nav li a.dropdown-toggle:focus,
header .nav li.active ul.dropdown-menu li a:hover,
header .nav li.active ul.dropdown-menu li.active a{
    -webkit-transition: all .3s ease;
    -moz-transition: all .3s ease;
    -ms-transition: all .3s ease;
    -o-transition: all .3s ease;
    transition: all .3s ease;
}


header .navbar-default .navbar-nav > .open > a,
header .navbar-default .navbar-nav > .open > a:hover,
header .navbar-default .navbar-nav > .open > a:focus {
    -webkit-transition: all .3s ease;
    -moz-transition: all .3s ease;
    -ms-transition: all .3s ease;
    -o-transition: all .3s ease;
    transition: all .3s ease;
}


header .navbar {
    min-height: 70px; 
	padding:18px 0;
}

header .navbar-nav > li  {
    padding-bottom: 12px;
    padding-top: 12px;
}

header  .navbar-nav > li > a {
    padding-bottom: 6px;
    padding-top: 5px;
    margin-left: 2px;
    line-height: 30px;
	font-weight: 700;
    -webkit-transition: all .3s ease;
    -moz-transition: all .3s ease;
    -ms-transition: all .3s ease;
    -o-transition: all .3s ease;
    transition: all .3s ease;
}


.dropdown-menu li a:hover {
    color: #fff !important;
}

header .nav .caret {
    border-bottom-color: #f5f5f5;
    border-top-color: #f5f5f5;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  background-color: #fff;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color:  #fff;
}	
	

.dropdown-menu  {
    box-shadow: none;
    border-radius: 0;
	border: none;
}

.dropdown-menu li:last-child  {
	padding-bottom: 0 !important;
	margin-bottom: 0;
}

header .nav li .dropdown-menu  {
   padding: 0;
}

header .nav li .dropdown-menu li a {
   line-height: 28px;
   padding: 3px 12px;
}
.item-thumbs img {
    margin-bottom: 15px;
}
.flex-control-paging li a.flex-active {
    background: #000;
    background: rgb(255, 255, 255);
    cursor: default;
}
.flex-control-paging li a {
    width: 30px;
    height: 11px;
    display: block;
    background: #666;
    background: rgba(0,0,0,0.5);
    cursor: pointer;
    text-indent: -9999px;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    -o-border-radius: 20px;
    border-radius: 20px;
    box-shadow: inset 0 0 3px rgba(0,0,0,0.3);
    
	}
	.panel-title>a {
    color: inherit;
    color: #FFF;
}
.panel-group .panel-heading+.panel-collapse .panel-body {
    border-top: 1px solid #ddd;
    color: #fff;
    background-color: #9C9C9C;
}
/* --- menu --- */

header .navigation {
	float:right;
}

header ul.nav li {
	border:none;
	margin:0;
}

header ul.nav li a {	
	font-size:12px;
	border:none;
	font-weight:700;
	text-transform:uppercase;
}

header ul.nav li ul li a {	
	font-size:12px;
	border:none;
	font-weight:300;
	text-transform:uppercase;
}


.navbar .nav > li > a {
  color: #848484;
  text-shadow: none;
  border: 1px solid rgba(255, 255, 255, 0) !important;
}

.navbar .nav a:hover {
	background:none;
	color: #14A085 !important;
}

.navbar .nav > .active > a,.navbar .nav > .active > a:hover {
	background:none;
	font-weight:700;
}

.navbar .nav > .active > a:active,.navbar .nav > .active > a:focus {
	background:none;
	outline:0;
	font-weight:700;
}

.navbar .nav li .dropdown-menu {
	z-index:2000;
}

header ul.nav li ul {
	margin-top:1px;
}
header ul.nav li ul li ul {
	margin:1px 0 0 1px;
}
.dropdown-menu .dropdown i {
	position:absolute;
	right:0;
	margin-top:3px;
	padding-left:20px;
}

.navbar .nav > li > .dropdown-menu:before {
  display: inline-block;
  border-right: none;
  border-bottom: none;
  border-left: none;
  border-bottom-color: none;
  content:none;
}
.navbar-default .navbar-nav>.active>a, .navbar-default .navbar-nav>.active>a:hover, .navbar-default .navbar-nav>.active>a:focus {
color: #14A085;
}


ul.nav li.dropdown a {
	z-index:1000;
	display:block;
}

 select.selectmenu {
	display:none;
}
.pageTitle{
color: #fff;
margin: 30px 0 3px;
display: inline-block;
}
 
#featured{
	width: 100%;
	background:#000;
	position:relative;
	margin:0;
	padding:0;
}

/*  Sliders
==================================== */
/* --- flexslider --- */

#featured .flexslider {
	padding:0;  
	background: #fff; 
	position: relative; 
	zoom: 1;
}
.flex-direction-nav .flex-prev{
left:0px; 
}
.flex-direction-nav .flex-next{ 
right:0px;
}
.flex-caption {zoom:0;
  color: #1C1D21;
  margin: 0 auto;
  padding: 1px;
  position: absolute;
  vertical-align: bottom;
  text-align: center;
  background-color: rgba(255, 255, 255, 0.26);
  bottom: 5%;
  display: block;
  left: 0;
  right: 0;
  }
.flex-caption h3 {color: #fff; letter-spacing: 1px; margin-bottom: 8px; text-transform: uppercase;}
.flex-caption p {margin: 0 0 15px;}
.skill-home{
margin-bottom:50px;
}
.c1{
border: #ed5441 1px solid;
background:#ed5441;
}
.c2{
border: #D867B2 1px solid;
background: #D867B2;
}
.c3{
border: #61B331 1px solid;
background: #4BC567;
}
.c4{
border: #609cec 1px solid;
background: #26AFF0;
}
.skill-home .icons {
padding: 33px 0 0 0;
width: 100%;
height: 178px;
color: rgb(255, 255, 255);
font-size: 42px;
font-size: 76px; 
text-align: center;
-ms-border-radius: 50%;
-moz-border-radius: 50%;
-webkit-border-radius: 50%;
border-radius: 0;
display: inline-table;
}
.skill-home h2 {
padding-top: 20px;
font-size: 36px;
font-weight: 700;
} 
.testimonial-solid {
padding: 50px 0 60px 0;
margin: 0 0 0 0;
background: #EFEFEF;
text-align: center;
}
.testi-icon-area {
text-align: center;
position: absolute;
top: -84px;
margin: 0 auto; 
width: 100%;
color: #000;}
.testi-icon-area .quote {
padding: 15px 0 0 0;
margin: 0 0 0 0;
background: #ffffff;
text-align: center;
color: #26AFF0;
display: inline-table;
width: 70px;
height: 70px;
-ms-border-radius: 50%;
-moz-border-radius: 50%;
-webkit-border-radius: 50%;
border-radius: 0;
font-size: 42px; 
border: 1px solid #26AFF0;
display: none;}

.testi-icon-area .carousel-inner { 
margin: 20px 0;
}
.carousel-indicators {
bottom: -30px;
}
.team-member {
    text-align: center;
    background-color: #F9F9F9;
    padding-bottom: 15px;
}
.fancybox-title-inside-wrap {
    padding: 3px 30px 6px;
    background: #292929;
}

.item_introtext {
    background-color: rgba(254, 254, 255, 0.66);
    margin: 0 auto;
    display: inline-block;
    padding: 25px;
}
.item_introtext span {
    font-size: 20px;
    display: block; 
    font-weight: bold;
}
.item_introtext strong {
    font-size: 50px;
    display: block;
    padding: 14px 0 30px;
}
.item_introtext p {
    font-size: 20px !important;
    color: #1C1D21;
    font-weight: bold;
}

.form-control{
border-radius:0;
}


/* Testimonial
----------------------------------*/
.testimonial-area {
padding: 0 0 0 0;
margin:0;
background: url(../img/low-poly01.jpg) fixed center center;
background-size: cover;
-webkit-background-size: cover;
-moz-background-size: cover;
-ms-background-size: cover;
color: red;}
.testimonial-solid p {
color: #1F1F1F;
font-size: 16px;
line-height: 30px;
font-style: italic;
} 
section.callaction {
	background:#fff;
	padding:50px 0 0 0;
}



/* Content
==================================== */

#content {
	position:relative;
	background:#fff;
	padding:50px 0 0px 0;
}

#content img {
	max-width:100%;
	height:auto;
}
 
.cta-text {
	text-align: center;
	margin-top:10px;
}


.big-cta .cta {
	margin-top:10px;
}
 
.box {
	width: 100%;
}
.box-gray  {
	background: #f8f8f8;
	padding: 20px 20px 30px;
}
.box-gray  h4,.box-gray  i {
	margin-bottom: 20px;
}
.box-bottom {
	padding: 20px 0;
	text-align: center;
}
.box-bottom a {
	color: #fff;
	font-weight: 700;
}
.box-bottom a:hover {
	color: #eee;
	text-decoration: none;
}


/* Bottom
==================================== */

#bottom {
	background:#fcfcfc;
	padding:50px 0 0;

}
/* twitter */
#twitter-wrapper {
    text-align: center;
    width: 70%;
    margin: 0 auto;
}
#twitter em {
    font-style: normal;
    font-size: 13px;
}

#twitter em.twitterTime a {
	font-weight:600;
}

#twitter ul {
    padding: 0;
	list-style:none;
}
#twitter ul li {
    font-size: 20px;
    line-height: 1.6em;
    font-weight: 300;
    margin-bottom: 20px;
    position: relative;
    word-break: break-word;
}


/* page headline
==================================== */

#inner-headline{
	background: #14A085;
	position:relative;
	margin:0;
	padding:0;
	color:#fefefe;
	/* margin: 15px; */
	border-top: 10px solid #11967C;
}


#inner-headline .inner-heading h2 {
	color:#fff;
	margin:20px 0 0 0;
}

/* --- breadcrumbs --- */
#inner-headline ul.breadcrumb {
	margin:30px 0 0;
	float:left;
}

#inner-headline ul.breadcrumb li {
	margin-bottom:0;
	padding-bottom:0;
}
#inner-headline ul.breadcrumb li {
	font-size:13px;
	color:#fff;
}

#inner-headline ul.breadcrumb li i{
	color:#dedede;
}

#inner-headline ul.breadcrumb li a {
	color:#fff;
}

ul.breadcrumb li a:hover {
	text-decoration:none;
}

/* Forms
============================= */

/* --- contact form  ---- */
form#contactform input[type="text"] {
  width: 100%;
  border: 1px solid #f5f5f5;
  min-height: 40px;
  padding-left:20px;
  font-size:13px;
  padding-right:20px;
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;

}

form#contactform textarea {
border: 1px solid #f5f5f5;
  width: 100%;
  padding-left:20px;
  padding-top:10px;
  font-size:13px;
  padding-right:20px;
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;

}

form#contactform .validation {
	font-size:11px;
}

#sendmessage {
	border:1px solid #e6e6e6;
	background:#f6f6f6;
	display:none;
	text-align:center;
	padding:15px 12px 15px 65px;
	margin:10px 0;
	font-weight:600;
	margin-bottom:30px;

}

#sendmessage.show,.show  {
	display:block;
}
 
form#commentform input[type="text"] {
  width: 100%;
  min-height: 40px;
  padding-left:20px;
  font-size:13px;
  padding-right:20px;
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
	-webkit-border-radius: 2px 2px 2px 2px;
		-moz-border-radius: 2px 2px 2px 2px;
			border-radius: 2px 2px 2px 2px;

}

form#commentform textarea {
  width: 100%;
  padding-left:20px;
  padding-top:10px;
  font-size:13px;
  padding-right:20px;
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
	-webkit-border-radius: 2px 2px 2px 2px;
		-moz-border-radius: 2px 2px 2px 2px;
			border-radius: 2px 2px 2px 2px;
}


/* --- search form --- */
.search{
	float:right;
	margin:35px 0 0;
	padding-bottom:0;
}

#inner-headline form.input-append {
	margin:0;
	padding:0;
}



/*  Portfolio
================================ */

.work-nav #filters {
	margin: 0;
	padding: 0;
	list-style: none;
}

.work-nav #filters li {
	margin: 0 10px 30px 0;
	padding: 0;
	float:left;
}

.work-nav #filters li a {
	color: #7F8289;
	font-size: 16px;
	display: block;	
}

.work-nav #filters li a:hover {

}

.work-nav #filters li a.selected {
	color: #DE5E60;
}

#thumbs {
	margin: 0;
	padding: 0;	
}

#thumbs li {
	list-style-type: none;
}

.item-thumbs {
	position: relative;
	overflow: hidden;
	margin-bottom: 30px;
	cursor: pointer;
}

.item-thumbs a + img {
	width: 100%;	
}

.item-thumbs .hover-wrap {
	position: absolute;
	display: block;
	width: 100%;
	height: 100%;
	
	opacity: 0;
	filter: alpha(opacity=0);
	
	-webkit-transition: all 450ms ease-out 0s;	
	   -moz-transition: all 450ms ease-out 0s;
		 -o-transition: all 450ms ease-out 0s;
		    transition: all 450ms ease-out 0s;
		  
	-webkit-transform: rotateY(180deg) scale(0.5,0.5);
	   -moz-transform: rotateY(180deg) scale(0.5,0.5);
		-ms-transform: rotateY(180deg) scale(0.5,0.5);
		 -o-transform: rotateY(180deg) scale(0.5,0.5);
			transform: rotateY(180deg) scale(0.5,0.5);	
}

.item-thumbs:hover .hover-wrap,
.item-thumbs.active .hover-wrap {
	opacity: 1;
	filter: alpha(opacity=100);
	
	-webkit-transform: rotateY(0deg) scale(1,1);
	   -moz-transform: rotateY(0deg) scale(1,1);
		-ms-transform: rotateY(0deg) scale(1,1);
		 -o-transform: rotateY(0deg) scale(1,1);
		    transform: rotateY(0deg) scale(1,1);
}

.item-thumbs .hover-wrap .overlay-img {
	position: absolute;
	width: 90%;
	height: 91%;
	opacity: 0.50;
	filter: alpha(opacity=80);
	background: #14A085;
}

.item-thumbs .hover-wrap .overlay-img-thumb {
	position: absolute;
	border-radius: 60px;
	top: 50%;
	left: 45%;
	margin: -16px 0 0 -16px;
	color: #fff;
	font-size: 32px;
	line-height: 1em;	
	opacity: 1;
	filter: alpha(opacity=100);
}
 
ul.portfolio-categ{
	margin:10px 0 30px 0;
	padding:0;
	float:left;
	list-style:none;
}

ul.portfolio-categ li{
margin: 0; 
float: left;
list-style: none;
font-size: 13px;
font-weight: 600;
border: 1px solid #D5D5D5;
margin-right: 15px;
}

ul.portfolio-categ li a{
	display:block;
	padding: 8px 20px;
	color: #14A085;
}
ul.portfolio-categ li.active{

border: 1px solid #D7D8D6;

background-color: #EAEAEA;
}
ul.portfolio-categ li.active a:hover, ul.portfolio-categ li a:hover,ul.portfolio-categ li a:focus,ul.portfolio-categ li a:active {
	text-decoration:none;
	outline:0; 
}
  #accordion-alt3 .panel-heading h4 {
font-size: 13px;
line-height: 28px;
color: #6B6B6B;}
.panel .panel-heading h4 {
font-weight: 400;
}
.panel-title {
margin-top: 0;
margin-bottom: 0;
font-size: 15px;
color: inherit;
}
.panel-group .panel {
margin-bottom: 0;
border-radius: 2px;
}
.panel {
margin-bottom: 18px;
background-color: #B9B9B9;
border: 1px solid transparent;
border-radius: 2px;
-webkit-box-shadow: 0 1px 1px rgba(0,0,0,0.05);
box-shadow: 0 1px 1px rgba(0,0,0,0.05);
}
#accordion-alt3 .panel-heading h4 a i {
font-size: 13px;
line-height: 18px;
width: 18px;
height: 18px;
margin-right: 5px;
color: #fff;
text-align: center;
border-radius: 50%;
margin-left: 6px;
}  
.progress.pb-sm {
height: 6px!important;
}
.progress {
box-shadow: inset 0 0 2px rgba(0,0,0,.1);
}
.progress {
overflow: hidden;
height: 18px;
margin-bottom: 18px;
background-color: #f5f5f5;
border-radius: 2px;
-webkit-box-shadow: inset 0 1px 2px rgba(0,0,0,0.1);
box-shadow: inset 0 1px 2px rgba(0,0,0,0.1);
}
.progress .progress-bar.progress-bar-red {
background: #ed5441;
} 
.progress .progress-bar.progress-bar-green {
background: #51d466;
}
.progress .progress-bar.progress-bar-lblue {
background: #32c8de;
}
/* --- portfolio detail --- */
.top-wrapper {
	margin-bottom:20px;
}
.info-blocks {
margin-bottom: 15px;
}
.info-blocks i.icon-info-blocks {
float: left;
color: #318FCF;
font-size: 30px;
min-width: 50px;
margin-top: 6px;
text-align: center;
background-color: #EFEFEF;
padding: 15px;
}
.info-blocks .info-blocks-in {
padding: 0 10px;
overflow: hidden;
}
.info-blocks .info-blocks-in h3 {
color: #555;
font-size: 20px;
line-height: 28px;
margin:0px;
}
.info-blocks .info-blocks-in p {
font-size: 12px;
}
  
blockquote {
	font-size:16px;
	font-weight:400;
	font-family:'Noto Serif', serif;
	font-style:italic;
	padding-left:0;
	color:#a2a2a2;
	line-height:1.6em;
	border:none;
}

blockquote cite 							{ display:block; font-size:12px; color:#666; margin-top:10px; }
blockquote cite:before 					{ content:"\2014 \0020"; }
blockquote cite a,
blockquote cite a:visited,
blockquote cite a:visited 				{ color:#555; }

/* --- pullquotes --- */

.pullquote-left {
	display:block;
	color:#a2a2a2;
	font-family:'Noto Serif', serif;
	font-size:14px;
	line-height:1.6em;
	padding-left:20px;
}

.pullquote-right {
	display:block;
	color:#a2a2a2;
	font-family:'Noto Serif', serif;
	font-size:14px;
	line-height:1.6em;
	padding-right:20px;
}

/* --- button --- */
.btn{text-align: center;
background: #318CCA;
color: #fff;
border-radius: 0;padding: 10px 30px;}
.btn-theme {
	color: #fff;
}
.btn-theme:hover {
	color: #eee;
}

/* --- list style --- */

ul.general {
	list-style:none;
	margin-left:0;
}

ul.link-list{
	margin:0;
	padding:0;
	list-style:none;
}

ul.link-list li{
	margin:0;
	padding:2px 0 2px 0;
	list-style:none;
}
footer{
background: #14A085;
}
footer ul.link-list li a{
	color: #FFFFFF;
}
footer ul.link-list li a:hover {
	color: #E2E2E2;
}
/* --- Heading style --- */

h4.heading {
	font-weight:700;
}

.heading { margin-bottom: 30px; }

.heading {
	position: relative;
	
}


.widgetheading {
	width:100%;

	padding:0;
}

#bottom .widgetheading {
	position: relative;
	border-bottom: #e6e6e6 1px solid;
	padding-bottom: 9px;
}

aside .widgetheading {
	position: relative;
	border-bottom: #e9e9e9 1px solid;
	padding-bottom: 9px;
}

footer .widgetheading {
	position: relative;
}

footer .widget .social-network {
	position:relative;
}


#bottom .widget .widgetheading span, aside .widget .widgetheading span, footer .widget .widgetheading span {	
	position: absolute;
	width: 60px;
	height: 1px;
	bottom: -1px;
	right:0;

}
.box-area{
border: 1px solid #F3F3F3;
padding: 0 15px 12px;
padding-top: 41px;
margin-top: -42px;
text-align: left;
background-color: #F9F9F9;
position: relative;}
/* --- Map --- */
.map{
	position:relative;
	margin-top:-50px;
	margin-bottom:40px;
}

.map iframe{
	width:100%;
	height:450px;
	border:none;
}

.map-grid iframe{
	width:100%;
	height:350px;
	border:none;
	margin:0 0 -5px 0;
	padding:0;
}

 
ul.team-detail{
	margin:-10px 0 0 0;
	padding:0;
	list-style:none;
}

ul.team-detail li{
	border-bottom:1px dotted #e9e9e9;
	margin:0 0 15px 0;
	padding:0 0 15px 0;
	list-style:none;
}

ul.team-detail li label {
	font-size:13px;
}

ul.team-detail li h4, ul.team-detail li label{
	margin-bottom:0;
}

ul.team-detail li ul.social-network {
	border:none;
	margin:0;
	padding:0;
}

ul.team-detail li ul.social-network li {
	border:none;	
	margin:0;
}
ul.team-detail li ul.social-network li i {
	margin:0;
}

 
.pricing-title{
	background:#fff;
	text-align:center;
	padding:10px 0 10px 0;
}

.pricing-title h3{
	font-weight:600;
	margin-bottom:0;
}

.pricing-offer{
	background: #fcfcfc;
	text-align: center;
	padding:40px 0 40px 0;
	font-size:18px;
	border-top:1px solid #e6e6e6;
	border-bottom:1px solid #e6e6e6;
}

.pricing-box.activeItem .pricing-offer{
	color:#fff;
}

.pricing-offer strong{
	font-size:78px;
	line-height:89px;
}

.pricing-offer sup{
	font-size:28px;
}

.pricing-container{
	background: #fff;
	text-align:center;
	font-size:14px;
}

.pricing-container strong{
color:#353535;
}

.pricing-container ul{
	list-style:none;
	padding:0;
	margin:0;
}

.pricing-container ul li{
	border-bottom: 1px solid #F5F5F5;
list-style: none;
padding: 15px 0 15px 0;
margin: 0 0 0 0;
color: #222;
}

.pricing-action{
	margin:0;
	background: #fcfcfc;
	text-align:center;
	padding:20px 0 30px 0;
}

.pricing-wrapp{
	margin:0 auto;
	width:100%;
	background:#fd0000;
}
 .pricing-box-item {
border: 1px solid #F5F5F5;
	
background: #F9F9F9;
	position:relative;
	margin:0 0 20px 0;
	padding:0;
  -webkit-box-shadow: 0 2px 0 rgba(0,0,0,0.03);
  -moz-box-shadow: 0 2px 0 rgba(0,0,0,0.03);
  box-shadow: 0 2px 0 rgba(0,0,0,0.03);
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}

.pricing-box-item .pricing-heading {
	text-align: center;
	padding:0px 0 0px 0;
	display:block;
}
.pricing-box-item.activeItem .pricing-heading {
	text-align: center;
	padding:0px 0 1px 0;
	border-bottom:none;
	display:block;
	color:#fff;
}
.pricing-box-item.activeItem .pricing-heading h3 {
	 
}

.pricing-box-item .pricing-heading h3 strong {
	font-size: 20px;
	font-weight:700;
	letter-spacing:-1px;
}
.pricing-box-item .pricing-heading h3 {
	font-size: 35px;
	font-weight:300;
	letter-spacing:-1px;
}

.pricing-box-item .pricing-terms {
	text-align: center;
	display: block;
	overflow: hidden;
	padding: 11px 0 5px; 
}

.pricing-box-item .pricing-terms  h6 {
	font-style:italic;
	margin-top:10px;
	color: #14A085;
	font-size: 22px;
	font-family:'Noto Serif', serif;
}

.pricing-box-item .icon .price-circled {
    margin: 10px 10px 10px 0;
    display: inline-block !important;
    text-align: center !important;
    color: #fff;
    width: 68px;
    height: 68px;
	padding:12px;
    font-size: 16px;
	font-weight:700;
    line-height: 68px;
    text-shadow:none;
    cursor: pointer;
    background-color: #888;
    border-radius: 64px;
    -moz-border-radius: 64px;
    -webkit-border-radius: 64px;
}

.pricing-box-item  .pricing-action{
	margin:0;
	text-align:center;
	padding:30px 0 30px 0;
}
 
/* ===== Widgets ===== */

/* --- flickr --- */
.widget .flickr_badge {
	width:100%;
}
.widget .flickr_badge img { margin: 0 9px 20px 0; }

footer .widget .flickr_badge {
    width: 100%;
}
footer .widget .flickr_badge img {
    margin: 0 9px 20px 0;
}

.flickr_badge img {
    width: 50px;
    height: 50px;
    float: left;
	margin: 0 9px 20px 0;
}
 
/* --- Recent post widget --- */

.recent-post{
	margin:20px 0 0 0;
	padding:0;
	line-height:18px;
}

.recent-post h5 a:hover {
	text-decoration:none;
}

.recent-post .text h5 a {
	color:#353535;
}

  
footer{
	padding:50px 0 0 0;
	color:#f8f8f8;
}

footer a {
	color:#fff;
}

footer a:hover {
	color:#eee;
}

footer h1, footer h2, footer h3, footer h4, footer h5, footer h6{
	color:#fff;
}

footer address {
	line-height:1.6em;
	color: #FFFFFF;
}

footer h5 a:hover, footer a:hover {
	text-decoration:none;
}

ul.social-network {
	list-style:none;
	margin:0;
}

ul.social-network li {
	display:inline;
	margin: 0 5px;
}

#sub-footer{
	text-shadow:none;
	color:#f5f5f5;
	padding:0;
	padding-top:30px;
	margin:20px 0 0 0;
	background: #14A085;
}

#sub-footer p{
	margin:0;
	padding:0;
}

#sub-footer span{
	color:#f5f5f5;
}

.copyright {
	text-align:left;
	font-size:12px;
}

#sub-footer ul.social-network {
	float:right;
}

  

/* scroll to top */
.scrollup{
    position:fixed;
	width:32px;
	height:32px;
    bottom:0px;
    right:20px;
	background: #222;
	
}

a.scrollup {
	outline:0;
	text-align: center;
}

a.scrollup:hover,a.scrollup:active,a.scrollup:focus {
	opacity:1;
	text-decoration:none;
}
a.scrollup i {
	margin-top: 10px;
	color: #fff;
}
a.scrollup i:hover {
	text-decoration:none;
}



 
.absolute{
	position:absolute;
}

.relative{
	position:relative;
}

.aligncenter{
	text-align:center;
}

.aligncenter span{
	margin-left:0;
}

.floatright {
	float:right;
}

.floatleft {
	float:left;
}

.floatnone {
	float:none;
}

.aligncenter {
	text-align:center;
}
 
img.pull-left, .align-left{
	float:left;
	margin:0 15px 15px 0;
}

.widget img.pull-left {
	float:left;
	margin:0 15px 15px 0;
}

img.pull-right, .align-right {
	float:right;
	margin:0 0 15px 15px;
}

article img.pull-left, article .align-left{
	float:left;
	margin:5px 15px 15px 0;
}

article img.pull-right, article .align-right{
	float:right;
	margin:5px 0 15px 15px;
}
 ============================= */

.clear-marginbot{
	margin-bottom:0;
}

.marginbot10{
	margin-bottom:10px;
}
.marginbot20{
	margin-bottom:20px;
}
.marginbot30{
	margin-bottom:30px;
}
.marginbot40{
	margin-bottom:40px;
}

.clear-margintop{
	margin-top:0;
}

.margintop10{
	margin-top:10px;
}

.margintop20{
	margin-top:20px;
}

.margintop30{
	margin-top:30px;
}

.margintop40{
	margin-top:40px;
}


/*  Media queries 
============================= */

@media (min-width: 768px) and (max-width: 979px) {

	a.detail{
		background:none;
		width:100%;
	}


	
	footer .widget form  input#appendedInputButton {
		  display: block;
		  width: 91%;
		  -webkit-border-radius: 4px 4px 4px 4px;
			 -moz-border-radius: 4px 4px 4px 4px;
				  border-radius: 4px 4px 4px 4px;
	}
	
	footer .widget form  .input-append .btn {
		  display: block;
		  width: 100%;
		  padding-right: 0;
		  padding-left: 0;
		  -webkit-box-sizing: border-box;
			 -moz-box-sizing: border-box;
				  box-sizing: border-box;
				  margin-top:10px;
	}

	ul.related-folio li{
		width:156px;
		margin:0 20px 0 0;
	}	
}

@media (max-width: 767px) {

  body {
    padding-right: 0;
    padding-left: 0;
  }
	.navbar-brand {
		margin-top: 10px;
		border-bottom: none;
	}
	.navbar-header {
		margin-top: 20px;
		border-bottom: none;
	}
	
	.navbar-nav {
		border-top: none;
		float: none;
		width: 100%;
	}
.navbar .nav > .active > a, .navbar .nav > .active > a:hover {
background: none;
font-weight: 700;
color: #26AFF0;
}
	header .navbar-nav > li {
padding-bottom: 0px;
padding-top: 2px;
}
	header .nav li .dropdown-menu  {
		margin-top: 0;
	}

	.dropdown-menu {
	  position: absolute;
	  top: 0;
	  left: 40px;
	  z-index: 1000;
	  display: none;
	  float: left;
	  min-width: 160px;
	  padding: 5px 0;
	  margin: 2px 0 0;
	  font-size: 13px;
	  list-style: none;
	  background-color: #fff;
	  background-clip: padding-box;
	  border: 1px solid #f5f5f5;
	  border: 1px solid rgba(0, 0, 0, .15);
	  border-radius: 0;
	  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, .175);
			  box-shadow: 0 6px 12px rgba(0, 0, 0, .175);
	}
	

	
	.navbar-collapse.collapse  {
		border: none;
		overflow: hidden;
	}

	
	.box {
		border-bottom:1px solid #e9e9e9;
		padding-bottom:20px;
	}

	#featured .flexslider .slide-caption {
		width: 90%; 
		padding: 2%; 
		position: absolute; 
		left: 0; 
		bottom: -40px; 
	}


	#inner-headline .breadcrumb {
		float:left;
		clear:both;
		width:100%;
	}

	.breadcrumb > li {
		font-size:13px;
	}

	
	ul.portfolio li article a i.icon-48{
		width:20px;
		height:20px;
		font-size:16px;
		line-height:20px;
	}


	.left-sidebar{
		border-right:none;
		padding:0 0 0 0;
		border-bottom: 1px dotted #e6e6e6;
		padding-bottom:10px;
		margin-bottom:40px;
	}
	
	.right-sidebar{
		margin-top:30px;
		border-left:none;
		padding:0 0 0 0;
	}
	
	
	footer .col-lg-1, footer .col-lg-2, footer .col-lg-3, footer .col-lg-4, footer .col-lg-5, footer .col-lg-6, 
	footer .col-lg-7, footer .col-lg-8, footer .col-lg-9, footer .col-lg-10, footer .col-lg-11, footer .col-lg-12{
		margin-bottom:20px;
	}

	#sub-footer ul.social-network {
		float:left;
	}
	

	
  [class*="span"] {
		margin-bottom:20px;
  }

}

@media (max-width: 480px) {
	.bottom-article a.pull-right {
		float:left;
		margin-top:20px;
	}


	.search{
		float:left;
	}

	.flexslider .flex-caption {
		display:none;
	}


	.cta-text {
		margin:0 auto;
		text-align:center;	
	}
	
	ul.portfolio li article a i{
		width:20px;
		height:20px;
		font-size:14px;
	}


}

 
.box-area:before {
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: 0;
    background-color: red;
    content: '';
    position: absolute;
    top: 7px;
    left: -1px;
    width: 100%;
    height: 23px;
    background: #F9F9F9;
    -moz-transform: skewY(-3deg);
    -o-transform: skewY(-3deg);
    -ms-transform: skewY(-3deg);
    -webkit-transform: skewY(-3deg);
    transform: skewY(11deg);
    background-size: cover;
}
.box-area:after {
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: 0;
    background-color: red;
    content: '';
    position: absolute;
    top: 7px;
    left: 1px;
    width: 100%;
    height: 22px;
    background: #F9F9F9;
    -moz-transform: skewY(-3deg);
    -o-transform: skewY(-3deg);
    -ms-transform: skewY(-3deg);
    -webkit-transform: skewY(-3deg);
    transform: skewY(-11deg);
    background-size: cover;
}
.box-area h3 {
    margin-top: -16px;
    z-index: 12;
    position: relative;
}
.courses{
padding:50px 0
}
.carousel-indicators li {
    display: inline-block; 
    border: 1px solid #929292;
	}
.textbox {
    background-color: #EFEFEF;
    padding: 4px 25px;
}
.textbox h3 {
    margin: 0;
    padding: 22px 0 14px;
    font-size: 18px;
} 
