# gadgets-nettools

NetTools for the gadgets of [polpo](https://github.com/polpo-system/polpo): the network part of the documents of the web: connections over NetSystem, streams on them, host and port of a URL, the proxies of the section NetSystem of Oberon.Text. HTTPDocs uses it.

```
portia.Install gadgets-nettools
```

## What is here

    src/ARM.NetTools.Mod     NetTools (in Linux Oberon the portable one, named for ARM)
    test/NetToolsTest.Mod

The source comes from ETH Linux Oberon (OLR, 2017-06-18), converted from an Oberon text to plain
text; the first commit has it unchanged. It compiles unchanged with all five of polpo's compilers
(x86, ARM, ARMv7, RISC-V, MIPS).

## Tests

    NetToolsTest.Run      1 check: the module loaded; it needs the desktop's display

The license is GPL-3 (`LICENSE`); the code comes from ETH Oberon, whose license (`LICENSE.ETH`)
asks to keep its copyright notice and conditions, which `LICENSE.ETH` does.
