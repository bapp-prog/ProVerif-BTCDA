# ProVerif-BTCDA
Welcome to the ProVerif codes repository for the automated software verification of the proposed protocol described in the paper titled "A Blockchain-Assisted Privacy-Preserving Cross-Domain Authentication for Internet of Things." This repository contains ProVerif codes specifically designed to rigorously analyze the security properties of the protocol outlined in the aforementioned paper.

### Step 1: Install ProVerif
opam install proverif OR download from: https://prosecco.gforge.inria.fr/personal/bblanche/proverif/

### Step 2: Run verification
proverif cross_domain_auth_proverif.pv

### Step 3: Generate results
proverif -html output cross_domain_auth_proverif.pv, and view results in output.html
