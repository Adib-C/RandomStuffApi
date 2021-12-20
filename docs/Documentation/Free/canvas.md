# Canvas
You can use this endpoint to manipulate images using the API and get the result back in base64 format. 

### [GET](#){ .http-request } `/canvas/:method`

### Required Parameters:

| Parameter Name  |  Type | Description
|:-------------:|:--------------:|:--------------:|
| `method` |  `path` | What type of method do you want | 
| `Authorization` | `header` | Your api key.|

### Optional Parameters

| Parameter Name  |  Type | Description
|:-------------:|:--------------:|:--------------:|
| `img1` |  `query` | First image URL (PNG FORMAT) | 
| `img2` | `query` | Second Image URL (PNG FORMAT)|
| `img3` | `query` | Third Image URL (PNG FORMAT)|
| `txt` | `query` | Text string |

### Customisation

#### Types of methods available and parameters required. 
##### Method(s) in which only 1 image is required:
"affect",
"beautiful", 
"wanted", 
"delete", 
"trigger",
 "facepalm", 
"blur", 
"hitler", 
"kiss", 
"jail", 
"invert", 
"jokeOverHead"
##### Method(s) in which 2 images are required:
"bed", 
"fuse" , 
"kiss", 
"slap", 
"spank"
##### Method(s) in which 3 images are required:
"distracted"
##### Method(s) in which only Text is required:  
"changemymind"