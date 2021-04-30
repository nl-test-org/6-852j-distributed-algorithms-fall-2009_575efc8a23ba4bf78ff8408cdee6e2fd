---
course_id: 6-852j-distributed-algorithms-fall-2009
layout: course_section
menu:
  leftnav:
    identifier: 4095967616e4d6e0960b171bcb69467b
    name: Assignments
    weight: 50
title: Assignments
type: course
uid: 4095967616e4d6e0960b171bcb69467b

---

Problem Sets
------------

Problem sets are due every two weeks. Full credit is given to solutions that present all the important logical steps and ideas in concise manner.

If you want your solution to be used as an example for the class, we encourage you to use the LaTeX solution template: ([TEX](/coursemedia/6-852j-distributed-algorithms-fall-2009/7097f0cb876168e94df33eb986ac4ab1_sol.tex)) ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_sol))

For some problems, you will be required to submit syntax-checked Tempo code for your distributed algorithms. Information about Tempo can be found in the [Tools]({{< baseurl >}}/sections/tools) section. 

| ASSN # | ASSIGNMENTS | NOTES |
| --- | --- | --- |
| 1 |  {{< br >}}{{< br >}} Part A ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset1a)) {{< br >}}{{< br >}} Part B ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset1b)) {{< br >}}{{< br >}}  | &nbsp; |
| 2 |  {{< br >}}{{< br >}} Part A ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset2a)) {{< br >}}{{< br >}} Part B ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset2b)) {{< br >}}{{< br >}}  | &nbsp; |
| 3 |  {{< br >}}{{< br >}} Part A ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset3a)) {{< br >}}{{< br >}} Part B ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset3b)) {{< br >}}{{< br >}}  | Part B, Problem 4: The question asks for a description of the best algorithm you can devise that solves the k-pseudo-session problem and its worst case time complexity. The time complexity is measured according to T(A) as defined on p. 557 of the textbook. |
| 4 |  {{< br >}}{{< br >}} Part A ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset4a)) {{< br >}}{{< br >}} Part B ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset4b)) {{< br >}}{{< br >}}  | &nbsp; |
| 5 |  {{< br >}}{{< br >}} Part A ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset5a)) {{< br >}}{{< br >}} Part B ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset5b)) {{< br >}}{{< br >}}  | &nbsp; |
| 6 |  {{< br >}}{{< br >}} Part A ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset6a)) {{< br >}}{{< br >}} Part B ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset6b)) {{< br >}}{{< br >}}  | Part A: In an invisible read, the transaction does not write any control information into the shared memory to inform the other transactions on possible read/write conflicts. Hence note that in the context of obstruction-free STM (software transactional memory), invisible reads require a read validation step. |
| 7 | ([PDF]({{< baseurl >}}/sections/assignments/mit6_852jf09_pset7)) |   

### Open Questions

Is it possible to implement a wait-free 3-process FIFO (first-in first-out) queue atomic object using only 2-process consensus objects and any-number-of-process read/write registers?

Problem Set Grading
-------------------

For each problem set, a group of 3-4 students will be responsible for working with the course staff to grade the solutions. If possible, we would like the grading to be completed by the Monday afternoon after the homework assignments are handed in, so that we can record the grades and hand them back on Tuesday. The number of times you have to grade over the course of the semester will depend on the size of the class. Part of your grade will depend on the quality and promptness of your work on problem set grading.