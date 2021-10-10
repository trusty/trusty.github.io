---
title: "Json to Struct in Elixir"
date: 2021-10-10T18:32:18+05:30
---
## We can convert JSON to struct in Elixir using Poison library in single line

```
Poison.decode!(json, as: [%Bear{}])
```
