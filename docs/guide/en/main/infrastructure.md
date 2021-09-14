# Components and services

> **Description:** This is the page were the infraestructure is described, but not just in terms of quantity
> the most important thing is refers to the details about to the interaction between them.

At this page it's important to use different types of divisions or segments to make clear the information.

#### e.g.

> related to items of infrastructure in fury and services.

- scopes
- services
- storage
- important relations with another apis

Also it's important to share information about the interaction with the infraestructure, because in some cases
we have a lot of different components and that it's an importan information to take into account when we need
to introduce new team members.

#### e.g.

> description related to interaction and use of the services.

- KVS distribution:

  - main-kvs-skeletor: this kvs save the data about the main objects to store with skeletor project.
  - idem-kvs-skeletor: store for idempotency keys to control request duplicity inside the project.

- Scopes use:

  - write-skeletor: all request related to POST/PUT/DELETE are redirected to this scope.
  - read-skeletor: all GET requests are moved with the traffic inside of this scope.