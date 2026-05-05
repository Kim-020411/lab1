# Experiment 2

## Implementation of Multiplexer and Encoder using Basic Logic Gates in Logisim

---

## Objective

The objective of this experiment is to design and implement a Multiplexer and Encoder in Logisim Evolution. The aim is to understand data selection, encoding techniques, and hierarchical circuit design using basic digital components.

---

## Background Study

A Multiplexer (MUX) is a combinational circuit that selects one input from multiple inputs and forwards it to a single output based on select lines. For an n-select line MUX, the number of inputs is 2^n.

In this experiment, an 8:1 Multiplexer is implemented using smaller 2:1 multiplexers in a hierarchical (tree) structure. This reduces complexity and demonstrates modular circuit design.

In this experiment, an 8:1 Multiplexer is implemented using smaller 2:1 multiplexers in a hierarchical (tree) structure. This reduces complexity and demonstrates modular circuit design.
.
---

## Experiment Description

In this experiment, two circuits were implemented

Firstly, 8:1 MUX was constructed using multiple 2:1 MUX blocks. Inputs were grouped and reduced in stages.
Then three select lines were used to control the selection process. Different input combinations were tested to verify correct output.

Secondly, 8 to 3 encoder was implemented. The encoder outputs a 3 bit binary code representing the highest priority active input. Multiple input cases were tested to ensure correct priority behavior.

---

## Circuit Diagram

(Uploaded along with the file)
---

## Observations

1. The multiplexer correctly selected the input based on select lines
2. Hierarchical design using 2:1 MUXes worked efficiently
3. The priority encoder correctly identified the highest-priority input when multiple inputs were active
4. When all inputs were 0, the output remained 0 and the valid signal was inactive
5. The circuits behaved as expected for all tested combinations
---

## Result

The 8:1 Multiplexer and 8:3 Priority Encoder were successfully implemented in Logisim. The outputs matched the expected results for all input combinations.

---

## Conclusion

This experiment helped in understanding the working of multiplexers and priority encoders. It demonstrated how complex digital circuits can be built using smaller modules and highlighted the importance of selection and priority logic in digital systems.
