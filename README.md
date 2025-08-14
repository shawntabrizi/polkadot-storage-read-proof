# Polkadot Storage Read Proof

This repo shows a minimal working example of verifying a Storage Read Proof, which are the bytes returned from the `state_getReadProof`.

This uses the `sp_state_machine::read_proof_check` to easily verify the proof.

In this example, we get a proof for the state of an account on Polkadot, including their balance.

You can find more details in the `./src/main.rs`.
