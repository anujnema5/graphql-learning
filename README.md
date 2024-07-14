<!-- Schema -->
### REQUIREMENTS

books {
    id, 
    title, 
    publishedYear,
    author
}

author {
    id,
    name,
    books
}

<!-- DATA -->
list of books
list authors
list of books with author details
list of author with book details