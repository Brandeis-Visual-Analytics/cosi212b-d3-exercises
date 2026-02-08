# cosi212b-d3-exercises
A set of d3 exercises to demonstrate its usage

## Instructions

First, let's look at a simple bar chart and line chart implemented in d3v7, the latest version as of February 2026, compared to an implementation in vega lite.  

Open the `d3_charts.html` in a text editor, and try to read through the code.  d3 is very idiomatic, so you see some odd logic like selecting all bars, "entering" them to bind them to the data, then adding the bars, then exiting.  This is what renders them.

To see this page, run a python web server in the directory:

    python -m http.server

Then, click on the link for d3_charts.html.  You should see an interactive bar chart and line chart with some simple tooltips.  Right click and inspect elements to see the SVG structure it created in the browser.

Now, do the same for `vegalite_charts.html`.  What do you think?  Is vega lite easier to understand and develop in?

Lastly, we should look at using `altair` to make the same chart.  Open up the `altair_charts.ipynb` in whatever notebook tool you use (I typically run a jupyter server `jupyter notebook altair_charts.ipynb`, but you could use pycharm, for example).  You may have to install some python packages to get it to work.  Altair can be used if you are making an interactive jupyter notebook, rather than a whole web tool.

### Next steps

Look through the [d3 gallery](https://observablehq.com/@d3/gallery?utm_source=d3js-org&utm_medium=hero&utm_campaign=try-observable), the [vega lite gallery](https://vega.github.io/vega-lite/examples/), and the [altair gallery](https://altair-viz.github.io/gallery/index.html) to see what can be done.  You are encouraged to use an AI assistant to try to develop your own visualizations, copy the gallery examples, or adapt them to your own data!