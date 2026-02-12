### dgx
Deterministic Graph eXecutor

Planned Go project layout:

```text
dgx/
 ├─ cmd/
 │   └─ dgx/
 │       └─ main.go
 ├─ internal/
 │   ├─ config/
 │   ├─ parser/
 │   ├─ validator/
 │   ├─ graph/
 │   ├─ state/
 │   ├─ expr/
 │   ├─ policy/
 │   ├─ engine/
 │   ├─ rng/
 │   ├─ aggregator/
 │   └─ output/
 ├─ pkg/ (optional public interfaces later)
 ├─ go.mod
 └─ README.md
```
