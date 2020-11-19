# jsPerformoBotData
Projects and Scripts to gather the data for testing jsPerformoBot

To collect the repositores that were used to test the bot on, GitHub's GRaphQL API Explorer was used (https://developer.github.com/v4/explorer/). The following query was executed on the API:
```
{
  search(query: "is:public archived:false fork:false followers:>=100 language:javascript", type: REPOSITORY, first: 100) {
    repositoryCount
    edges {
      node {
        ... on Repository {
          id
          name
          url
        }
      }
      cursor
    }
  }
}
```

It is only possible to get the first 100 JavaScript projects this way, to increase the number of repositories to test on, the cursor of each project is also pulled to be able to add another parameter to the query *after: $CURSOR$*, which then collects the first 100 JavaScript projects after that cursor.

The repositories and results that were used for the project can be found in this repository under:
- $botResults.md$
- $repositoriesUsed.md$
- $statisticsPerRepositoryUsed.md$

An example of the first 300 repositories and how a query results looks like from  pulled GitHub's GRaphQL API Explorer can be found in the folder $exampleQueryResults$. These were the results on 27 October 2020, very similar to the ones used in the project.
