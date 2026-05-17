### About the test files:
The test files generated are stored in the tests directory, they have a unified naming convention according to the size of the sets that the file contains.
Each file has 30 random instances of the subset sum problem (random target sum and random set of the same size)

#### General Test File (initial_general_tests.txt):
A consolidated test file containing 15 random tests of **varying sizes** (sizes 1–18). This file is useful for quick smoke testing and performance validation across different problem sizes in a single test run.

### How to parse the files:

**Uniform test files (uniform_test_sizeN.txt):**
```text
line 1: number_of_instances (always 30)
then the following pattern begins: 

line 2: target_sum
line 3: space_separated_numbers_of_size_specified_by_file
...
```

**General test file (initial_general_tests.txt):**
```text
line 1: number_of_tests (always 15)
then for each test, the following pattern repeats:

line 1: test_size (size of the set, varies 1-18)
line 2: target_sum
line 3: space_separated_numbers_of_the_multiset
...
```
