# Linker

The linker processes object files (which in our project are .out files) and generates an executable file. The linker has two main tasks, combining code and relocating symbols. Code from each input file's .text segment is merged together to create an executable. This also determines the absolute address of each symbol (assembler outputs a symbol table containing the relative address of each symbol). Since the absolute address is known, instructions that rely on absolute addressing can have the addresses filled in.
