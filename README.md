# heroku

    $ git clone https://github.com/sotolab/node_html.git
    $ cd node_html

    $ npm install  -g    heroku
    
    최초
    $ heroku login
    $ heroku git:clone -a myproject
    $ cd node_html
    $ rm -rf .git/
    $ git init
    $ git add .
    $ git config user.name " "
    $ git config user.email " "
    $ git commit -am "make it better"
    $ git push heroku master
    $ heroku  open

    수정이후
    $ git add .
    $ git config user.name " "
    $ git config user.email " "
    $ git commit -am "update index.js"
    $ git push heroku master
    $ heroku  open
