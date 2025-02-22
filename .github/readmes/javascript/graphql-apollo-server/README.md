# GraphQL Apollo Server Example

This example shows how to implement a **GraphQL server with JavaScript (Node.js)** based on [Prisma Client](https://www.prisma.io/docs/concepts/components/prisma-client), [apollo-server](https://www.apollographql.com/docs/apollo-server/) and [Nexus Schema](https://nxs.li/components/standalone/schema). It is based on a SQLite database, you can find the database file with some dummy data at [`./prisma/dev.db`](./prisma/dev.db).

__INLINE(../_setup-0.md)__
curl https://codeload.github.com/prisma/prisma-examples/tar.gz/latest | tar -xz --strip=2 prisma-examples-latest/javascript/graphql-apollo-server
__INLINE(../_setup-1.md)__
cd graphql-apollo-server
__INLINE(../_setup-2.md)__
cd prisma-examples/javascript/graphql-apollo-server
__INLINE(../_setup-3.md)__

__INLINE(../_start-graphql-server.md)__

__INLINE(../../_using-the-graphql-api.md)__

__INLINE(../_next-steps-graphql.md)__
