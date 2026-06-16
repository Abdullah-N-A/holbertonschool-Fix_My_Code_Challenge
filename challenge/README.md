# Fix My Code Challenge

A series of debugging challenges across multiple programming languages.

## Tasks

### 0. FizzBuzz (`0-fizzbuzz.py`)
Python implementation of FizzBuzz. Fixed condition order so multiples of both 3 and 5 correctly print `FizzBuzz`.

### 1. Print square (`1-print_square.js`)
Node.js script that prints a square of `#` characters. Fixed `parseInt` radix from `16` to `10`.

### 2. Sort (`2-sort.rb`)
Ruby script that sorts integer arguments in ascending order. Fixed insert index from `i - 1` to `i`.

### 3. User password (`3-user.py`)
Python `User` class with MD5-hashed passwords. Fixed name mangling bug in setter (`_password` → `__password`) and case mismatch in `is_valid_password` (`.upper()` → `.lower()`).

### 4. Double linked list (`4-delete_dnodeint/`)
C implementation of a doubly linked list. Fixed `delete_dnodeint_at_index` to correctly update `prev->next` (not `prev->prev`) and free the node only after pointer updates.
