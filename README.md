# Betting reference example

This is a sample projects that demonstrates the use of Atlas with CLB and
Cardano private network.

Enter Nix shell

$ nix develop

And then:

* to run Aiken-based suite:

$ export AIKEN_BET_REF=1; cabal run atlas-bet-ref

* to run Plutus Tx suite:

$ cabal run atlas-bet-ref
