# nationalize
api for nationalize.io
# Example
```nim
import asyncdispatch, nationalize, json, strutils
let data = waitFor nationalize_by_name("name")
echo data
```

# Launch (your script)
```
nim c -d:ssl -r  your_app.nim
```
