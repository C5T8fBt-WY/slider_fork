Forked from [llllllllll/slider](https://github.com/llllllllll/slider)

## Changes list
- batch calculation of slider midpositions, for data science purposes etc.
- fix wrong result of midposition calculation for reverse sliders
- fix parsing error of `HoldNote`

## Files changed
- beatmap.py
  - Slider
    - [x] get_edgetimes
    - [x] calc_position_at
  - HoldNote
    - [x] _parse
- curve.py
  - [x] implement `at()` for each `Curve`