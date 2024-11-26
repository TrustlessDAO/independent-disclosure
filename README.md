# IndependentDisclosure: Peer-to-Peer Vulnerability Disclosure

## Overview
Welcome to the IndependentDisclosure repository. This repository is part of a decentralized, peer-to-peer vulnerability disclosure process that aims to facilitate responsible and efficient communication between security researchers and protocols.

## Disclosure Process
As a protocol representative, you have been invited to this private repository because a security researcher has identified a potential vulnerability in your protocol. The researcher has chosen to use the IndependentDisclosure process to disclose the vulnerability details to you securely and transparently.

Here's what you can expect from the disclosure process:

1. **Invitation**: The researcher has invited you as a collaborator to this private repository, granting you access to the vulnerability details.

2. **Vulnerability Report**: The researcher has provided a detailed vulnerability assessment in the [report.md](./report.md) which outlines the nature of the vulnerability, its potential impact, and any supporting evidence.

3. **IndependentDisclosure Contract**: The researcher has deployed an [IndependentDisclosure](https://gist.github.com/0xKorok/cb1925bd68cf919b6d18181d46dd3cce) smart contract, which serves as an immutable record of the disclosure process. The contract includes a reference to the initial commit hash of this repository, establishing a tamper-proof link between the contract and the vulnerability report.

4. **Collaborative Discussion**: You can use the GitHub issue tracking and discussion features within this repository to engage in a collaborative discussion with the researcher. This allows for secure communication, clarification of the vulnerability details, and coordination of remediation efforts. These details may be revealed in the event of a dispute to help reach a resolution/settlement based on verifiable details and transparent communication/intentions during the negotiation process.

5. **Categorization Timeline**: The researcher has included the suggested deadline for categorizing the vulnerability in [initial-terms.md](./initial-terms.md). This is the waiting period, to be observed by the researcher, to allow you to apply either the "confirmed", "non-issue", or "won't fix" designations.
    * This most often takes 24-72h. In special circumstances a longer period may be required. It is the responsibility of the protocol to provide reasonable evidence to justify an extended period (beyond the researchers initial suggestions).

6. The protocol can make it's final severity decision known by editing [protocol-severity.md](./protocol-severity.md) to add the designation they believe is correct. This decision should be considered binding. 

7. **Final Categorization**: The protocol has full control over which of the 3 designations ("confirmed", "non-issue", or "won't fix") they choose to apply to the issue. Before selecting a final categorization the protocol should carefully consider the implications of each:
    * `Confirmed`: Begins the extended timeline for settlement / mitigation. Protocol should complete [authorization.md](./authorization.md) then DM the commit hash for the authorization to the researcher. Please send the hash from your official Telegram or Twitter. This way no dispute can arise as to the authenticity of the commitment. 

    * `Non-Issue`: Ends the disclosure process. Gives researcher permission to go public with the full-report immediately.

    * `Won't Fix`: This is a kind of confirmation. Protocol should decide if it would prefer to keep the issue private if so they should negotiate with the researcher on a fair price to keep their their work confidential. If no timely settlement is reached they can go public with the report.


## Protocol Expectations
To ensure a smooth and effective disclosure process, we kindly request the following from you as a protocol representative:

1. **Timely Response**: Please acknowledge receipt of the vulnerability report and provide an initial response within a reasonable timeframe (e.g., 48-72 hours).

2. **Good Faith Collaboration**: Engage in good faith discussions with the researcher, providing transparency and cooperation throughout the process.

3. **Responsible Disclosure**: Adhere to the agreed-upon timeline for addressing the vulnerability and coordinate with the researcher for responsible disclosure.

4. **Attribution and Recognition**: If applicable, consider providing appropriate attribution and recognition to the researcher for their responsible disclosure efforts.

## Researcher Expectations
The researcher is expected to:

1. **Detailed Reporting**: Provide a comprehensive vulnerability report, including necessary technical details and supporting evidence.

2. **Collaborative Engagement**: Engage in constructive discussions with the protocol representatives to facilitate a smooth resolution process.

3. **Responsible Disclosure**: Adhere to the agreed-upon timeline for disclosure and allow sufficient time for the protocol to address the vulnerability.

4. **Confidentiality**: Maintain the confidentiality of the vulnerability details until the agreed-upon disclosure timeline has been reached or the vulnerability has been resolved or deemed a non-issue.

## Contact Information
If you have any questions or concerns regarding the IndependentDisclosure process or the contents of this repository, please contact the researcher directly using the communication channels they have provided.

If you have questions, comments, or concerns the researcher is unable to address you can reach out to a [TrustlessDAO representative](https://x.com/0xKorok) our DMs are open and we will do our best to respond within 24 hours.

We appreciate your cooperation and commitment to enhancing the security of your protocol and the broader ecosystem.