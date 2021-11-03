# BRICK-2.0
**BRICK**: A Bounded Verifier for C code

## Introduction
**BRICK** is a bounded reachability checker for numerically intensive C code, with special emphasis on handling nonlinear operations. It supports user-speciﬁed safety speciﬁcation checking as well as built-in assertionchecking.

Diﬀerent from the existing tools, **BRICK** supports the checking of codes with nonlinear operations. e.g. trigonometric functions, exponential functions by delta-decision SMT solver dReal. **BRICK** has scaled well on realistic programs in evaluation, e.g. the benchmarks in SV-Comp.


**BRICK** returns the check result and generates a *Witness* file which shows the detailed information, e.g. the counter-example which triggers the assert statement.

---

## Install
`zip -s0 brickPart.zip --out brick.zip`

and

`unzip brick.zip`

---

## Usage

**BRICK** verifies with following command in the standard unix command-line style:

`cd brick`

&&

`./bin/brick < filename > -b < bound > -p < precision > [-options].`

---

## Team Members
Lei Bu, Zhunyi Xie and Xiao Guo
