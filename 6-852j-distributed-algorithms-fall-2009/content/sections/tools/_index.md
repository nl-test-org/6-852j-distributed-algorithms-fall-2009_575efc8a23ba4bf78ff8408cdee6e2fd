---
course_id: 6-852j-distributed-algorithms-fall-2009
layout: course_section
menu:
  leftnav:
    identifier: 0da48dce23227545e62749a6d0a030be
    name: Tools
    weight: 60
title: Tools
type: course
uid: 0da48dce23227545e62749a6d0a030be

---

The Tempo Toolkit
-----------------

### Tempo Basics

To precisely model and prove properties of distributed algorithms in an asynchronous network, we introduced Input/Output Automata (IOA) formalism. The Tempo Toolkit is a collection of tools to simplify the process of developing and validating IOA systems. (Tempo actually works with Timed Input/Output Automata, a more powerful version of IOA that includes timing constraints. For our purposes, we will not make use of the timing features.)

The toolkit consists of the Tempo language, which closely matches the format of the pseudocode used in the book to describe IOA, a syntax checker to validate your IOA code, as well as connections to a homegrown simulator, the PVS theorem prover, and the UPAAL model-checker.

### Your Requirements

When specified by the problem set, you will be required to write your distributed algorithm in the Tempo language and validate it with the syntax checker. You will **not** be required to use the other tools included with the toolkit—simulation, theorem proving, model-checking—but are welcome to try if you have some experience with these techniques. We recommend that you experiment with writing your code in Tempo for the relevant questions in Part B of Problem Set 2. We will **require** you to hand in syntax-checked Tempo code starting with Problem Set 3.

### Installing the Tempo Toolkit

Windows, Mac, and Linux versions of the toolkit can be found at [VeroModo](http://www.veromodo.com/). We recommend that you download the version including the Eclipse-based user interface. For this to work, you must have Java version 1.5 or better. The latest versions of Java can be downloaded [here](http://www.java.com/en/download/index.jsp).

Within the install directories see doc/Tempo\_Guide.pdf for an overview of both the TIOA formalism and the Tempo language. The same file is also available here:

The Tempo Language User Guide and Reference Manual ([PDF - 1.0MB]({{< baseurl >}}/sections/tools/mit6_852jf09_tempo_guide)) (Courtesy of Nancy Lynch, Stephen J. Garland, Dilsun Kaynar, Laurent Michel, and Alex Shvartsman. Used with permission.) Section 3 provides some toy examples of TIOA algorithms implemented in Tempo.