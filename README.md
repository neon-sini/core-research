# core-research

Research and solution sets for the final step of the Neon District puzzle.

## Files

### `segments.txt`

#### Format

- Each line represents a segment. The first token represents the stroke width of the segment, the second is the 24-bit RGB color as a hexadecimal number. 
- The n-th line corresponds with the nth segment. Similarly to the svg, rings are encoded in clockwise ordering. Each ring is comprised of four segments, therefore each ring will be comprised of four lines from the file. For example the firth to the fouth line inclusive will be the first ring, the fifth line to the ninth line inclusive will be the second, etc.
- Each line can be preceded by whitespace as the stroke width is right aligned with other stroke width properties.

### 'puzzle.svg'

#### Format

- The rings of the puzzle are encoded from the inside to outside. 
- The first segment of a n-th ring is rotated by `(n * 2 * pi/16)`. Every segment is then aligned with the first, being ordered from that point on clockwise. 

## Segments

### Colors

|enumeration|hexadecimal|color|
|-----------|-----------|-----|
|A|#335533|dark-green|
|B|#884466|magenta|
|C|#668844|light-green|
|D|#446688|blue|

### Sizes

|enumeration|stroke width|
|-|-|
|E|5|
|F|10|
|G|15|
|H|20|

## Notes
