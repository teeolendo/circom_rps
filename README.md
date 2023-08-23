# Circom Example - Rock Paper Scissors
This repository contains a simple circuit demonstrating how to start using Circom. The example repo covers a simple Rock Paper Scissors example that shows you how to use write your own ZKPs using Circom.

## Getting Started
To get started, review the RPS.circom file which contains all the logic required for this circuit to compile and be used successfully. It also contains a Node project that we use to
import the [CircomLib](https://github.com/iden3/circomlib), a repository of hundreds of circuits you can use to build your own ZK circuits.

## Installing Circom
- If you do not have Circom installed on your system, you can run `curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh` to install Rustup
- In your preferred directory, clone the circom repository `git clone https://github.com/iden3/circom.git`
- Enter the circom directory and use the cargo build to compile: `cargo build --release`
The installation takes around 3 minutes to be completed. When the command successfully finishes, it generates the circom binary in the directory target/release. You can install this binary as follows:
- And finally, run `cargo install --path circom` to complete your install. You should now have Circom installed and be able to run `circom --help` to confirm your installation.

## Installing Snark JS
ZKPs can be broken down into two important pieces, Constraint Generation and Proof Generation. Snark JS is an important library for Proof Generation, which can generate proofs using Groth16, Plonk or FFLonk.
You can learn more about Snark JS [here](https://github.com/iden3/snarkjs)

- Run `npm install -g snarkjs` to use Snark JS globally on your device

## Compiling this circuit
In order to compile this circuit, go through a [Powers of Tau] ceremony and eventually generate a Solidity file; refer to the commands.txt file for all the instructions to get you started.


## Resources
[Circom Documentation](https://docs.circom.io/getting-started/installation/)
[Understanding ZKPs 1](https://dev.to/tonyolendo/the-complete-full-stack-guide-to-getting-started-with-zero-knowledge-proofs-using-circom-and-zk-snarks-part-1-53gi)
[Understanding ZKPs 2](https://dev.to/tonyolendo/the-complete-full-stack-guide-to-getting-started-with-zero-knowledge-proofs-using-circom-and-zk-snarks-part-2-58o)
[Video of how to use this repo](https://youtu.be/AWA107F2uDQ)
