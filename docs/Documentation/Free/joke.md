# Jokes
You can use this endpoint to get jokes from the API, available for both free and paid plans.


### [GET](#){ .http-request } `/joke`

### Required Parameters:

| Parameter Name  |  Type | Description
|:-------------:|:--------------:|:--------------:|
| `type` |  `query` | What type of joke do you want | 
| `Authorization` | `header` | Your api key.|

### Optional Parameters:

| Parameter Name  |  Type | Description
|:-------------:|:--------------:|:--------------:|
| `blacklist` |  `query` | What type of joke do you not want. You can select more than 1 for eg - `?blacklist=nsfw&political` | 

### Customisation 

#### Flags available for blacklisting

| Flag | Explanation |
| :--- | :--- |
| `nsfw` | This will block nsfw jokes  |
| `religious` | This will block religious jokes |
| `political` | This will block Political Jokes  |
| `racist` | This will block Racist Jokes |
| `sexist` | This will block Sexist jokes |
| `explicit` | This will block explicit Jokes |


#### Types of jokes available

| Type | Explanation |
| :--- | :--- |
| `any` | This will return any type of joke.  |
| `dark` | This will return a Dark Joke 🌑 |
| `pun` | This will return a pun \(Dad Jokes 👨‍👧\) |
| `spooky` | This will return a scary joke 👻 |
| `christmas` | This will return a Christmas-based joke ❄️ |
| `programming` | This will return a programming joke 🤓 |
| `misc` | Any other type of Joke\(s\) |

