# elf2mem

Extract a section from an ELF to Verilog's readmem format

```
usage: elf2mem.py [-h] [-s section] [-o output] [-l length] [-a address] elf-file

positional arguments:
    elf-file              The input ELF file

optional arguments:
    -h, --help            show this help message and exit
    -s section, --section section
                          The name of the ELF section file to output
    -o output, --output output
                          The path to the output readmem file (default: stdout)
    -l length, --length length
                          The length of a memory word in number of bytes
                          (default: 1)
    -a address, --addresses address
                          The number of addresses to increment per word
```
