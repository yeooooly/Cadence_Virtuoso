# Virtuoso

## 목차

1. [NOT Gate](#1-not-gate)
2. [NAND Gate](#2-nand-gate)
   - [2-input NAND Gate](#2-input-nand-gate)
   - [3-input NAND Gate](#3-input-nand-gate)
   - [4-input NAND Gate](#4-input-nand-gate)
3. [NOR Gate](#3-nor-gate)
   - [2-input NOR Gate](#2-input-nor-gate)
   - [3-input NOR Gate](#3-input-nor-gate)
   - [4-input NOR Gate](#4-input-nor-gate)
4. [Switch](#4-switch)
5. [MUX](#5-mux)
   - [2X1 MUX](#2x1-mux)
   - [4X1 MUX](#4x1-mux)
   - [8X1 MUX](#8x1-mux)
   - [16X1 MUX](#16x1-mux)
   - [MUX 비교](#mux-비교-logic-vs-switch)
6. [ADDER](#6-adder)
   - [XOR Gate](#xor-gate)
   - [Half Adder](#half-adder)
   - [Full Adder](#full-adder)

---

## 1. NOT Gate

<h3 align="center">NOT Gate 회로 구성</h3>

<p align="center">
  <img src="img/NOT_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/F2.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/F3.png" width="90%">
</p>

<p align="center">
PMOS Width 시뮬레이션한 결과, <b>2.91u</b>일 때 가장 안정적으로 동작
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/NOT_LAY.png" width="45%">
</p>

<p align="center">
Size : 1.16um x 5.84um
</p>

## 2. NAND Gate

### 2-input NAND Gate

<h3 align="center">2-input NAND Gate 회로 구성</h3>

<p align="center">
  <img src="img/2NAND.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/2NAND_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/2NAND_SIM.png" width="90%">
</p>

<p align="center">
PMOS Width 시뮬레이션한 결과, <b>2.53u</b>일 때 가장 안정적으로 동작
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/2NAND_LAY.png" width="45%">
</p>

<p align="center">
Size : 1.36um x 5.6um
</p>

### 3-input NAND Gate

<h3 align="center">3-input NAND Gate 회로 구성</h3>

<p align="center">
  <img src="img/3NAND_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/3NAND_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/3NAND_SIM.png" width="90%">
</p>

<p align="center">
PMOS Width 시뮬레이션한 결과, <b>2.31u</b>일 때 가장 안정적으로 동작
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/3NAND_LAY.png" width="45%">
</p>

<p align="center">
Size : 1.78um x 5.62um
</p>

### 4-input NAND Gate

<h3 align="center">4-input NAND Gate 회로 구성</h3>

<p align="center">
  <img src="img/4NAND_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/4NAND_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/4NAND_SIM.png" width="90%">
</p>

<p align="center">
PMOS Width 시뮬레이션한 결과, <b>2.135u</b>일 때 가장 안정적으로 동작
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/4NAND_LAY.png" width="45%">
</p>

<p align="center">
Size : 2.2um x 5.685um
</p>

## 3. NOR Gate

### 2-input NOR Gate

<h3 align="center">2-input NOR Gate 회로 구성</h3>

<p align="center">
  <img src="img/2NOR_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/2NOR_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/2NOR_SIM.png" width="90%">
</p>

<p align="center">
PMOS Width 시뮬레이션한 결과, <b>3.99u</b>일 때 가장 안정적으로 동작
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/2NOR_LAY.png" width="45%">
</p>

<p align="center">
Size : 1.36um x 7.06um
</p>

### 3-input NOR Gate

<h3 align="center">3-input NOR Gate 회로 구성</h3>

<p align="center">
  <img src="img/3NOR_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/3NOR_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/3NOR_SIM.png" width="90%">
</p>

<p align="center">
PMOS Width 시뮬레이션한 결과, <b>5u</b>일 때 가장 안정적으로 동작
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/3NOR_LAY.png" width="45%">
</p>

<p align="center">
Size : 1.78um x 8.31um
</p>

### 4-input NOR Gate

<h3 align="center">4-input NOR Gate 회로 구성</h3>

<p align="center">
  <img src="img/4NOR_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/4NOR_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/4NOR_SIM.png" width="90%">
</p>

<p align="center">
PMOS Width 시뮬레이션한 결과, <b>5.95u</b>일 때 가장 안정적으로 동작
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/4NOR_LAY.png" width="45%">
</p>

<p align="center">
Size : 2.2um x 9.51um
</p>

## 4. Switch

<h3 align="center">Switch 회로 구성</h3>

<p align="center">
  <img src="img/SW_SCH.png" width="60%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/SW_LAY.png" width="45%">
</p>

## 5. MUX

### 2X1 MUX

#### Logic

<h3 align="center">2X1 MUX (Logic) 회로 구성</h3>

<p align="center">
  <img src="img/21MUX_LOG_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/21MUX_LOG_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/21MUX_LOG_SIM.png" width="90%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/21MUX_LOG_LAY.png" width="85%">
</p>

<p align="center">
Size : 4.63um x 5.87um
</p>

#### Switch

<h3 align="center">2X1 MUX (Switch) 회로 구성</h3>

<p align="center">
  <img src="img/21MUX_SW_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/21MUX_SW_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/21MUX_SW_SIM.png" width="90%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/21MUX_SW_LAY.png" width="35%">
</p>

<p align="center">
Area : <b>16.56 µm²</b>
</p>

### 4X1 MUX

#### Logic

<h3 align="center">4X1 MUX (Logic) 회로 구성</h3>

<p align="center">
  <img src="img/41MUX_LOG_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/41MUX_LOG_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/41MUX_LOG_SIM.png" width="90%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/41MUX_LOG_LAY.png" width="85%">
</p>

<p align="center">
Area : <b>100.86 µm²</b>
</p>

#### Switch

<h3 align="center">4X1 MUX (Switch) 회로 구성</h3>

<p align="center">
  <img src="img/41MUX_SW_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/41MUX_SW_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/41MUX_SW_SIM.png" width="90%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/41MUX_SW_LAY.png" width="50%">
</p>

<p align="center">
Area : <b>52.52 µm²</b>
</p>

### 8X1 MUX

#### Logic

<h3 align="center">8X1 MUX (Logic) 회로 구성</h3>

<p align="center">
  <img src="img/81MUX_LOG_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/81MUX_LOG_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/81MUX_LOG_SIM.png" width="90%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/81MUX_LOG_LAY.png" width="90%">
</p>

<p align="center">
Area : <b>272.45 µm²</b>
</p>

#### Switch

<h3 align="center">8X1 MUX (Switch) 회로 구성</h3>

<p align="center">
  <img src="img/81MUX_SW_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/81MUX_SW_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/81MUX_SW_SIM.png" width="90%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/81MUX_SW_LAY.png" width="70%">
</p>

<p align="center">
Area : <b>135.66 µm²</b>
</p>

### 16X1 MUX

#### Logic

<h3 align="center">16X1 MUX (Logic) 회로 구성</h3>

<p align="center">
  <img src="img/161MUX_LOG_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/161MUX_LOG_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/161MUX_LOG_SIM.png" width="90%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/161MUX_LOG_LAY.png" width="100%">
</p>

<p align="center">
Area : <b>741.90 µm²</b>
</p>

#### Switch

<h3 align="center">16X1 MUX (Switch) 회로 구성</h3>

<p align="center">
  <img src="img/161MUX_SW_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/161MUX_SW_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/161MUX_SW_SIM.png" width="90%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/161MUX_SW_LAY.png" width="90%">
</p>

<p align="center">
Area : <b>310.02 µm²</b>
</p>

### MUX 비교 (Logic vs Switch)

<div align="center">

| Area (µm²) | 2X1 MUX | 4X1 MUX | 8X1 MUX | 16X1 MUX |
|:---:|:---:|:---:|:---:|:---:|
| Logic | 27.18 | 100.86 | 272.45 | 741.90 |
| Switch | 16.56 | 52.52 | 135.66 | 310.02 |
| Ratio | 1.64 | 1.92 | 2.01 | 2.39 |

| Transistor 수 | 2X1 MUX | 4X1 MUX | 8X1 MUX | 16X1 MUX |
|:---:|:---:|:---:|:---:|:---:|
| Logic | 14 | 42 | 98 | 210 |
| Switch | 6 | 16 | 38 | 78 |

</div>

<p align="center">
Switch(Transmission Gate) 방식이 Logic 방식보다 트랜지스터 수와 면적이 적고, 입력이 많아질수록 차이가 커짐
</p>

## 6. ADDER

<p align="center">
<b>Half Adder</b> : 1-bit 입력 A, B를 더함 &nbsp;→&nbsp; S = A ⊕ B, &nbsp;C = A · B<br>
<b>Full Adder</b> : A, B와 carry-in(Cin)을 더함 (Half Adder 2개 + OR 게이트) &nbsp;→&nbsp; S = A ⊕ B ⊕ Cin, &nbsp;Cout = AB + Cin(A ⊕ B)
</p>

### XOR Gate

<h3 align="center">XOR Gate 회로 구성</h3>

<p align="center">
  <img src="img/XOR_SCH.png" width="60%">
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/XOR_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/XOR_SIM.png" width="90%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/XOR_LAY.png" width="40%">
</p>

<p align="center">
Size : 2.56um x 6.5um
</p>

### Half Adder

<h3 align="center">Half Adder 회로 구성</h3>

<p align="center">
  <img src="img/HALFADDER_SCH.png" width="60%">
</p>

<p align="center">
S = A ⊕ B, &nbsp;C = A · B
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/HALFADDER_TB.png" width="90%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/HALFADDER_SIM.png" width="90%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/HALFADDER_LAY.png" width="45%">
</p>

<p align="center">
Area : 4.6um x 6.5um = <b>29.9 µm²</b>
</p>

### Full Adder

<h3 align="center">Full Adder 회로 구성</h3>

<p align="center">
  <img src="img/FULLADDER_SCH.png" width="80%">
</p>

<p align="center">
S = A ⊕ B ⊕ Cin, &nbsp;Cout = AB + Cin(A ⊕ B)
</p>

<h3 align="center">Symbol &amp; Test Bench</h3>

<p align="center">
  <img src="img/FULLADDER_TB.png" width="70%">
</p>

<h3 align="center">Simulation</h3>

<p align="center">
  <img src="img/FULLADDER_SIM.png" width="90%">
</p>

<h3 align="center">Layout</h3>

<p align="center">
  <img src="img/FULLADDER_LAY.png" width="70%">
</p>
