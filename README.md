# CR Docker

## Cheatsheet

To keep the pod to keep alive, use following entrypoint.
```
ENTRYPOINT ["tail", "-f", "/dev/null"]
```