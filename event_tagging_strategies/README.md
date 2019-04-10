* tagging_with_searches_1 - original experiment to collect query and event text data and build a NN to map from text to query
* query string cluster exemplars and mapping - Using Ryan's technique to collapse related query terms into groups and find their exemplar - this dataset is used in several other files
* category_page_research - I exampine which queries are most appropriately associated with each category
* tagging_with_searches_2 - same thing as tagging_with_searches_1 but this time I collapse the queries together into their families - the effect is a deduplicated set of tags and also much more data since now I take the top 2000 queries and collapse them to the top 500 families rather than just taking the top 500 queries
* tagging_events_to_elasticsearch - I really clean up the modeling pipeline so that the datascience is easier to understand and reproduce
* supply vs demand analysis - I compare the search volume across our popular queries with the inventory volume across the same queries - the goal is to better understand supply/demand dynamics and look to correct imbalances
