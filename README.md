# AI Evidence Milestone Dispute Resolver

An AI-powered Intelligent Contract built on **GenLayer** to resolve milestone disputes through evidence-based evaluation and consensus validation.

## Overview

The AI Evidence Milestone Dispute Resolver is designed to evaluate submitted evidence against predefined milestone requirements and determine an appropriate dispute resolution.

The contract uses GenLayer's nondeterministic execution and validator consensus to evaluate evidence and validate the resulting decision.

## Features

* **Milestone Requirements** — Define the conditions that must be satisfied.
* **Evidence Submission** — Allow the provider to submit evidence through a URL.
* **Dispute Management** — Allow the client to open a dispute after evidence submission.
* **AI Evidence Evaluation** — Evaluate evidence against the specified requirements.
* **Consensus Validation** — Validate the AI-generated decision through GenLayer's consensus mechanism.
* **Resolution Tracking** — Store the decision, reasoning, and final resolution on-chain.
* **Contract State Retrieval** — Retrieve the current state of the dispute.

## Workflow

1. Initialize the contract with a provider address and milestone requirement.
2. The provider submits evidence through a URL.
3. The client opens a dispute if necessary.
4. The contract retrieves and evaluates the submitted evidence.
5. GenLayer validators validate the evaluation result through consensus.
6. The contract records the final decision and resolution.

## Possible Outcomes

| Decision | Resolution          |
| -------- | ------------------- |
| APPROVE  | RELEASE_TO_PROVIDER |
| REJECT   | REFUND_TO_CLIENT    |

The contract records the evaluation result and reasoning. The current implementation does not directly transfer funds; it records the resolution outcome.

## Technology Stack

* Python
* GenLayer Intelligent Contracts
* GenLayer Studio
* AI-powered evidence evaluation
* Nondeterministic execution and consensus validation

## Project Status

**Deployed and tested in GenLayer Studio.**

The contract was executed successfully, and the returned state showed the evidence submitted, dispute resolved, and the final decision recorded.

## Learning Goals

This project explores how AI-powered evaluation and consensus validation can be applied to milestone-based dispute resolution using GenLayer Intelligent Contracts.

---

Built as part of my GenLayer Intelligent Contract development journey.
