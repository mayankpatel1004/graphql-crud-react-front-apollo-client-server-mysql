# graphql-crud-react-front-apollo-client-server
graphql-crud-react-front-apollo-client-server


```bash
typeDefs - 
    The defination of our schema of what we can expect from queries and mutations.
Resolvers - 
    Instead of the expectation of fields or required parameters, here we define the functions and behaviours of how should the queries and mutations would work.
Queries -
    The "gets" that we want to read from the server.
Mutations - 
    Our requests that are going to affect any data that we have on our own server.
```

```bash
# mutation{
#   setMessage(newMessage: "Its a Mutation !!!....")
# }

mutation{
  CreateUser(name:"Mikkke", email:"mayank@yopmail.com", gender: "Male"),{
    name
    email
  }
}

# query {
#   welcomeMessage(name: "Mayank Patel",dayOfWeek: "Sunday")
#   hello
#   getUser {
#     name
#     college
#   }
#   getUsers{
#     name
#   }
#   getPostsFromExternalAPI {
#     id
#     body
#   }
# }


```
