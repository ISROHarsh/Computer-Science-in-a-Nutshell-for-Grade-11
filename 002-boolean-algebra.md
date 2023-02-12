# Boolean Algebra
_Boolean algebras are systems where you take propositions which can have true-or-false values, and assign them symbolic names, as if they were math variables._

* `Boolean variables` - The values `true` and `false` represented by `1` or `0` are known as boolean variables.
* `Boolean experessions` - They deal with boolean variables and operators such as `AND` `OR` `NOT` etc.
* `Logic gates` - They are a bunch of electronic components (mostly transistors) connected together to give the effect of a component with (usually) two inputs and one output. A voltage is applied to the inputs, and the output will depend on the type of gate.

---
## Logic Gates

### `AND` Gate
![](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b9/AND_ANSI_Labelled.svg/180px-AND_ANSI_Labelled.svg.png)

_Returns `true` if both the inputs are true._

**Truth table**

| A | B | A AND B |
|:---:|:---:|:---------:|
| 0 | 0 |    0    |
| 1 | 1 |    1    |
| 1 | 0 |    0    |
| 0 | 1 |    0    |

---

### `OR` Gate
![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/16/OR_ANSI_Labelled.svg/180px-OR_ANSI_Labelled.svg.png)

_Returns `true` if one of the input is true._

**Truth table**

| A | B | A OR B |
|:---:|:---:|:--------:|
| 0 | 0 |    0   |
| 1 | 1 |    1   |
| 1 | 0 |    1   |
| 0 | 1 |    1   |

---


### `NOT` Gate
![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/60/NOT_ANSI_Labelled.svg/180px-NOT_ANSI_Labelled.svg.png)

_Also known as inverter gate. Returns opposite of the input._

**Truth table**

| A | NOT A|
|:---:|:------:|
| 0 |   1  |
| 1 |   0  |

---


### `NOR` Gate
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c6/NOR_ANSI_Labelled.svg/180px-NOR_ANSI_Labelled.svg.png)

_Returns opposite of two `OR` gates_

**Truth table**

| A | B | A NOR B |
|:---:|:---:|:--------:|
| 0 | 0 |    1   |
| 1 | 1 |    0   |
| 1 | 0 |    0   |
| 0 | 1 |    0   |

---

### `XOR` Gate
![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/XOR_ANSI_Labelled.svg/180px-XOR_ANSI_Labelled.svg.png)

_EXCLUSIVE-OR. Returns `true` when the number of true inputs is odd._

**Truth table**

| A | B | A XOR B |
|:---:|:---:|:---------:|
| 0 | 0 |    0    |
| 1 | 1 |    0    |
| 1 | 0 |    1    |
| 0 | 1 |    1    |

---

### `NAND` Gate
![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e6/NAND_ANSI_Labelled.svg/180px-NAND_ANSI_Labelled.svg.png)

_NOT-AND gate. Returns opposite of two `AND` inputs._

**Truth table**

| A | B | A NAND B |
|:---:|:---:|:----------:|
| 0 | 0 |     1    |
| 1 | 1 |     0    |
| 1 | 0 |     1    |
| 0 | 1 |     1    |

---

### `XNOR` Gate
![](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b8/XNOR_ANSI_Labelled.svg/180px-XNOR_ANSI_Labelled.svg.png)

_EXCLUSIVE-NOT-OR. Returns `true` when both the inputs are equal._

**Truth table**

| A | B | A XNOR B |
|:---:|:---:|:---------:|
| 0 | 0 |    1    |
| 1 | 1 |    1    |
| 1 | 0 |    0    |
| 0 | 1 |    0    |

---

## Logic circuits for some boolean expression

|                      |                |        
|----------------------|----------------|
|![](assets/logic-circuit-1.png)| ![](assets/logic-circuit-2.png)|
|![](assets/logic-circuit-1.png)| ![](assets/logic-circuit-2.png)| 

---

<!-- ## Laws/rules of Boolean Algebra -->










