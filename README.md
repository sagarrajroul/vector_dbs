# Vector DataBase (CromaDB, Pinecode, Weaviate)

## What is vector data base
A vector database is a data base used for storing high-dimensional embeddings of image or text.

### What is Embadding 
The vector representation of image or text is an embadding.

### Why we need Vector db not relational db.
As we can't store unstructured data like image and text in relation db. it is difficult to search in relationaldb if i will store the image or audio as a base64 in relational db. Ex. what are the similar dogs.

![vector db work](https://www.google.com/url?sa=i&url=https%3A%2F%2Fdev.to%2Fpavanbelagatti%2Fwtf-is-a-vector-database-a-beginners-guide-16p&psig=AOvVaw3HWoW9rl7l-LHJcd45BV8R&ust=1722536135678000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCKj5wo7x0YcDFQAAAAAdAAAAABAE)

### Index in vector data base
It is kind of a datastructure where we will store similar kind of embadding(clusters) and when we query we just have to query thet index not the whole db.

### Use case of Vector DB
1. Long term memory for llms
2. Semantic search: Search beased on the meaning of the context
3. Recommendation system: Recommend similar product to the user.
4. Auto complete: Auto complete the text based on the text.
5. Similarity Search: Text, image, Audio, Video


