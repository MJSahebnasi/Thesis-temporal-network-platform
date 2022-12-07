### - *continues* time simulation  
### - need to keep track of *off* nodes

- [ ] Simulation Class:
  - [x] init
    + [ ] when creating each process we need 2 implementations: one with time generator func passed, one with entity-time pairs passed
          overloading?
  - [ ] run
    - [ ] event selector
    - [ ] event executer: implemented inside each event class
    - [ ] snapshot
    - [ ] history ?

- [ ] events:
  - [x] types:
    - [x] node [/edge?] entrance
    - [x] node [/edge?] natural death (end of life span)
    - [x] node [/edge?] sudden death (attack)
    - [x] node [/edge?] on/off
  - [ ] implementation:
    - [ ] node [/edge?] entrance
    - [ ] node [/edge?] natural death (end of life span)
    - [ ] node [/edge?] attack (sudden death)
    - [ ] node [/edge?] on/off

- [ ] produce random nums with specified distribution:  
  - [ ] basic
  - [ ] range (min to max)
  - [ ] traffic generator

