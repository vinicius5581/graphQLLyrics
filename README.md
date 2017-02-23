# Lyrical-GraphQL
Starter project from a GraphQL course on Udemy.com

## Queries & Mutations

```
{
  songs{
    id,
    title,    
    lyrics{
      content
    }
  }
}
```
```
mutation{
  addSong(title: "I need that"){
    id,
    title
  }
}
```
```
mutation {
  addLyricToSong(songId: "58aea91474212c1b97cf826e", content: "I couldn't fell"){
    title,
    lyrics{
      content
    }
  }
}
```
