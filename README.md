# core-research

Research and solution sets for the final step of the Neon District puzzle.

### `segments.txt`

#### format

- Each line represents a segment. The first token represents the stroke width of the segment, the second is the 24-bit RGB color as a hexadecimal number. 
- The nth line corresponds with the nth segment. Similarly to the svg, rings are encoded in clockwise ordering. Each ring is comprised of four segments, therefore each ring will be comprised of four lines from the file. For example the firth to the fouth line inclusive will be the first ring, the fifth line to the ninth line will be the second, etc.
- Each line can be preceded by whitespace as the stroke width is right aligned.
