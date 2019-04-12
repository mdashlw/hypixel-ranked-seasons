# Hypixel Ranked Seasons

All Hypixel Ranked seasons in the following JSON schema:

```js
{
  "number": 1, // Season number, 1-indexed
  "hiddenInAPI": false, // Indicates whether the season is hidden in Hypixel API or not
  "leaderboard": [ // Stored leaderboard of the season
    {
      "uuid": "...", // Player UUID
      "name": "...", // Player name
      "ranked": { // Ranked object
        "rating": 123, // Rating
        "position": 1 // Position
      }
    }
  ]
}
```

Leaderboards - from **1** (inclusive) to **36** (inclusive)

## Contributing

You are free to contribute in any way.

##### Incomplete Seasons Leaderboards

* Season **4**: missing ratings for #2-10
* Season **8**: missing #7
* Season **11**: missing #1-4
* Season **15**: missing rating for #1; missing #2-10
* Season **24**: missing #9
* Season **31**: missing #2-3
* Season **34**: missing #2
* Season **35**: missing #5; missing #9

## License

No.
