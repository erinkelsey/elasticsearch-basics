# Elasticsearch Basics

Basic concepts and examples for working with Elasticsearch.

# What Is It?

Elasticsearch is a modern search and analytics engine, which is based on Apache Lucene. It is open source, built with Java, and is a NoSQL database. This means it stores data in an unstructured way. While Elasticsearch is a NoSQL database, it also has a strong focus on search capabilities and features.

## Elastic Stack

![Elastic Stack](images/elastic-stack.png)

# Key Concepts

## Documents

Documents are the things you are searching for. They can be more than text - any structured JSON data works. Every document has a unique ID, as well as a type.

This can be thought of as a row in a relational database.

## Types

A type defines the schema and mapping shared by documents, which represent the same sort of thing. For example, a log entry, an encyclopedia article, etc.

This can be thought of as a table in a relational database.

## Indices

An index powers search into all documents within a collection of types. They contain inverted indices, that let you search across everything within them, all at once.

This can be thought of as a relational database.

### Inverted Indices

![Inverted Indices](images/inverted-indices.png)
