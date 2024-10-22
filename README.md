<h2>Checking all git hashcode records</h2>
<br/>

```bash
git log --graph --oneline --all;
```

<img src="./assets/git-log-graph-all.jpeg" alt="git-log-graph-all">
<br/>

<h2>Restoring to a point using a specific git hashCode</h2>
<img src="./assets/git-checkout-hash.jpeg" alt="git-checkout-hash">
<br/>

```bash
git checkout <gitHash>;
```

<h2>Restoring to a specific git HEAD point</h2>

```bash
git checkout <HEAD>;
```


<h2>Restoring a file from current git hash point</h2>

```bash
git restore <path/fileName.ext>;
```
