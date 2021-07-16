Post: https://api.github.com/gists

Headers: 

```Accept: application/vnd.github.v3+json```

Body:

```json
{
    "description": "List",
    "public": true,
    "files": {
        "list1.txt": {
            "content": "List..."
        },
        "list2.txt": {
            "content": "List2..."
        }
    }
}
```
