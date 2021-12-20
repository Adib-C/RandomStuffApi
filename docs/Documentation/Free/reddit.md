# Reddit
You can use this endpoint to get reddit images/posts from the API, available for both free and paid plans.


### [GET](#){ .http-request } `/reddit/:method`

### Required Parameters:

| Parameter Name  |  Type | Description
|:-------------:|:--------------:|:--------------:|
| method |  path | What type of function do you want to perform? | 
| searchType | query | The searchType can be `hot`, `top`, `new`, `rising` |
| Authorization | header | Your api key.|

### Available Methods

* FetchSubredditPost
* FetchPost
!!! info "`FetchSubredditPost` and `FetchPost` methods"
          
          These methods requires another query parameter: `subreddit`
* RandomMeme
* FetchRandomPost
* fetchPostById
!!! info "`fetchPostById` method"

          This method requies another query parameter: `id`
  




