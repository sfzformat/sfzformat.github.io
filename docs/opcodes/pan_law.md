---
template: "sfz/opcode.j2"
opcode_name: "pan_law"
---
Allowed values are balance and mma. In earlier versions of ARIA,
no_law was also supported but that was later deprecated,
and if no_law is specified then balance will be used.

## Examples

```sfz
pan_law=balance
pan_law=mma
```
