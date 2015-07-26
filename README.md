# data-table

A reusable table component

## Features

* Render a list of object into table form
* Ordering of the columns
* Load data from server
* Table pagination (local data)
* Column sorting with multiple sorting keys
* Column search (planned)
* Table themes (planned)
* Table pagination from server side, django-rest-framework format (planned)

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    npm install && bower install
    
To run ajax example in this project, run:

    json-server --watch db.json

To develop this element:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/data-table/`, where `data-table` is the name of the directory containing it.
