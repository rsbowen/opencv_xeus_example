OpenCV in C++ is great for doing computer vision and image processing work in a
C++ environment. Now there is a 
[Jupyter Kernel called Xeus](https://blog.jupyter.org/interactive-workflows-for-c-with-jupyter-fe9b54227d92)
for C++, which enables faster development cycles.

This repo contains a small example notebook showing how to use OpenCV in Xeus.
It shows how to get the includes to work, and contains a small shim for
displaying OpenCV images directly in the browser.

To try it out: follow the 
[Xeus installation directions](https://github.com/QuantStack/xeus), then run the notebook in this
repository. It does a fairly simple task: loads an image, cuts the saturation
by half, and displays the image. Interactively, you can try out and immediately
see the effect of all sorts of changes, for example:

* Try changing the factor by which the saturation is changed from 2 to something else
* Try messing with the hue or value instead

It's not quite as convenient as the equivalent thing in python, and the
technology is newer. But if you are using C++ anyway, your development
iteration time may be sped up quite a bit.
