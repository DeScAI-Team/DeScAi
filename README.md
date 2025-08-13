DeScAi - Autonomous On-Chain AI for Scientific Research Review.

DeScAi is the first blockchain-AI based project to run entirely on chain, and the only project training a large and inter-disciplinary Sci-LLM exclusively on full, peer reviewed, texts. 
Located within the Stony Brook University Blockchain Business lab, our team is building a transparent, unbiased, and accessible AI review mechanism for scientific research in the DeSci space.
Our system allows readers, investors, and researchers alike to generate and access high quality and reliable research reviews near-instantly.  

The DeSci movement is dismantling traditional institutional barriers in scientific research, opening opportunities for global participation. But without robust quality control, openness risks promoting misinformation, low-quality publications, and predatory behavior. 

As the walled gardens of Academia and Publishing Journals crumble, DeScAi empowers the public with tools to:
  - Cut through jargon and hype
  - Access objective and verifiable "Proof of Review" statements
  - Identify truly valuable research worth reading or funding

DeScAi operates fully on-chain, leveraging:
  - EVM based smart contracts for governance and execution
  - Chainlink Oracle Network for inter-chain connectivity
  - Akash Network for decentralized compute
  - Arweave for permanent, immutable storage
<img width="851" height="1032" alt="High-Res-Fixed drawio" src="https://github.com/user-attachments/assets/e85b7c88-8ec8-4720-9a39-943dc05c3185" />

This digram outlines the flow generally as follows:  Author uploads their paper through the dapp and pays a small fee estimated between $1-$2, this fee covers all oracle, data storage, and and NFT minting costs.  Their paper is then uploaded to a DA layer like Arweave where it is available to the oracle via HTTP request. The oracle fetches the paper, spins up the AI api server with one call, and submits the paper for review with another. These outputs are then passed, with an oracle attestation and original paper link, to a smart contract responsible for minting the NFTS and providing them to the author while also pushing outputs to the DA layer. A registry off all paper reviews is provided in the dapp and interfaces with the DA layer. DeSci protocols can also interface with these DA listings as they are publicly accessible and immutable. 


Roadmap

Phase 1 - Foundation (2025 Q3-Q4):
  - Collect and organize dataset
  - Train model
  - Build a simple WebApp prototype with the model running centrally. 

Phase 2 - Decentralization (2026 Q1-Q2):
  - Port model to decentralized compute network
  - Implement oracle-compute network interconnectivity 
  - Integrate review oracle-compute review pipeline with WebApp

Phase 3 - Launch (2026 Q3):
  - Stress test and finalize functionality
  - Initialize liquidity pools to smooth cross chain payment
  - Launch Dapp through Webapp-EVM integration


Our primary goal is to launch the DeScAi platform by Q3 2026 & Integrate reviews with existing DeSci protocols. 


Success will be measured as achieving:
  - Review costs under $2 
  - Review Generation in under 3 minutes
  - High throughput without loss of accuracy or functionality 
