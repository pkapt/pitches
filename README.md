# pitches

convert between scientific pitch notation (SPN) and frequency

## Example

```
from pitches import Converter

c = Converter()
frequency = c.freq("C4")
# >> 523.2511306011972

pitch = c.pitch(100)
# >> 'G2'
