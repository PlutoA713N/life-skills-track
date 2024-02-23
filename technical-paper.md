# Investigating Database Options for Improved Full-Text Search Performance

# Full-Text Search
Full-text search is a retrieval method enabling users to find documents containing specific words or phrases within a collection. It involves tokenizing text, creating an index, and utilizing it to swiftly locate relevant documents. This approach is fundamental in applications like search engines and databases, facilitating efficient and flexible information retrieval.


## Elasticsearch
Elasticsearch is a powerful, distributed search engine built on top of Apache Lucene. It provides real-time search capabilities and supports large-scale data processing. With a RESTful API, Elasticsearch is known for its ease of use and scalability. It excels in handling unstructured data and is suitable for projects requiring extensive analytics and complex queries.

## Solr
Apache Solr, also built on Apache Lucene, is an open-source search platform. It is known for its flexibility and robust features, offering faceted search, hit highlighting, and distributed search capabilities. Solr is suitable for various use cases, including e-commerce, content discovery, and enterprise search.

## Lucene
Apache Lucene is the underlying technology for both Elasticsearch and Solr. It is a high-performance, full-featured text search engine library written in Java. Lucene is powerful but lacks some of the features provided by Elasticsearch and Solr. It is often used as a building block for custom search solutions.

## Comparison of Full-Text Search Engines
| Feature            | Lucene                                             | Solr                                               | Elasticsearch                                       |
|--------------------|----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|
| **Underlying Tech** | Library for building search functionality in Java  | Built on Lucene, provides additional features        | Built on Lucene, offers a distributed search engine |
| **Use Case**        | Library for custom search solutions               | Versatile, suitable for various search applications  | Real-time distributed search engine                  |
| **Scalability**     | Not inherently scalable, used as a building block  | Horizontal scalability, supports distributed search | Built for scalability, distributed by design          |
| **Ease of Use**     | Requires development effort for custom solutions  | Configurable, provides a user-friendly interface     | User-friendly, RESTful API, easier to set up and use  |


## References
- [Elasticsearch Official Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html)
- [Apache Solr Official Website](https://lucene.apache.org/solr/)
- [Apache Lucene Official Website](https://lucene.apache.org/core/)
- [Lucene vs Solr vs ElasticSearch](https://anytxt.net/how-to-choose-a-full-text-search-engine/)
