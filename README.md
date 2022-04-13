Note that although most commits were done by a single person, the project has been done by triple programming as a team to catch errors, develop models, clean data and visualize results by streaming meetings on discord and contributing equally

Steps to setup geojsonio:
  Install pip install geojsonio
  Create a github token, select only create gist
  open geojson.io.py and replace ghapi = github3.Github() with ghapi = github3.login(token=yourtoken)
  run program