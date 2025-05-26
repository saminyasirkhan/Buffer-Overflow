💣 Buffer Overflow Exploitation & Secure Binary Analysis
Analysed and exploited stack-based buffer overflows in 64-bit Linux binaries using gdb-peda. Bypassed authentication logic by manipulating return addresses and jumping over validation checks. Used cyclic patterns to determine overflow offset and injected the address of the shell() function to hijack program execution.

Explored protection mechanisms including stack canaries, ASLR, and RELRO, and evaluated how code obfuscation, encryption, and safer functions (e.g. strncpy) mitigate overflow-based attacks.

Key Areas Covered:

🐛 Buffer overflow discovery and offset calculation with pattern_create

📌 Control flow hijacking through return address manipulation

🧠 Disassembly of logic using GDB to reverse engineer input validation

🔐 Analysis of stack canaries, ASLR, and segmentation protections

🧬 Mitigation strategies: bounds checking, obfuscation, secure function usage

Skills: Binary Exploitation · GDB Debugging · x86-64 Assembly · System Security · Memory Management · Secure Coding
