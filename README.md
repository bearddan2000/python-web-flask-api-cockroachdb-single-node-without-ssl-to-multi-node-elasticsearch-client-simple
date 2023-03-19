# python-web-flask-api-cockroachdb-single-node-without-ssl-to-multi-node-elasticsearch-client-simple

## Description
Reads a multi cluster node for data in `animal-demo` document.

Uses `dog` table then covverts it to json for
elasticsearch to use.

## Tech stack
- python
    - flask
    - elasticsearch
    - elasticsearch_dsl
    - sqlalchemy
- elasticsearch
- kibana
- cockroach

## Docker stack
- python
- elasticsearch
- kibana
- cockroachdb/cockroach:v19.2.4

## To run
`sudo ./install.sh -u`
- Get all beverages: http://localhost/dog
  - Schema id, breed, and color
- Query with params: http://localhost/dog/id/<id>

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Docker setup](https://lynn-kwong.medium.com/all-you-need-to-know-about-using-elasticsearch-in-python-b9ed00e0fdf0)
- [Search setup](https://www.elastic.co/guide/en/elasticsearch/client/python-api/master/examples.html)