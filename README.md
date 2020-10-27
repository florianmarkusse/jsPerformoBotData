# jsPerformoBotData
Projects and Scripts to gather the data for testing jsPerformoBot

To collect the repositores that were used to test the bot on, GitHub's GRaphQL API Explorer was used (https://developer.github.com/v4/explorer/). The following query was executed on the API:
`
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
`
