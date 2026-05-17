### About the test files:
The test files generated are stored in the tests directory, they have a unified naming convention according to the size of the sets that the file contains.
Each file has 30 random instances of the subset sum problem (random target sum and random set of the same size)

### How to parse the files:
Here is the format of the test files:

```text
line 1: number_of_instances (always 30)
then the following pattern begins: 

line 2: target_sum
line 3: space_separated_numbers_of_size_specified_by_file
...
