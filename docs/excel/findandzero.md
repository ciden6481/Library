---

---

tags:
    - lambda
---
# find_and_zero

```

LAMBDA(find,lookin,return,VALUE(IFNA(SUBSTITUTE(HSTACK(XLOOKUP(find, lookin, return), XLOOKUP(find, lookin, OFFSET(return, 0, 1))), ".", 0), "0")));

```

