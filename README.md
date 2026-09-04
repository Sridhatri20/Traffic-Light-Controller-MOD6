# Traffic Light Controller Using MOD-6 Counter

## 📌 Project Overview

This project implements a **digital traffic light controller using a MOD-6 counter and sequential logic**. The circuit was designed and simulated using **SimulIDE** to control the sequence of traffic signal states.

The controller uses **flip-flops, logic gates, and K-map optimized logic** to generate the required sequence of traffic light states. The simulation was used to verify the state transitions, timing sequence, and cyclic operation of the controller.

## 🎯 Objectives

* Design a digital traffic light controller using a **MOD-6 counter**.
* Implement sequential logic using **flip-flops and logic gates**.
* Derive and simplify the required logic using **Karnaugh Maps (K-maps)**.
* Simulate the complete circuit using **SimulIDE**.
* Verify the correct state transitions and cyclic operation of the traffic signals.

## 🛠️ Software Used

* **SimulIDE**

## 🔧 Components / Concepts Used

* MOD-6 Counter
* Flip-Flops
* Logic Gates
* Karnaugh Map (K-map)
* Clock Signal
* Digital Logic
* Sequential Logic
* Traffic Light Signals

## ⚙️ Working Principle

The traffic light controller operates as a **sequential digital circuit**.

A clock signal drives the counter, and the **MOD-6 counter cycles through six distinct states**. Each state represents a particular stage of the traffic signal sequence.

The outputs of the counter are processed using logic gates to generate the required traffic light signals. K-map simplification is used to obtain optimized Boolean expressions for the required logic.

After reaching the sixth state, the counter returns to the initial state, making the operation **cyclic**.

### Basic Operation

```text
Clock
  ↓
MOD-6 Counter
  ↓
State Generation
  ↓
Logic Gates
  ↓
Traffic Light Outputs
  ↓
Next State
  ↺
```

## 📊 State Sequence

The controller passes through six states:

| State | Counter State | Traffic Signal |
| ----: | :-----------: | -------------- |
|     0 |      000      | State 1        |
|     1 |      001      | State 2        |
|     2 |      010      | State 3        |
|     3 |      011      | State 4        |
|     4 |      100      | State 5        |
|     5 |      101      | State 6        |

After State 5, the counter returns to **000**, and the sequence repeats.

> The exact output combination for each state depends on the logic implemented in the simulated circuit.

## 🧮 Logic Design

The sequential logic was developed using flip-flops and logic gates.

Karnaugh Maps were used to simplify the Boolean expressions obtained from the required state/output combinations. The simplified expressions were then implemented using logic gates in SimulIDE.

## 🖥️ Simulation

The complete circuit was implemented and tested in **SimulIDE**.

The simulation was used to verify:

* Correct counter operation
* State transitions
* Traffic signal sequencing
* Cyclic operation
* Correct logic output for each state

### Circuit Diagram
<img width="1170" height="770" alt="image" src="https://github.com/user-attachments/assets/260f6fdb-d724-4711-8cd5-c1304dbf224e" />



## ✅ Result

The traffic light controller was successfully designed and simulated using a **MOD-6 counter and sequential digital logic**. The simulation verified the required state transitions and cyclic operation of the traffic signal controller.

## 📚 Concepts Learned

Through this project, the following concepts were applied:

* Sequential circuit design
* MOD-N counters
* Flip-flops
* Logic gates
* State transitions
* Karnaugh Map simplification
* Digital circuit simulation
* Timing and cyclic operation

## 🚀 Future Improvements

The project can be further extended by:

* Adding pedestrian crossing control
* Adding emergency vehicle priority
* Implementing adjustable timing for each signal
* Extending the controller for multiple road intersections

## 👩‍💻 Author

**Sridhatri Gunupuru**
B.Tech – Electrical Engineering
National Institute of Technology Rourkela

