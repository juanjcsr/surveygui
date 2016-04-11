# Surveygui

Quickstart package for the [surveyor](https://github.com/NUBIC/surveyor) and [surveyor-gui](https://github.com/kjayma/surveyor_gui) packages.

**Surveygui** is a 4.1 Rails app that you can deploy if you need a fast and easy-to-use survey generator app.

# ToDo

Most of the items described here are already available in the surveyor and surveyor_gui packages.

* Add User generators
* Validate user responses
* Testing

# Survey Creation

You can check any created surveys by going to ```localhost:3000/surveyor_gui/```.  To create a new survey, click on the _New Survey_ link.

# Take Survey

Navigate to ```localhost:3000/surveys``` and chose your new created survey

# Install

## Dependencies
/
**Surveygui** is build on top of Rails 4.1. Work is been done to make Surveygui run on the last version of Rails

You need also a PostgreSQL database

## Install steps

Just clone this repo:

```
git clone https://github.com/juanjcsr/surveygui
```

install the dependencies:

```
bundle install
```


and then create and migrate the database

```
rake db:create db:migrate
```

