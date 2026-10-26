# Vsfm

Flashable FM-1 packages and the browser compiler that writes a Prophet VS bank into them.

| File | What it is |
| --- | --- |
| `loom-vs.fwsc` | LOOM-VS package, product `FM-1_1100`, 610136 bytes |
| `loom-vs.bin` | LOOM-VS app image, 581300 bytes. The VS bank starts at offset 398104 |
| `vsfm-compiler.html` | Browser compiler. Its built-in package is Skiff, product `FM-1_700` |
| `patches/VS_Factory_Patches.zip` | Sequential factory program dump and wave dump |

The factory programs are already in both packages. Building the compiler with this zip does not change either image. The bank has 100 programs, starting with ZENNY 1, CHOIR 1, and PACBELL.

`loom-vs.fwsc` is the package from before the silent MIDI engine. The C source of the LOOM-VS changes is not in this repository. The public base is [charlesvestal/fm1-loom](https://github.com/charlesvestal/fm1-loom) tag `v0.5.4-beta`.

MD5:

- `loom-vs.fwsc` `3397e4c095c102399146a1e28df00ab8`
- `loom-vs.bin` `e68651e934095332e4022f81292bd7dd`
