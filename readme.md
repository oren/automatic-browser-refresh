# Automatic Browser Refresh

Template website for refreshing the browser on file change

## Index

* [Install](#install)
* [Run](#run)

## install

    git clone git@github.com:oren/automatic-browser-refresh.git
    cd automatic-browser-refresh
    npm install

## Run

    go build && ./automatic-browser-refresh  # run the webserver (assumes go installed)
    npm run livereload                       # watch changes in static dir
    modify any file in the static folder and notice the automatic browser refresh

## How does it work?

It uses [live-reload](https://github.com/Raynos/live-reload) npm module that is doing the watching and the browser refresh - `live-reload --port 4000 static/`
