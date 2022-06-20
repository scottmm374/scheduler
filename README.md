# Scheduler

<!-- [url to video demo] -->

## Description

    Scheduler for shift work. (ADD MORE LATER)

## Specifications

- 8 operators
- 4 with Boiler Lisense(BLOP), 4 without(OP)
- 12 hours shifts 5:30-5:30
- require 1 BLOP operator on each shift woth 1 OP.
- work rotation
  - 36 hour / 48 hour rotating weeks
  - night shift/ day shift rotation every week
- Schedule runs Monday-Sunday

  - Max 6 days a week
  - Min 36 hours a week
  - Max 14 days in a row with 36 hours off
  - Max 16 hours straight with min 8 hours off in between shifts
  - On call Operators that are coming off day shift.

- Time off

  - BLOP = 13 Vacation days 40hours sick, and 3 floating holidays
  - OP no BL = 7 days vacation, 40 hours sick and 3 float holidays

- Potential issues disrupt schedule

  - Plant trips
    - Min 3 days
    - Everyone comes in, 12 hour shifts 4 each shift
  - Weather

    - 3 consecutive days below 20, requires 3 people on shift. 1 BLOP 1 OP and 1 Any position
    - watched and adjusted a week before.

  - Injury to an OP or promoted OP to another plant, or OP quits

## TODO

### Functionality

- [ ] Create Employees with information - [ ] First name - [ ] Last name - [ ] position - [ ] Bool Boiler Lisense - [ ] Vacation days available - [ ] sick days available - [ ] Wants OT bool

- [ ] Create a dataset to track all hours worked, for each operator.
- [ ] Create data set for accumulated data?
- [ ] Track days per week scheduled

### Tests-edgecases

- [ ] 7 day workweek (not allowed)
- [ ] Max hours worked in day (No more then 16) - min 8 hours off
- [ ] max consecutive days (14) - min 36 hours off
- [ ] Check that 1 BLOP and 1 OP on all shifts
- [ ] Check rotations 36/48 minimum
- [ ] check rotations night/days equal

## Considerations

- Decide how to visually represent schedule
- Decide how to recieve input? CL or create a simple gui?
- Pandas?
- Datetime module
