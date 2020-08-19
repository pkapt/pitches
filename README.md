# pitches

convert between scientific pitch notation (SPN) and frequency

## installation

this module is hosted on PyPi, so it can be installed with `pip install pitches`

## requirements

Should work with Python 2.7, or any Python 3

## Example

```
from pitches import Converter

c = Converter()
frequency = c.freq("C4")
# >> 523.2511306011972

pitch = c.pitch(100)
# >> 'G2'
