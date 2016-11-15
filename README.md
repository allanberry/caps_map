author: Allan Berry
date: Fall 2016

CAPS: Chicago Aerial Photograph Service
===

The UIC library has a bunch of aerial photographs in storage.  This little project is a quick visualization, or at least the beginning of a visualization, to provide an index map for the collection.

It uses Python and Flask for a simple web server.  To run Flask, you'll need to install it first:

* pip install -r requirements.txt

If you don't have a usable Pip instance, I recommend getting comfortable with [Pyenv](https://amaral.northwestern.edu/resources/guides/pyenv-tutorial).

Then you can run the app like this: 

* export FLASK_APP=app.py
* python -m flask run

...or you can rip out the meat of the project, `index.svg`, and use it in a different way; up to you.

The file `templates/index.html` contains some D3 code to present the SVG file.

You'll also find a paper I wrote (`paper_final.pdf`), during a summer class on the subject of UIC's aerial photographs, and the original index file (`static/index.jpg`) which the svg is based on.

Hope this helps.  If not, please get in touch.

-Allan Berry
aberry3@uic.edu