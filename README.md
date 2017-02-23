# Lyrical-GraphQL
Starter project from a GraphQL course on Udemy.com

## Heroku URL

Currently up to date with 55. Will continue.. sleep is needed.

https://pacific-island-18342.herokuapp.com/


## Linked content

http://dev.apollodata.com/react/cache-updates.html

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
