# PurityPlotter


###### LOCATION DATA MODEL (json)

```javascript
{
    name : string,
    description : string,
    color : number,
    location : {
        x : number,
        y : number,
        z : number,
    }
    dimension : string (overworld, nether, end),
    created : number (unixTimestamp),
    history : [{obj}]
}
```
