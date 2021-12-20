# Waifu
You can use this endpoint to get waifu pictures from the API, available only with paid plans.

!!! danger "NSFW"

    This is a warning that this endpoint is NSFW, meaning it may contain adult content. Be careful when using this endpoint and displaying it to your users. You need to ensure safety of your users while accessing this endpoint. Failure in doing so may result in your api key being revoked permanently.


### [GET](#){ .http-request } `/waifu/:type`

### Required Parameters:

| Parameter Name  |  Type | Description
|:-------------:|:--------------:|:--------------:|
| type |  path | SFW or NSFW, wether you want NSFW or SFW waifu pitcures. | 
| Authorization | header | Your api key.|

#### Optional Paremeters:

| Paremeter | Type | Default Value |
| :-------------: | :--------------: | :--------------: |
| waifu_type | string | waifu |

###Available waifu_types: 
- ##### SFW
??? info "SFW"

    1.`waifu`,    
    2.`neko`,    
    3.`shinobu`,    
    4.`megumin`,    
    5.`bully`,    
    6.`cuddle`,    
    7.`cry`,     
    9.`hug`,      
    10.`awoo`,    
    11.`kiss`,   
    12.`lick`,   
    13.`pat`,     
    14.`smug`,    
    15.`bonk`,    
    16.`yeet`,    
    17.`blush`,    
    18.`smile`,    
    19.`wave`,    
    20.`highfive`,        
    21.`handhold`,    
    22.`nom`,     
    23.`bite`,     
    24.`glomp`,     
    25.`slap`,     
    26.`kill`,         
    27.`kick`,    
    28.`happy`,    
    29.`wink`,     
    30.`poke`,     
    31.`dance`,     
    32.`cringe`

- ##### NSFW
??? danger "NSFW"
           
    1.`waifu`,    
    2.`neko`,    
    3.`trap`,    
    4.`blowjob`
