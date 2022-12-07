### - *continues* time simulation  
### - need to keep track of *off* nodes

- [ ] produce random nums with specified distribution:  
  - [ ] basic
  - [ ] range (min to max)
  - [ ] traffic generator

- [ ] events:
  - [ ] types:
    - [ ] node [/edge?] entrance
    - [ ] node [/edge?] natural death (end of life span)
    - [ ] node [/edge?] sudden death (attack)
    - [ ] node [/edge?] on/off
  - [ ] implementation:
    - [ ] for each process we need 2 implementations: 
          one with time generator func passed, one with entity-time pairs passed
          overloading?
    - [ ] node [/edge?] entrance
    - [ ] node [/edge?] natural death (end of life span)
    - [ ] node [/edge?] attack (sudden death)
    - [ ] node [/edge?] on/off

- [ ] event executer:
  - [ ] DS: heap?

- [ ] snapshot
- [ ] history ?
