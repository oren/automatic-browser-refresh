# Automatic Browser Refresh

Template website for refreshing the browser on file change

## Index

* [Install](#install)
* [Run](#run)

## install

    sudo npm install -g node-live-reload
    git clone git@github.com:oren/automatic-browser-refresh.git
    cd automatic-browser-refresh

## Run

    go run server.go                         # run the webserver (assumes go installed)
    node-live-reload -d . -d static          # watch current dir and static dir
    modify the html/css/js file and notice the automatic browser refresh

