# Manual vs AI-Assisted Test Case Comparison

> Replace blanks with the actual time you measured. Do not claim these values are measured until you have done the work.

| Criterion | Manual test design | AI-assisted test design |
|---|---|---|
| Number of initial cases | 5 | Record the actual number generated |
| Coverage | Core valid flow and common validation/payment failures | Review actual AI output; note additional distinct areas |
| Accuracy | Review against the stated requirement | Check unsupported assumptions, expected results, and duplicates |
| Time taken | ___ minutes | Prompt + generation + review: ___ minutes |
| Final finding | Focused baseline cases | Can accelerate drafting, but human review is required |

## Time saved formula

Time saved (%) = ((manual time - AI-assisted total time) / manual time) × 100

Include prompt preparation, generation, and review in AI-assisted total time. The result may be negative if AI-assisted work takes longer.

## Conclusion

ChatGPT can accelerate initial test case drafting and suggest additional scenarios. Its output must be reviewed for accuracy, duplication, and assumptions that are not supported by the requirement. The QA tester remains responsible for the final test cases.
