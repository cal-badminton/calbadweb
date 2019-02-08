Cal Badminton Website
=====================

Design by HTML5UP and compiled with JekyllRB. Hosted currently on OCF and can be accessed [here](https://badminton.berkeley.edu).

To run locally:
* (if not installed) Install the Jekyll gem with `gem install jekyll`
* Go into the directory and `bundle exec jekyll serve -w --livereload`
* access the website at `localhost:4000`

To deploy:
* Run `jekyll build`
* Run `scp -r _site/* badmintn@ssh.ocf.berkeley.edu:public_html`
* ssh into the server `ssh badmintn@ssh.ocf.berkeley.edu`
* Fix the index file format `mv index.html index.shtml`
* Then you are done!
