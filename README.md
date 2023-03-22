# Prisma Basics

### To install:

`npm install @prisma/client`
or
`yarn add @prisma/client`

```
what is this
```

1. What is Prisma and why do we need it?

Prisma is an open-source, modern database toolkit that simplifies database access and management for application developers. It provides a type-safe and scalable ORM (Object-Relational Mapping) that allows developers to interact with databases using programming languages and APIs they are already familiar with, such as JavaScript, TypeScript, and Node.js.

Prisma supports various popular databases such as PostgreSQL, MySQL, and MongoDB, and enables developers to perform complex database operations with ease, such as filtering, sorting, pagination, and aggregation. Prisma also handles database schema migrations, making it easy to make changes to the database schema without causing disruptions to the application.

2. How Prisma differs from other ORMs
   Prisma differs from other ORMs (Object-Relational Mapping) in a few key ways:

Type-safety: Prisma provides type-safe database access, which means that developers get compile-time checks on their queries, reducing the likelihood of runtime errors. Other ORMs typically rely on string-based queries, which can lead to errors that aren't caught until runtime.

Performance: Prisma uses a client-server architecture, which optimizes database access by caching queries and managing database connections more efficiently. Other ORMs may generate inefficient SQL queries, leading to slower performance.

Declarative schema management: Prisma's schema management is declarative, meaning that developers define the desired database schema in code, and Prisma handles the SQL migrations automatically. Other ORMs may require developers to manually write SQL migrations, which can be error-prone and time-consuming.

Language support: Prisma supports multiple programming languages, including JavaScript, TypeScript, and Rust. Other ORMs may only support a single language or a limited set of languages.

Overall, Prisma provides a more modern, efficient, and secure way to manage database interactions than many other ORMs, making it an attractive choice for many developers.

3.
