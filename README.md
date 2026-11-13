# DSA01-192411215-Assignment1 (C++)

- **Name:** Dhanush Kumar R
- **Register number:** 192411215


## Tasks
| Task | Files | Result |
|---|---|---|
| 1 OO analysis | `Task01/main.cpp` | Objects, encapsulation, polymorphism; rule R1 holds |
| 2 Tokens/constants | `Task02/main.cpp` | Macro bug `DOUBLE_IT(1+2)=5`; enum class needs cast |
| 3 Data types | `Task03/main.cpp` | sizeof/ranges; double error grows with n; int overflows at 3M journeys |
| 4 Implicit conversions | `Task04/predict.cpp`, `fixed.cpp` | Prediction vs actual; sign-compare warning; fixed with casts/braces |
| 5 Precedence | `Task05/predict.cpp`, `peak_check.cpp` | Prediction vs actual; table lookup equals expression |
| 6 Control structures | `Task06/complete_code.cpp`, `peak_boundary.cpp`, `pseudocode.txt` | Matches expected output; 10:00 and 20:00 are off-peak |
| 7 Procedural vs OOP | `Task07/*.cpp` | Procedural/public balance can go negative; OOP cannot |
| 8 Input/output | `Task08/main.cpp`, `getline_version.cpp` | Recovers from letters and out-of-range input |
| 9 Implementation & tests | `Task09/main.cpp` | 22/22 tests pass |
| 10 Expectation vs execution | `Task10/main.cpp` | Double drifts, int overflows at 3M, long long exact |
| 11 Final design | `Task11/main.cpp`, `fares.cfg` | constexpr defaults + config file override |
| 12 Design challenge | `Task12/main.cpp`, `analysis.md` | MODIFY: zone table, discount rule, Pass class; 11/11 tests pass |

# DSA01-192411215-Assignment2 (CO2)

- **Name:** Dhanush Kumar R
- **Register number:** 192411215


## Tasks
| Folder | Files | Result (fill in) |
|---|---|---|
| Q1 | three_ways, predict_output, complete_code | |
| Q2 | marks_register, dangling_reference, vector_invalidation, alt_index_pointer | |
| Q3 | ambiguous_error (fails on purpose), courier, alt_parcel_template | |
| Q4 | account_shift, account_circular, account_deque | |
| Q5 | predict_output, complete_code, tickets_in_function, alt_ticket_office | |
| Q6 | complete_code, correctness_tests, inline_benchmark | |
| Q7 | redesign_benchmark, REPORT_NOTES.md | |

# DSA01-192411215-Assignment3

**Name:** Dhanush Kumar R  **Register No:** 192411215
**Course:** C++ OOP - Assignment 3 (CO3): Constructors, Destructors and Operator Overloading

## Compiler
`g++ --version` -> (paste your version here, e.g. g++ 13)

## Compile command
```
g++ -std=c++17 -Wall -Wextra <file>.cpp -o <name>
```
Sanitizer builds add `-fsanitize=address -g`; timing builds add `-O0` or `-O2`.

## How to run everything
```
bash run_all.sh
```
Or one program at a time, e.g. `g++ -std=c++17 -Wall -Wextra Q1/book.cpp -o q1 && ./q1`

## Tasks
| Folder | Files | Result (fill in after running) |
|---|---|---|
| Q1 | book.cpp, no_default_ctor.cpp, reorder_demo.cpp, explicit_demo.cpp, book_default_args.cpp | |
| Q2 | prescription_shallow.cpp, prescription_deep.cpp, prescription_experiments.cpp, prescription_vector.cpp | |
| Q3 | auditorium.cpp, auditorium_leak.cpp, logger_predict.cpp, seatmap_alternatives.cpp | |
| Q4 | money_complete.cpp, money_full.cpp, money_friend_vs_member.cpp | |
| Q5 | time_playlist.cpp, counter_predict.cpp, timing.cpp | |
| Q6 | Text.h, text_main.cpp, text_compare.cpp | |
| Q7 | complex_rlc.cpp | |

Notes: some programs are SUPPOSED to fail (no_default_ctor.cpp, explicit_demo.cpp with -DUSE_EXPLICIT,
money_friend_vs_member.cpp with -DMEMBER_ONLY, prescription_shallow.cpp under ASan). Screenshot those errors.
To see every copy in Q6 (a+b+c), also compile with `-fno-elide-constructors`.



