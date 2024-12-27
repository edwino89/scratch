# scratch
Too Cheap to Pay for Evernote

## Bvrgeon Tech - 271224
1. Stack: React Native/Expo, Golang/Python, Postgres
2. Storage: postgres, s3 like object storage, local first storage...
3. Notifications: email, websockets
4. Auth: email/password, OAuth: Google, Apple
5. Payments: stripe, paystack, pesapal
6. Deployment: vps, docker swarm, github actions ci/cd

## Ideas
1. React Hooks, Stale While Revalidate [Link](https://dev.to/aviaryan/a-guide-to-stale-while-revalidate-data-fetching-with-react-hooks-15do)
2. Add Retries to HTTP Requests [Link](https://dev.to/bearer/add-retries-to-http-requests-377n)
1. Payment Gateways in Kenya [Link](https://josephmatino.com/best-payment-gateways-in-kenya/)
1. Design Patterns in react [Link](https://www.youtube.com/watch?v=MdvzlDIdQ0o)
1. Using React with Golang [Link](https://www.youtube.com/watch?v=Y7kuW1qyDng)
1. How to Build Recursive React Component [Link](https://www.youtube.com/watch?v=6UU2Ey4KZr8)
1. Getting Started with OAuth2 in Go [Link](https://medium.com/@pliutau/getting-started-with-oauth2-in-go-2c9fae55d187)
1. Go Embed sub.FS Folder [Link](https://clavinjune.dev/en/blogs/serving-embedded-static-file-inside-subdirectory-using-go/)
2. React Native Cheat Sheet [Link](https://cheatography.com/bochrak/cheat-sheets/react-native/)
1. Math Latex [Link](https://www.npmjs.com/package/mathlive)
   
## Web
1. Code with Beto [Link](https://beto.vercel.app/)
1. React Native for Web [Link](https://necolas.github.io/react-native-web/docs/)
1. Universal Apps [Link](https://www.youtube.com/watch?v=VSZEfQx-byg&list=PLXXnezSEtvNPlwbFvG3NzJAW5ikYsG2Lh)
1. GlueStack UI [Link](https://gluestack.io/ui/docs/apps/dashboard-app)

## React Native Sites
1. BeatGig [Link](https://beatgig.com/)
1. Twitter [Link](https://x.com/)
1. BlueSky [Link](https://bsky.app/)
1. FlipKart [Link](https://www.flipkart.com/)  
1. Evan Bacon [Link](https://evanbacon.dev/)  

## Expo Universal Ideas
1. Tables
2. Drop Downs using Modals
3. Forms
4. Media Queries
5. Notifications/Toast Messages

## React Native/Expo Component Patterns
1. Single Responsibility Components
2. Compound Components ie children props, context eg Aside & Main, Form Elements, Tables... etc
3. Custom Hooks eg useWindowDimention, useFetch, onLayout for views, Media Queries, # of Columns... etc

## React vs Postgres
|React/React Native|Postgres|
|---|---|
|declarative UI|declarative data storage|
|quirky edge cases eg optimize renders aka hooks|quirky edge cases eg optimize queries|
|zustand, react query cache|redis, memecache cache|
|react patterns - compound components, props, caching|postgres patterns - transactions, recursive queries, caching|
|dsl: typeScript/javascript/jsx|dsl: sql/plpgsql/c|
|rich framework/plugin ecosystem|rich forks/plugin ecosystem|
|vercel|supabase|
|complex: can use htmx|complex: can use sqlite|
|abstractions: ui libraries; shadcn, gluestack|abstractions: orms gorm, sql alchemy|

## DB Schema for a Chat App
```
-- db schema for chat app
create table users(
id 
username
email
password_hash
created_at)

create table channels(
id
name
description
channel type
channel status open, closed, stale...
created at)

create table messages(
id 
user_id
channel_id 
content text
created at
is_direct_message)

create table channel_memberships(
id 
user_id
channel_id
joined_at) depends on channel type can use exists???

create table direct_messages(
id primary key
sender id
receiver id
content
created at)


dm/aggregate_id

channel
channel type
channel members
have a condition on channel creation

```

