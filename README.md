# graphql-java
Graphql Experiments in java. Meant as a reference

### Sample Graphql in java

installing maven
```sudo apt-get install maven```

Initializing project:

```mvn archetype:generate -DarchetypeArtifactId=maven-archetype-webapp -DgroupId=com.howtographql.sample -DartifactId=hackernews-graphql-java -Dversion=1.0-SNAPSHOT```

Running server:

```mvn jetty:run -Djetty.http.port=9999```

## Declarative Data Fetching apis

```{
     allLinks{
       url
       description
     }
   }
   ```


## Mutation Samples

```mutation createLink{
     createLink(url:"https://google.com",description:"google home page"){
       url
       description
     }
   }
   ```
   