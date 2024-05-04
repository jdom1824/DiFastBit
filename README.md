# DiFastBit

Distributed Transaction Differentiation Scheme for Fast Payments

## Project Description

Bitcoin is a payment system that generates a decentralized currency without the need for time-constraints transactions. Therefore, it is vulnerable to double-spending attacks. In the literature, Karame et al. have formalized the necessary requirements to successfully prevent these attacks, focusing on fast payment scenarios where the buyer does not wait for Bitcoin confirmation. Several solutions have been proposed to mitigate these attacks, such as flooding, where each transaction is propagated without restriction to detect double spending; listeners/observers, which prevent isolation to detect the attack; and finally, penalties by revealing private keys. However, there is no solution that fully avoids double spending attacks in fast payment scenarios in Bitcoin. We propose DiFastBit, a distributed layer of Bitcoin nodes that differentiates between normal transactions and fast payment transactions, giving them special treatment. To develop this project, it is necessary to establish theoretical foundations that help demonstrate its viability, along with a proof of concept. Our contributions to Bitcoin include a scientific paper explaining the workings of the DiFastBit layer, a theoretical demonstration that DiFastBit avoid double-spending attacks in fast payments, and a proof of concept that allows us to visualize a first functional version of this new layer.

## Potential Impact

1. **Improving Bitcoin's Security**: By addressing Bitcoin's vulnerability to double-spending attacks in fast payment scenarios, this project aims to strengthen transaction security. Since double-spending attacks can undermine trust in the currency, finding solutions to avoid these risks is critical for Bitcoin adoption.

2. **Innovation Transaction Management**: DiFastBit introduces a distributed layer of nodes that differentiates between transactions and fast payment transactions. This differentiation allows for specialized treatment better done to the needs of fast payments, thus improving the efficiency and responsiveness of the system in these scenarios.

3. **Academic and Technical Contribution**: Publishing a scientific paper and creating both a theoretical demonstration and a proof of concept will significantly contribute to the existing body of knowledge, providing valuable insights to the cryptocurrency and blockchain technology community.

4. **Potential for Broad Adoption**: If successful, DiFastBit could establish a new standard for managing fast payments in cryptocurrencies, potentially being adopted by other systems and similar technologies, thus extending its impact beyond Bitcoin.

5. **Development of Theoretical and Practical Infrastructure**: The project proposes a practical solution and commits to building  a solid theoretical foundation that proves its viability. This includes a theoretical demonstration and a proof of concept, both of which are essential for validating new technologies.


## Project Timelines and Potential Milestones

| DiFastBit Schedule |
|---|

| Task | Month 1 | Month 2 | Month 3 | Month 4 | Month 5 | Month 6 | Month 7 | Month 8 | Month 9 | Month 10 | Month 11 | Month 12 |
| --- |:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Review related works | X | X | X | X | X | X |  |  |  |  |  |  |
| Identify cases of double spending in fast transactions | X | X | X | X |  |  |  |  |  |  |  |  |
| Analyze transaction propagation in bitcoin network  |  |  | X | X | X | X |  |  |  |  |  |  |
| Model double spending scenarios for fast bitcoin payments |  |  |  | X | X | X | X | X | X |  |  |  |
| Model the DiFastBit layer to avoid double spending |  |  |  |  |  |  |  |  | X | X | X |  |
| Correctness proof of DiFastBit layer |  |  |  |  |  |  | X | X | X |  |  |  |
| Develop and validate proof of concept for DiFastBit |  |  |  |  |  |  | X | X | X | X |  |  |
| Conduct comparative analysis with existing literature |  |  |  |  |  |  | X | X |  |  |  |  |
| Write paper |  |  |  | X | X | X | X | X | X | X | X | X |

## Project Budget
| Category | Description                                           | Salary    | Time (Months) | Total       |
|----------|-------------------------------------------------------|-----------|---------------|-------------|
| PERSONAL |                                                       |           |               |             |
|          | Senior Researcher                                     | $4,634.75 | 12            | $55,617.00  |
|          | Junior Researcher                                     | $1,916.67 | 6             | $11,500.00  |
|          | Developer                                             | $5,158.33 | 4             | $20,633.33  |
|          | Project Manager                                       | $7,403.33 | 6             | $44,420.00  |
| SOFTWARE/SERVICES                                               |           |               |             |
|          | AWS Services                                          | $968.28   | 6             | $5,809.67   |
|          | ChatGPT                                               | $20.00    | 12            | $240.00     |
|          | Copilot                                               | $30.00    | 6             | $180.00     |
| PUBLICATIONS                                                    |           |               |             |
|          | Paper (Blockchain: Research and Applications)         | $1,600.00 |               | $1,600.00   |
| **Total**|                                                       |           |               | **$140,000.00** |
