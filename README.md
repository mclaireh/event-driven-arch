# How to Run This Site

This site is built with mkdocs here are the steps to replicate and install this site to view the documentation locally.

1. Have python and pip installed on your system
2. Run `pip install mkdocs` in terminal
3. Run `mkdocs serve` in terminal
4. From the terminal copy the IP address that it is being served on.
   For example it is usually something like:
   ```
   Serving on http://127.0.0.1:8000/
   ```
5. Now you should be able to view the site locally.

To deploy the site to Github Pages, simply create a PR and then push to main. Github Actions are setup that will automatically deploy the site to Github Pages.