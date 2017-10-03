Baby A3C: solving Atari environments in 180 lines
=======
Sam Greydanus | October 2017 | MIT License

Results for less than a day on a 980 Ti (CUDA would make this faster):

![breakout-v0.gif](breakout-v0/breakout-v0.gif)
![pong-v0.gif](pong-v0/pong-v0.gif)
![spaceinvaders-v0.gif](spaceinvaders-v0/spaceinvaders-v0.gif)

About
--------

_Make things as simple as possible, but not simpler._

Frustrated by the number of deep RL implementations that are clunky and opaque? In this repo, I've stripped a [high-performance A3C model](https://github.com/ikostrikov/pytorch-a3c) down to its bare essentials. Everything you'll need is contained in 180 lines...
	
 * If you are trying to **learn deep RL**, the code is compact, readable, and commented
 * If you want **quick results**, I've included pretrained models
 * If **something goes wrong**, there's not a mountain of code to debug
 * If you want to **try something new**, this is a simple and strong baseline

Dependencies
--------
 * Python 2.7 or 3.6
 * NumPy
 * SciPy: just for a single line...you could write a workaround
 * [PyTorch](http://pytorch.org/): easier to write, understand, and debug than TensorFlow :)