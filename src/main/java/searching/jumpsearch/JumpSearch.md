### `JumpSearch.md`

```markdown
# Jump Search

Jump Search is an algorithm for searching an element in a sorted array. The basic idea is to divide the array into blocks of fixed size and perform a linear search within each block. The optimal block size is the square root of the array's length.

## Algorithm Steps

1. **Choose a block size**: The optimal block size is generally the square root of the array's length (`m = √n`).
2. **Jump through blocks**: Start at the first element of each block and jump to the next block until you find a block where the target element could be located.
3. **Linear search within the block**: Perform a linear search within the identified block to find the target element.

## Complexity

- **Time Complexity**: O(√n)
- **Space Complexity**: O(1)

