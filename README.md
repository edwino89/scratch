# scratch
Too Cheap to Pay for Evernote

## Bvrgeon Tech - 271224
1. Stack: React Native/Expo, Golang/Python, Postgres
2. Storage: postgres, s3 like object storage, local first storage...
3. Notifications: email, websockets
4. Auth: email/password, OAuth: Google, Apple
5. Payments: stripe, paystack, pesapal
6. Deployment: vps, docker swarm, github actions ci/cd

## Business Tools
1. Google Africa Accelerator [Link](https://startup.google.com/programs/accelerator/africa/)
2. Moodle LMS [Link](https://moodle.org/)
3. Tunga [Link](https://tunga.io/for-developers/)
4. Designing a Landing Page [Link](https://www.youtube.com/watch?v=cJ10BYWNPns)

## Ideas
1. React Hooks, Stale While Revalidate [Link](https://dev.to/aviaryan/a-guide-to-stale-while-revalidate-data-fetching-with-react-hooks-15do)
2. Add Retries to HTTP Requests [Link](https://dev.to/bearer/add-retries-to-http-requests-377n)
1. Payment Gateways in Kenya [Link](https://josephmatino.com/best-payment-gateways-in-kenya/)
1. Design Patterns in react [Link](https://www.youtube.com/watch?v=MdvzlDIdQ0o)
2. Infinite Scroll [Link](https://medium.com/@Jscrambler/implementing-infinite-scroll-with-react-query-and-flatlist-in-react-native-e219c30e3d0c)
3. Refine; React Design Patterns [Link](https://refine.dev/blog/react-design-patterns/)
1. Using React with Golang [Link](https://www.youtube.com/watch?v=Y7kuW1qyDng)
1. How to Build Recursive React Component [Link](https://www.youtube.com/watch?v=6UU2Ey4KZr8)
1. Getting Started with OAuth2 in Go [Link](https://medium.com/@pliutau/getting-started-with-oauth2-in-go-2c9fae55d187)
1. Go Embed sub.FS Folder [Link](https://clavinjune.dev/en/blogs/serving-embedded-static-file-inside-subdirectory-using-go/)
2. React Native Cheat Sheet [Link](https://cheatography.com/bochrak/cheat-sheets/react-native/)
1. Math Latex [Link](https://www.npmjs.com/package/mathlive)
2. Visualize LLM [Link](https://bbycroft.net/llm)
1. Probability and Statistics Course [Link](https://www.probabilitycourse.com/courses.php)
2. AI Movies [Link](https://watch.runwayml.com/)
3. Golang React WebRTC [Link](https://www.youtube.com/watch?v=JTIm3ChI-6w&list=PLT-AS3Wcy-pndmzVGbgHLKjEXSzQLdgFM&index=2)
4. LiveStream Project [Link](https://www.youtube.com/watch?v=qenAQwLvZfA&list=PLkqiWyX-_LotUQHQXzeVD6Ogtcok7lObw&index=19)
5. 25 React Projects [Link](https://www.youtube.com/watch?v=5ZdHfJVAY-s)
6. Research Papers [Link](https://sci-hub.ru/)
7. Tutorials [Link](https://rutracker.org/forum/viewforum.php?f=1565&start=2400)

## Web
1. Code with Beto [Link](https://beto.vercel.app/)
1. React Native for Web [Link](https://necolas.github.io/react-native-web/docs/)
1. Universal Apps [Link](https://www.youtube.com/watch?v=VSZEfQx-byg&list=PLXXnezSEtvNPlwbFvG3NzJAW5ikYsG2Lh)
1. GlueStack UI [Link](https://gluestack.io/ui/docs/apps/dashboard-app)
2. Shuffle.Dev [Link](https://shuffle.dev/components/bootstrap/all/alert)

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

## ML
1. ML [Link](https://ml-resources.vercel.app/)
2. Music Recommender App [Link](https://www.youtube.com/watch?v=gaZKjAKfe0s)
3. Machine Learning Lib From Scratch [Link](https://github.com/duongttr/mllib-from-scratch?tab=readme-ov-file)
4. The Bitter Lesson [Link](http://www.incompleteideas.net/IncIdeas/BitterLesson.html)

## Postgres
1. Modeling HIerarchical Tree Data [Link](https://leonardqmarcq.com/posts/modeling-hierarchical-tree-data)
2. Scaling Postgres Zerodah [Link](https://zerodha.tech/blog/working-with-postgresql/)
3. Replicating Postgres [Link](https://www.enterprisedb.com/postgres-tutorials/postgresql-replication-and-automatic-failover-tutorial)
4. State Machine in Postgres [Link](https://felixge.de/2017/07/27/implementing-state-machines-in-postgresql/)
5. Use your database as a state machine [Link](https://blog.lawrencejones.dev/state-machines/)

## Golang
1. 100 Golang Mistakes [Link](https://100go.co/)
2. PGX WalkThrough [Link](https://www.youtube.com/watch?v=sXMSWhcHCf8)

## Python
1. Python Fire CLI [Link](https://github.com/google/python-fire/blob/master/docs/guide.md)

## React Native/Expo Component Patterns
1. Single Responsibility Components
2. Compound Components ie children props, context eg Aside & Main, Form Elements, Tables, Toast Messages... etc
3. Custom Hooks eg useWindowDimention, useFetch, onLayout for views, Media Queries, # of Columns... etc
4. Layout Components, Pass Prop, Error State & Loading State
5. 

## HTMX
1. Server Side Rendered [Link](https://www.wimdeblauwe.com/blog/2024/12/31/problems-i-no-longer-have-by-using-server-side-rendering/)

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

## Expo File Upload
```
import { StyleSheet, Button, View } from "react-native";
import * as DocumentPicker from "expo-document-picker";
import axios from "axios";
import { apiUrl } from "./url";

export default function App() {
  const pickSomething = async () => {
    try {
      const docRes = await DocumentPicker.getDocumentAsync({
        type: "audio/*",
      });

      const formData = new FormData();
      const assets = docRes.assets;
      if (!assets) return;

      const file = assets[0];

      const audioFile = {
        name: file.name.split(".")[0],
        uri: file.uri,
        type: file.mimeType,
        size: file.size,
      };

      formData.append("audioFile", audioFile as any);

      const { data } = await axios.post(apiUrl, formData, {
        headers: {
          Accept: "application/json",
          "Content-Type": "multipart/form-data",
        },
      });
      console.log(data);
    } catch (error) {
      console.log("Error while selecting file: ", error);
    }
  };

  return (
    <View style={styles.container}>
      <Button title="Pick something" onPress={pickSomething} />
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: "#fff",
    alignItems: "center",
    justifyContent: "center",
  },
});
```
