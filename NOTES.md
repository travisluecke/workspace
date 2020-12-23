# Notes
pc
- id
- name
- ...

campaign
- id
- [pc]

npc 
- id
- disposition

encounters
- id
- name
- [npcs]

combat tracker
- id
- campaignid
- Layer action
- Status
- Active players
- Per-entity:
  - id
  - Automatic dis/advantages  
  - Hidden (Bystander)
  - Conditions (...)
  - Initiative roll
  - Name
  - Concentration flag
  - Status
  - AC
  - HP/Max
  - Actions
  - Apply damage/healing
    - Calculate concentration DC
  - Spells
    - DCs
