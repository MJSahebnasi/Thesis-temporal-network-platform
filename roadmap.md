## events:
  - [x] types:
    - [x] node [/edge?] entrance
    - [x] node [/edge?] natural death (end of life span)
    - [x] node [/edge?] sudden death (attack)
    - [x] node [/edge?] on/off
  - [x] implementation: event.execute()
    - [x] node [/edge?] entrance
    - [x] node [/edge?] natural death (end of life span)
    - [x] node [/edge?] sudden death (attack)
    - [x] node [/edge?] on/off

## Simulation Class:
  - [x] init simulation
  - [x] create events
  - [x] run
    - [x] event selector: heap
    - [x] event executer: use the implementation inside each event class
  - [ ] report: 
    - [x] outcome
    - [ ] snapshot: change in design required: must add off_nodes, time, ... to the snapshot report
   
## Auxiliary:
  - [ ] graphic reports?
  - [ ] advanced input validation

## TEST
  - [ ] functional tests
  - [ ] performance tests
  
## DOC website

## Release
