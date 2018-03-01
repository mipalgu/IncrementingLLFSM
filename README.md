# IncrementingLLFSM
Examples of the Kripke structures generation for the Incrementing LLFSM.

This repository contains the results from the paper "An OO and Functional Framework For Versatile Semantics Of Logic-Labelled Finite State Machines".  There are three folders:

<dl>
  <dt><strong>single:</strong></dt>
  <dd>Contains Kripke structures for executing a single instance of the Incrementing LLFSM.</dd>
  <dt><strong>multiple:</strong></dt>
  <dd>Contains Kripke structures for executing two Incrementing LLFSMs in round-robin, taking snapshots per ringlet execution. </dd>
  <dt><strong>multiple_single_snapshot:</strong></dt>
  <dd>Contains Kripke structures for executing two Incrementing LLFSMs taking a snapshot per schedule cycle, as opposed to per ringlet.</dd>
</dl>

Each folder contains a .gv file which is a graphviz file in the dot format, a pdf, and a .smv file which can be used by NuSMV.
