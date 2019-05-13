# Preliminary

Make sure you have [PLY](https://www.dabeaz.com/ply/) installed.

# Usage

Create an input file, then feed it to the compiler.

```
$ python braindead.py [INPUT_FILE]
```

Braindead is basically identical to the well-known esoteric language, [brainf\*\*k](https://esolangs.org/wiki/Brainfuck), with the only difference being the recognized symbols and removal of INPUT operation:

|         | brainf**k |    braindead    |
|---------|:---------:|:---------------:|
| INC     |     +     |     高雄發大    |
| DEC     |     -     |     高雄發財    |
| SHIFT_L |     <     |     雄大發財    |
| SHIFT_R |     >     |     大發高財    |
| OUTPUT  |     .     |     雄高財發    |
| INPUT   |     ,     | (not supported) |
| LOOP_L  |     [     |     發發財財    |
| LOOP_R  |     ]     |     雄大雄高    |
