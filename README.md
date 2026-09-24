# Half / Full Adder

## Aim

To realize **Half Adder and Full Adder** circuits:

1. Using **X-OR and basic gates**
2. Using **NAND gates only**

## Apparatus Required

* Digital Trainer Kit
* IC 7486 — X-OR Gate
* IC 7432 — OR Gate
* IC 7408 — AND Gate
* IC 7400 — NAND Gate
* Connecting wires

## Procedure

1. Verify the required logic gates.
2. Make the connections according to the circuit diagram.
3. Switch ON the VCC and apply different combinations of inputs according to the truth table.
4. Note the output readings for the Half Adder and Full Adder, including **Sum and Carry** outputs.

## Half Adder

A Half Adder adds two binary inputs **A** and **B** and produces:

* **Sum (S)**
* **Carry (C)**

### Truth Table

| A | B | Sum (S) | Carry (C) |
| - | - | ------- | --------- |
| 0 | 0 | 0       | 0         |
| 0 | 1 | 1       | 0         |
| 1 | 0 | 1       | 0         |
| 1 | 1 | 0       | 1         |

The observed voltage readings were approximately **0 V for LOW** and **5 V for HIGH**.

### Boolean Expressions

**Sum:**

```text
S = A ⊕ B
```

**Carry:**

```text
C = A · B
```

## Full Adder

A Full Adder adds three binary inputs:

* **A**
* **B**
* **Cin** (previous carry)

and produces:

* **Sum (S)**
* **Carry (C)**

### Truth Table

| A | B | Cin | Sum (S) | Carry (C) |
| - | - | --- | ------- | --------- |
| 0 | 0 | 0   | 0       | 0         |
| 0 | 0 | 1   | 1       | 0         |
| 0 | 1 | 0   | 1       | 0         |
| 0 | 1 | 1   | 0       | 1         |
| 1 | 0 | 0   | 1       | 0         |
| 1 | 0 | 1   | 0       | 1         |
| 1 | 1 | 0   | 0       | 1         |
| 1 | 1 | 1   | 1       | 1         |

These outputs match the truth-table readings recorded in the practical file.

### Boolean Expressions

**Sum:**

```text
S = A ⊕ B ⊕ Cin
```

**Carry:**

```text
C = AB + BCin + ACin
```

## Implementations

### 1. Using XOR and Basic Gates

The Half Adder and Full Adder are realized using:

* XOR gates
* AND gates
* OR gates

### 2. Using NAND Gates Only

The Half Adder and Full Adder are also realized using **NAND gates only**, as specified in the experiment.

## Result

The **Half Adder and Full Adder circuits** were successfully realized and verified using XOR/basic gates and NAND gates only.

The obtained **Sum and Carry outputs** were found to agree with their respective truth tables.


