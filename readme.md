# Sequence Padding

## What it can do?

* Pad a varible length list with 0
* Return each sub-sequence's length
* Supporting list with max dims/depth >= 2

## Usage
Inputs:
```
seq = [[[1, 2, 3], [4, 5, 6, 7]],
       [[1], ],
       [[7, 8, 9], [10, 11]]]
```

Outputs:
```
padded_seq = [[[1, 2, 3, 0], [4, 5, 6, 7]],
              [[1, 0, 0, 0], [0, 0, 0, 0]],
              [[7, 8, 9, 0], [10, 11, 0, 0]]]
              
lengths = [3, 4, 1, 0, 3, 2]
```
