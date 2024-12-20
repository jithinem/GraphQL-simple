http://localhost:4000/graphql

query Query {
    persons {
        id,
        name,
        posts: {
            name
        }
    }
}