> [Sucrase](https://sucrase.io/) is a fast transpiler which I personally use instead of Babel / TypeScript when rapid prototyping some code.  
> You can get it to work with [nodemon](https://nodemon.io/)!

---

# 1. Install `sucrase` and `nodemon`

# 2. Create a file [`nodemon.json`](./nodemon.json)

```json
{
  "execMap": {
    "ts": "sucrase-node"
  }
}
```
