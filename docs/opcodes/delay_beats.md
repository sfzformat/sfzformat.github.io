---
template: "sfz/opcode.j2"
opcode_name: "delay_beats"
---
Used in Cakewalk Dimension Pro and DropZone, alongside [stop_beats], to play slices of loops at specific points in the bar.
## Examples
```sfz
delay_beats=1
delay_beats=2.25 stop_beats=3
delay_beats=25.9922 stop_beats=26.0964  
```
## Practical Considerations
In ARIA this opcode can be used, but every region uses up a polyphony voice, and therefore raising polyphony to
MAX is recommended for sequences beyond a very short length.


[stop_beats]: stop_beats.md
