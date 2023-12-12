Pair: whimsical-wolves \
Commit: [c4a03784723fb0c099a7a22c66c421a1f0613e7f](https://github.khoury.northeastern.edu/CS4500-F23/whimsical-wolves/tree/c4a03784723fb0c099a7a22c66c421a1f0613e7f) \
Self-eval: https://github.khoury.northeastern.edu/CS4500-F23/whimsical-wolves/blob/6416808b0a62afc563722666059051e104505f75/10/self-10.md \
Score: 72/110 \
Grader: Vish Jeyaraman


#### [72/110pts] Program Inspection
1. [20/20pts] Helpful and accurate self-eval. 
2. [36/70pts] A well-designed data representation for configurations.
   - [0/10pts] Purpose statement for data representation.
   - [10/10pts] Language internal constructor.
   - [0/10pts] A separate "builder" that creates the data representation from JSON.
   - [10/10pts] A way to enforce "key correcteness".
   - [10/10pts] Method(s) that retrieves the value of entries.
   - [0/10pts] Method(s) that modifies the value of entries.
   - [6/10pts] unit tests.
     - Missing. Partial credit for honesty. 
3. [10/10pts] Server does not touch the referee configuration inside of a server configuration other than passing it on to the referee.
4. [6/10pts] Referee does not touch the scoring configuration inside of a referee configuration other than passing it on to the scoring functionality.
   - Referee touches scoring configuration, partial credit for honesty
