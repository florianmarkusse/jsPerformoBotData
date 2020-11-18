# Results summary

| Repository                 | # of performance bugs | # of files |
|----------------------------|-----------------------|------------|
| mermaid                    | 10                    | 2          |
| DeepLearning-500-Questions | 5                     | 1          |
| fullPage.js                | 3                     | 3          |
| create-react-app           | 2                     | 2          |
| pdf.js                     | 2                     | 1          |
| mpvue                      | 2                     | 1          |
| amphtml                    | 2                     | 1          |
| RSSHub                     | 2                     | 1          |
| dayjs                      | 1                     | 1          |
| strapi                     | 1                     | 1          |
| uni-app                    | 1                     | 1          |
| sequelize                  | 1                     | 1          |
| 12                         | 32                    | 16         |

# Results per performance bug type

| Repository                 | Undefined variables | Unnecessary binary operations | Reverse array fill |
|----------------------------|---------------------|-------------------------------|--------------------|
| mermaid                    |                     | 10                            |                    |
| DeepLearning-500-Questions |                     | 5                             |                    |
| fullPage.js                |                     | 3                             |                    |
| create-react-app           |                     | 2                             |                    |
| pdf.js                     |                     | 2                             |                    |
| mpvue                      |                     | 2                             |                    |
| amphtml                    |                     | 2                             |                    |
| RSSHub                     |                     | 2                             |                    |
| dayjs                      | 1                   | 1                             |                    |
| strapi                     |                     | 1                             |                    |
| uni-app                    |                     | 1                             |                    |
| sequelize                  |                     | 1                             |                    |

# Not pull Requestable

| Repository                 | # of performance bugs | # of files | Reason            |
|----------------------------|-----------------------|------------|-------------------|
| mermaid                    | 10                    | 2          | Generated   files |
| create-react-app           | 2                     | 2          | Generated files   |
| DeepLearning-500-Questions | 5                     | 1          | Deprecated        |
| pdf.js                     | 2                     | 1          | Purposefully      |
| mpvue                      | 2                     | 1          | Generated   files |
| amphtml                    | 2                     | 1          | Purposefully      |
|                            | 23                    | 6          |                   |

# Pull Requests sent

| Repository  | #fixes | Status   |
|-------------|--------|----------|
| dayjs       | 1      | Accepted |
| fullPage.js | 1      | Pending  |
| postcss     | 1      | Declined |
| RSSHub      | 2      | Accepted |
| sequelize   | 1      | Pending  |
| strapi      | 1      | Pending  |
| uni-app     | 1      | Pending  |

# False positives

| Repository   | #Fixes | #Files | Reason                      |
|--------------|--------|--------|-----------------------------|
| handsontable | 1      | 1      | Module that does reflection |
| Hubot        | 1      | 1      | Module                      |
| node         | 2      | 2      | Module                      |
| p5.js        | 4      | 1      | Module                      |
| parallax     | 1      | 1      | Reflection                  |
| portainer    | 2      | 2      | Module                      |
| ws           | 1      | 1      | Module                      |