Simple single-file key-value database (index + CSV + JSON)

## Structure
0. unique id by line num (?)
1. crc32 hash of index field (binary)
2. index field
3. CSV data
4. JSON data in last CSV field
