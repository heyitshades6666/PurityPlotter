# PurityPlotter
public &amp; private cords plotted onto a graph representing the Purity Vanilla Minecraft server

<h3>
  POINT DATA MODEL (json)
</h3>
```javascript
{
    name : string
    description : string
    color : number
    location : {
        x : number
        y : number
        z : number
    }
    dimension : string (overworld, nether, end)
    created : number (unixTimestamp)
    history : [{obj}]
}
```
