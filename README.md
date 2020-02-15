# kubectl-plugins

My kubectl plugins.

Put on your path for `kubectl` to pick them up, works with current context/user.

- `kubectl-cleartoken`: Clears the current contexts auth-token
- `kubectl-copytoken`: Copies the current contexts auth-token 
- `kubectl-cronview`: Allows for human-friendly cron schedules

Example usage:

```
kubectl cronview
```

Some require additional tools:

- jq
- pbcopy
- sort
- sed


