Forked from [llllllllll/slider](https://github.com/llllllllll/slider)

## Changes list
- batch calculation of slider midpositions, for data science purposes etc.
- fix wrong result of midposition calculation for reverse sliders
- fix parsing error of `HoldNote`

## Files changed
- beatmap.py
  - Slider
    - [ ] get_edgetimes
    - [ ] calc_position_at
  - HoldNote
    - [ ] _parse
- curve.py
  - implement `at()` for each `Curve`s