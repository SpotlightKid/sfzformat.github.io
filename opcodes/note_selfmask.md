---
layout: "sfz/opcode"
lang: "en"
opcode_name: "note_selfmask"
---
Default self-masking behavior is that higher-velocity notes turn off
lower-velocity notes, but lower-velocity notes do not turn off
higher-velocity notes. This is generally desirable when playing repeated
piano notes, ride cymbals, hammered dulcimers etc. With note_selfmask set to off,
notes turn off notes with the same pitch regardless of velocity, which generally
sounds less "musical" but does ensure that note polyphony is always preserved
within the set limit, and can sound right for certain instruments.

## Example

```
note_selfmask=off
```
