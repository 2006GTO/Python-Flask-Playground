# Python-Flask-Playground
Using a custom url to dynamically change rendered html

Install flask using pip in your terminal (pip install Flask)

Install/Run a virtual environment https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/26/python-virtual-env/

In the root folder of this project, in your terminal, run "python server.py"

Navigate to localhost:5000

Navigating this WebApp:

'/' will show "Hello World!"
'/play' will add formatting and three blue boxes
'/play/<num>' will add the total number of boxes you typed in to the web page
'/play/<num>/<color>' will dynamically add the total number of boxes you typed in, plus make them the color you typed in as well.
