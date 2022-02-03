# repository_dispatch_example

You can use the types keyword to limit your workflow to run when a specific event_type value is sent in the repository_dispatch webhook payload.

```
on:
  repository_dispatch:
    types: [on-demand-test]
```
