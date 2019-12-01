advent
=====

Starting a REPL and running the solution for day 1, part one:

    $ rebar3 clojerl repl
    ===> Verifying dependencies...
    ===> Compiling advent
    ===> Clojerl Compiling clojerl
    ===> Clojerl Compiling advent
    %%% Compiling advent/day_1.clje...
    Clojure 0.5.1
    clje.user=> (advent.day-1/part-one)
    3389778
    clje.user=>

For any other day replace 1 with `n` and for running part two
just call `(advent.day-n/part-two)`.

Input files are stored under the `priv` folder.
