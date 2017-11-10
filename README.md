# Combined filtering + sorting demo

This demo combines both the [filtering demo](https://github.com/fin-hypergrid/fin-hypergrid-filtering-demo) and the [sorting demo](https://github.com/fin-hypergrid/fin-hypergrid-sorting-demo), illustrating how to:
* install multiple plugins
* append multiple data transformers in a piped data model

### Hypergrid version
\>= `3.0.0`

> NOTE: As of this writing, v3.0.0 has not yet been released, nor is it in a committed branch. To build this demo today, pull #619 and build it in another folder; then edit package.json dependencies to reference that folder (_e.g.,_ `"fin-hypergrid": "file:../fin-hypergrid"` or a relative path to wherever you put it).

### Try it out

```bash
git clone https://github.com/fin-hypergrid/fin-hypergrid-filter-and-sort-demo.git filter-sort-demo
cd filter-sort-demo
npm install
gulp
open index.html
```

For further explanation/recommendations, see the individual demos and the [template](https://github.com/fin-hypergrid/fin-hypergrid-browserify-template) READMEs.
