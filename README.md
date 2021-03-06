# Recognize

![Project Icon](https://raw.githubusercontent.com/bitbutt/csc342-recognize/master/thumbnail.jpg "Project Icon")

## About

This repository contains a working prototype of the Recognize project frontend
and backend for the Fall 2014 semester of CSC-342 at North Carolina State
University. This project is a web application built on the Django framework.

## Team Members

* Miles Richardson
* Logan Adams
* Nikolay Titov
* William Higgins
* Christian Durazo
* Patrick Crocker

## Dependencies

* Python 3 (including headers)
* SQLite 3

## Installation

1. Copy/clone the project to the desired install location
2. Run the `setup.sh` script to install dependencies in the app's virtual environment and initialize the database
3. Use the following guide to configure serving the Django application with gunicorn and nginx ([link](https://www.digitalocean.com/community/tutorials/how-to-deploy-python-wsgi-apps-using-gunicorn-http-server-behind-nginx))
4. Access the game at `http://yourConfiguredServer/` and the admin console at `http://yourConfiguredServer/admin/`. Send an HTTP GET request to `http://yourConfiguredServer/json/albums/` to retrieve the album data as JSON.

## License

This project is released under the terms of the [MIT License](https://raw.githubusercontent.com/bitbutt/csc342-recognize/master/LICENSE).
