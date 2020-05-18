[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/BVCN-Jupyter_rise/master?filepath=Untitled.ipynb)


# BVCN-Jupyter_rise
BVCN Jupyter base with RISE slideshow support added for use via MyBInder.org.

See [here](https://github.com/fomightez/BVCN-Jupyter_base) for base version for use by learners.

The version that launches from here has RISE slideshow ability as well. This was made a new repository in order to decrease clutter of toolbar for learners. **THIS VERSION IS MEANT TO BE USED BY INSTRUCTORS SO THEY CAN USE THE RISE SLIDESHOWS TO CLEARLY SHOW AND DEMONSTRATE CODE CELLS.**


----

Technical notes:

RISE only works in the classic notebook mode. Therefore, upon launch the session starts in that interface so that the slideshow presentation icon is visible. The icon that siwtches from the notebook to the RISE slideshow mode looks like a bar chart. An time you are in the slideshow mode you can press the 'X' in the upper left to return to the notebook. 

**My students are working in JupyterLab. How do I switch so my interface looks like theirs when illustrating something?**  
You can switch to JupyterLab interface by editing the URL. The easiest way from the notebook view is to edit the URL so `notebooks` and any text with the name of the notebook after that is replaced with the text `lab`. Press return after that edit and the interface will change. Switching back from JupyterLab to the classic interface where RISE works is as easy as selecting above the from the main  menu: `Help` > `Launch Classic Notebook`.

You'll notice the kernel that is attached to the start up notebook is not the vanilla Python 3 and is instead the 'xpython' one. This is the same kernel with which the default notebook that [the base](https://github.com/fomightez/BVCN-Jupyter_base) opens. The idea is that you can then more easily switch from the code you are entering in the slideshow to view the debugger, if needed, without the need for also toggling the kernel. (Let me know if there would be a better way to approach the starting kernel.)

----

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/BVCN-Jupyter_rise/master?filepath=Untitled.ipynb)
