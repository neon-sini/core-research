# core-research

Research and solution sets for the final step of the Neon District puzzle.

## Files

### `segments.txt`

#### Format

- Each line represents a segment. The first token represents the stroke width of the segment, the second is the 24-bit RGB color as a hexadecimal number. 
- The n-th line corresponds with the nth segment. Similarly to the svg, rings are encoded in clockwise ordering. Each ring is comprised of four segments, therefore each ring will be comprised of four lines from the file. For example the firth to the fouth line inclusive will be the first ring, the fifth line to the ninth line inclusive will be the second, etc.
- Each line can be preceded by whitespace as the stroke width is right aligned with other stroke width properties.

## Segments

### Colors

|hexadecimal|color|
|-----------|-----|
|#335533|dark-green|
|#884466|magenta|
|#668844|light-green|
|#446688|blue|

### Sizes

|stroke width|
|----|
|5|
|10|
|15|
|20|

## Notes
