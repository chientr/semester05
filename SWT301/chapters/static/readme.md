# Static techniques
```
Static techniques do not execute code
```
## Review and test process
* People techniques
    * Individual
        * desk-checking
        * data-stepping
        * proof-reading
    * Group
        * Review for consensus
        * Walkthrough for education
        * Inspection to find faults
* Benefits
    * Productivity improve
    * Reduced timescales
    * Reduced testing time and cost
    * Lifetime cost reduction
    * Reduced fault levels
    * Improved customer relations
* Inspect condition
    * Anything written down can be inspected
* Review condition
    * Anything can be inspected

## Review types
* Informal Review: undocumented
* Technical Review: by technical expert, no need of management participation
* Decision-making Review: group discuss on documents
* Walkthrough: author educate people
* Inspection:
    * Using processes and standards to find faults.
    * Certificate required
    * Entry/Exit criteria

## Objective/goals
* V & V
* Achieve consensus
* Process imrpovement

## Activities
* Planning
* Kick-off: roles and responsibilities
* Individual preparation
* Review meeting
* Rework
* Follow-up

## Roles & Responsibilities
* Leader/moderator planning
* Reviewer/inspector executing
* Manager (optional) planning, too

## Deliverables
* Changes in Review
* Change request for source documents
* Process imrpovement suggestion
* Metrics

## Pitfall
* Lack of training
* Lack of documenting
* Lack of management support - "lip service"
* Failure to improve processes

```
Inspection can find deep-seated faults
```

## Static analysis
* Data flow analysis
    * The study of program variables
    * Examples
        * re-defined without being used variables
        * used before defined
* Control flow analysis
    * Unreachable code
    * Infinite loops
    * Multiple entry to loops
    * Reducible code
    * Conform to a flowchart
    * Jump to undefined labels
    * Labels to which jumping
    * Cyclomatic complexity and other metrics
        * LOC
        * operands & operators (Halstead's metrics)
        * fan-in & fan-out
        * nesting levels
        * function calls
        * OO metrics: inheritance tree depth, number of methods, coupling & cohesion
* Limitations
    * Does not execute code
* Advantages
    * Can find deep-seated fault
    * Give objective quality assessment of code