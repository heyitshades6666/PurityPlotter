# PurityPlotter


###### LOCATION DATA MODEL (json)

```javascript
{
    name : string,
    description : string,
    color : number (hex),
    location : {
        x : number,
        y : number,
        z : number,
    }
    dimension : number (1 = overworld, 2 = nether, 3 = end),
    created : number (unixTimestamp),
    history : [{obj}]
}
```
