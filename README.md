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

<h3 align="center">2X1 MUX 회로 구성</h3>

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

### 4X1 MUX

### 8X1 MUX

### 16X1 MUX
