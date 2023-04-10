# Class 8 Notes

## APIs

## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. What does REST stand for?

    - Representational State Transfer

1. REST APIs are designed around a resource or a set of resources.

1. What is an identifier of a resource? Give an example.

    - URI (Uniform Resource Identifier) that uniquely identifies the resource. For example, in a RESTful API for a blog, the URI "/posts/123" could be the identifier of a specific blog post, where "123" is the ID of the post.

1. What are the most common HTTP verbs?

    - GET, POST, PUT, PATCH, and DELETE

1. What should the URIs be based on?

    - The resources being accessed, not the actions being performe

1. Give an example of a good URI.

    - Descriptive, easy to read, and consistent with the resources being accessed

1. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

    - Means that it requires multiple requests to retrieve or manipulate a single resource

1. What status code does a successful `GET` request return?

    - 200 OK

1. What status code does an unsuccessful `GET` request return?

    - 404 Not Found

1. What status code does a successful `POST` request return?

    - 201 Created

1. What status code does a successful `DELETE` request return?

    - 204 No Content

---

Bookmark and Review

- [RegExr](https://regexr.com/)

*Pay particular attention to the cheatsheet*

- [Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

- [Regex 101](https://regex101.com/)