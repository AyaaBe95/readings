# GraphQL @connection

## AWS Amplify
- It is a set of tools and services that can be used together or on their own, to help front-end web and mobile developers build scalable full stack applications
- With Amplify, user can configure app backends and connect  app in minutes, deploy static web apps in a few clicks, and easily manage app content outside the AWS console.

## API (GRAPHQL)
- GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data.
- It provides a complete and understandable description of the data in your API.
- It gives clients the power to ask for exactly what they need and nothing more,
- It enables powerful developer tools.

### Add relationships between types
- @connection: enables you to specify relationships between @model types.
- Usage: Relationships between types are specified by annotating fields on an @model object type with the @connection directive.

### Relations:
- Has one
- Has many
- Belongs to
- Many-to-many connections

### Limit
- The default number of nested objects is 100. You can override this behavior by setting the limit argument

### Generates
- In order to keep connection queries fast and efficient, the GraphQL transform manages global secondary indexes (GSIs) on the generated tables on your behalf when using @connection
