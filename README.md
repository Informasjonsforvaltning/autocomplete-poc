# autocomplete-poc

## Assignment
Implement an autocomplete/suggestion solution on top of the ElasticSearch APIs.

We have provided a docker-compose file containing ElasticSearch. Use the provided JSON files for indexing. 

To simplify the assignment the autocomplete should only support the field `title.nb`. The result of the 
autocomplete will be used to execute the final search query which will return the documents.

There are several different techniques to implement this. You can find the documentation below.

## Documentation
- https://www.elastic.co/guide/en/elasticsearch/reference/7.17
- https://www.elastic.co/guide/en/elasticsearch/reference/7.17/query-dsl-prefix-query.html
- https://www.elastic.co/guide/en/elasticsearch/reference/7.17/search-suggesters.html#completion-suggester
- https://www.elastic.co/guide/en/elasticsearch/reference/7.17/search-as-you-type.html
