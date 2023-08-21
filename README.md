Short example to demonstrate how authorization on choices and templates is inherited across transaction tree.

Compile with

```
daml build
```

Run with 
```
daml sandbox --dar .daml/dist/authorization-0.0.1.dar
```
in one terminal and
```
daml script --script-name Main:main --dar .daml/dist/authorization-0.0.1.dar --ledger-host localhost --ledger-port 6865
```
in another.
