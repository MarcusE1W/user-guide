# Inline Evaluation

### Python

Getting started with Python is as simple as:

1. Create a new file with a `.py` extension or open a `.py` file
2. While over some code press Cmd/Ctrl+Enter
3. Allow Light Table a few seconds while it connects to a python process
4. You'll now see results inline!

If you want to use Light Table to do matplotlib/pylab graphs and such, you'll need to install the IPython kernel:

1. Follow these [instructions](http://ipython.org/ipython-doc/stable/install/install.html) to install IPython (note: it must IPython 1.0 or greater and you *must* install pyzmq as well in order for it to work with Light Table.)
2. Make sure IPython is on your path
3. Restart Light Table
4. Open a `.py` file by pressing Cmd/Ctrl+Shift+O
5. Over an expression that will return a graph, press Cmd/Ctrl+Enter
6. You'll see the graph embedded below your expression.
