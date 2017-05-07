### Clojure Eval

After starting Light Table, open a new file by pressing `Ctrl-N`. This will create a temporary file named `untitled-1`.

Since the new file is not yet a Clojure or ClojureScript file we will set the syntax to Clojure. To do so, press `Ctrl-Space` to open the command bar, type/select 'Set current editor syntax', then select Clojure from the list.

Next, type `(+ 1 2)` followed by pressing `Ctrl-Enter` (`Cmd-Return` on Mac). This installs dependencies, if any, and evals the expression, which should return `3` to the immediate right of the line.

![](images/quickstart/clojure-eval-0.8.1.png)

### Clojure Instarepl

> Note: Instarepl currently only works for Clojure files (.clj), not ClojureScript.

> Note: The Instarepl is anticipated to be deprecated due to a lack of a maintainer and removed entirely starting with v0.9.0.

The Instarepl is no longer packaged with Light Table by default. First we will need to install the plugin. Navigate to the command bar (`Ctrl-Space`) and type/select 'Plugins: Show plugin manager'. This will open up the plugin manager. Type 'clojureinstarepl' and press enter to get a list of results. Hover the mouse over the 'ClojureInstarepl' result and an option to install the plugin should appear on the right hand side. Click to install the plugin. It may be necessary to restart Light Table to ensure the new plugin is fully loaded.

With the Instarepl plugin installed, press `Ctrl-Space` to show the command bar, type "repl" in the command search box, and then select one item to run it:
