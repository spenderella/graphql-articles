# GraphQL: From Basics to Architecture

Examples and schemas for GraphQL article series.

## Articles
1. Introduction to GraphQL [ENG](https://tsalnikova.medium.com/introduction-to-graphql-663e211f8190) [RU](https://systems.education/graphql-intro)
2. GraphQL Schemas and Types [RU](https://systems.education/graphql-schema)
3. GraphQL Architecture [RU](https://systems.education/grapfql-arch)

## 🐳 Local Test Server

Run a full-featured GraphQL server locally with Docker:
```
bash
cd test-server 
docker-compose up --build 
```

## 📋 Schema & Query Files

Ready to copy schemas and queries from articles:
- `schemas/` - GraphQL schemas from articles
- `queries/` - Example queries and mutations

## How to use

### 🐳 Local (Docker)
1. Clone this repository:
```
bash
   git clone https://github.com/your-username/graphql-articles
   cd graphql-articles/test-server
```
2. Start the server:
``` docker-compose up --build ```
3. Open http://localhost:8080/graphql in your browser
4. Test queries, mutations, and real-time subscriptions
5. Stop with Ctrl+C,  then cleanup:
```docker-compose down```

Local server includes WebSocket subscriptions.
