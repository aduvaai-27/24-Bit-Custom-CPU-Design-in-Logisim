Here's a GitHub project description:

---

**24-Bit Custom CPU Design in Logisim**

A fully functional 24-bit CPU designed and simulated in Logisim, built following Von Neumann architecture. The processor implements a 14-instruction ISA with a 4-bit opcode, 8-bit address field, and 24-bit data word.

**Instruction Set:**
ADD, SUB, INC, DEC, AND, OR, LDA, STO, BUN, JZ, JNZ, ROL, ROR, MUL

**Key Features:**
- Microprogrammed control unit with ROM-based micro-operation sequencing
- Complete Fetch–Execute cycle with RTL-level micro-operations
- Register datapath: PC, MAR, MBR, IR, AC, and carry flip-flop
- ALU with zero and negative status flags for conditional branching
- Booth's Multiplication Algorithm for signed 24-bit multiplication

**Built for:**
CSE 2114 – Computer Organization and Architecture
Khulna University of Engineering & Technology (KUET)

**Tools Used:** Logisim
