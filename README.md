# Multiple Page Application Example (MPA)

## What is an MPA?
Traditional web application architecture where each page of the application is served separately using a new request from the browser to the server.

## Design Patterns

### View Transitions
View transitions exist for MPAs that enable web components to remain between routes served. This eliminates the white space or "flash" that appears in a typically MPA when users change routes.

### Prefetch
When the user wants to navigate to a new page, there is a performance penalty. Prefetching the new page helps to minimize the performance cost of switching routes.

There are different techniques to prefetch the next possible page, including using the Cache Storage with Service Workers or the Speculation Rules API.