Note that although most commits were done by a single person, the project has been done by a team of 3 with equal contributions.

Steps to setup geojsonio:
  Install pip install geojsonio
  Create a github token, select only create gist
  open geojson.io.py and replace ghapi = github3.Github() with ghapi = github3.login(token=yourtoken)
  run program