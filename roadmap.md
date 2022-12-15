### - *continues* time simulation  
### - need to keep track of *off* nodes

events:
  - [x] types:
    - [x] node [/edge?] entrance
    - [x] node [/edge?] natural death (end of life span)
    - [x] node [/edge?] sudden death (attack)
    - [x] node [/edge?] on/off
  - [ ] implementation: event.execute()
    - [ ] redesign neighbors for entrance & on

Simulation Class:
  - [x] init simulation
    - [ ] report: outcome/snapshot/full
  - [x] create events
  - [ ] run
    - [x] event selector: heap
    - [x] event executer: use the implementation inside each event class
  
