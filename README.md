# core-research

Research and solution sets for the final step of the Neon District puzzle.

## Files

### `segments.txt`

#### Format

- Each line represents a segment. The first token represents the stroke width of the segment, the second is the 24-bit RGB color as a hexadecimal number. 
- The n-th line corresponds with the nth segment. Similarly to the svg, rings are encoded in clockwise ordering. Each ring is comprised of four segments, therefore each ring will be comprised of four lines from the file. For example the firth to the fouth line inclusive will be the first ring, the fifth line to the ninth line inclusive will be the second, etc.
- Each line can be preceded by whitespace as the stroke width is right aligned with other stroke width properties.

### `puzzle.svg`

#### Format

- The rings of the puzzle are encoded outward from the center. 
- The first segment of a n-th ring is rotated clockwise by `(n * 2 * pi/16)`.

## Segments

### Dunno

|Track|0|1|2|3|
|-|-|-|-|-|
|0|AA|BD|BA|BD|
|1|DC|CD|DA|DD|
|2|BB|CA|AB|BC|
|3|CC|CC|BA|CC|
|4|BD|AA|BC|CB|
|5|DA|AB|DD|DD|
|6|AB|CA|DC|BB|
|7|CC|DB|BC|AD|
|8|DD|DC|CB|CD|
|9|CB|AB|BD|BA|
|A|AB|AA|BA|AC|
|B|BD|CA|AD|DB|
|C|DB|CD|CA|AD|
|D|DD|AD|DB|DB|
|E|BC|BB|CC|BD|
|F|CA|CB|AC|CA|


### Colors

|enumeration|hexadecimal|color|
|-----------|-----------|-----|
|A|#335533|dark-green|
|B|#446688|blue|
|C|#884466|magenta|
|D|#668844|light-green|

### Sizes

|enumeration|stroke width|
|-|-|
|A|5|
|B|10|
|C|15|
|D|20|

## Notes
