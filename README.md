A small ngram experiment: visualizing the frequency of "`nth` circle of hell" in books using a chart of concentric rings. Because why not.

## Data collection

Perform the following ngram queries:

```
first circle of hell,second circle of hell,third circle of hell,fourth circle of hell,fifth circle of hell,sixth circle of hell,seventh circle of hell,eighth circle of hell,ninth circle of hell,tenth circle of hell

first circle of Hell,second circle of Hell,third circle of Hell,fourth circle of Hell,fifth circle of Hell,sixth circle of Hell,seventh circle of Hell,eighth circle of Hell,ninth circle of Hell,tenth circle of Hell
```

For each one, save the html page, find the line that begins `var data = [{"ngram": "first circle of Hell", ...`. Copy them into a separate file, and do some munging to turn it into a json file (data.json).
