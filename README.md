# chisel-async-rst_n-patch

firrtl_negedge_reset.patch is for firrtl tag: v1.4.1

chsiel-testers_negedeg_reset.patch is for chisel-testers tag: v1.5.1

These patches are compatible with chisel-projects

## Usage

```
  $ git clone https://github.com/chipsalliance/firrtl
  $ git checkout v1.4.1
  $ git submodule update --init --recursive
  $ git apply firrtl_negedge_reset.patch
```

```
  $ git clone https://github.com/freechipsproject/chisel-testers
  $ git checkout v1.5.1
  $ git submodule update --init --recursive
  $ git apply chisel-testers_negedge_reset.patch
```