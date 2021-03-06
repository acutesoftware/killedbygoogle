<div align="center">
  <img src="assets/tombstone.png" alt="tombstone" style="height: 80px; width: 80px; padding: 0 20px;">
  <h1>Killed by Google</h1>
</div>

A tribute and log of beloved products and services killed by Google.

## Contribute

To add a product, add it to `graveyard.json` file. You'll need the following information:

- Name of Product (`name`)
- Launch Date (`dateOpened`)
- Discontinued Date (`dateClosed`)
- Description (`description`)
- Link (`link`)

The object should be appended to `graveyard.json` in the following format (note the alphabetical order of keys):

```
  {
    "dateClosed": "YYYY-MM-DD",
    "dateOpened": "YYYY-MM-DD",
    "description": "Product Name was a Harry Potter search engine."
    "link": "https://wikipedia.org",
    "name": "Product Name"
  }
```

### Description
The description should be a single sentence describing the product. It should begin with the products name. For example, "Google Reader was an RSS/Atom feed aggregator." It will be attached to a generated sentence like "Killed about 5 years ago, Google Reader was an RSS/Atom feed aggregator."

Please be respectful, only use past tense.

### Link
Link should be a resource that mentions the discontinuation date and talks about the product. Wikipedia is perfect.
