# Book details example 

http://localhost:8080/graphql

## Query
{
  bookById(id: "book-1"){
    id
    name
    pageCount
    author {
      firstName  
      lastName    
    }
  }
}

## Find the available queries
{
  __schema {
    queryType {
      fields {
        name
      }
    }
  }
}

## Find the available mutations
{
  __schema {
    mutationType {
      fields {
        name
      }
    }
  }
}


## Find the available types

{
  __schema {
    types {
      name      
      description 
      kind
    }
  }
}