Psychometrics
=============

Test logic
----------

- Contingent questions
    - Should be able to specify questions to skip, contingent upon having given
      a certain response to an earlier question

- Contingent instructions
    - Should be able to give an instruction that refers directly to a previous
      response (for example, ‘You responded X to question 1; please describe how
      this affects you’)

- Completion
    - Should indicate progress to test-taker
    - Should enforce completion of every question before submission is allowed
        - May still be useful to record partially-completed tests

Response types
--------------

- Text (single- or multi-line)
- Number (optionally with unit)
- Mutually-exclusive options
    - Response selected with a radio button
    - Special case: yes / no may be represented with a checkbox
- Rank for each of a number of items
    - Typically must give a total order
    - Ordering may be over a subset of the items presented
- Value on a scale
    - Typically a linear scale
    - Points on the scale may be labelled
    - Some items may be reverse-scored
