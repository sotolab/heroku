# heroku

    $ git clone https://github.com/sotolab/node_metamask_ropsten_contract.git
    $ cd node_metamask_ropsten_contract

    $ npm install  -g    heroku
    최초
    $ heroku login
    $ heroku git:clone -a sotoedu 
    $ cd sotoedu
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
