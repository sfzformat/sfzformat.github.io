---
template: "sfz/opcode.j2"
opcode_name: "pitcheg_release_zero"
---
When 1, indicates release time is the time it would take to get
from 0dBs to -oo, NOT the time to get from the current sustain to zero.

In other words, under default behavior, the release time is fixed, while
setting this to 1 makes the release slope fixed but time will be shorter
when sustain level is lower.

## Examples

```sfz
pitcheg_release_zero=1
pitcheg_release_zero=0
```
