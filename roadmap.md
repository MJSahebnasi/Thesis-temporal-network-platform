### - *continues* time simulation  
### - need to keep track of *off* nodes

- [ ] Simulation Class:
  - [x] init simulation
    - [ ] report: outcome/snapshot/full
  - [ ] create events
  - [ ] run
    - [ ] event selector: heap
    - [ ] event executer: implemented inside each event class

- [ ] events:
  - [x] types:
    - [x] node [/edge?] entrance
    - [x] node [/edge?] natural death (end of life span)
    - [x] node [/edge?] sudden death (attack)
    - [x] node [/edge?] on/off
  - [ ] implementation: event.execute()
    - [ ] node [/edge?] entrance
    - [ ] node [/edge?] natural death (end of life span)
    - [ ] node [/edge?] attack (sudden death)
    - [ ] node [/edge?] on/off

