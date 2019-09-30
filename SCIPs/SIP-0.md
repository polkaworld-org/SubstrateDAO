# SIP

| SIP | Title                     | Status | Type | Created    | Updated |
| ----| ------------------------- | -------| -----| ---------- | -------- |
| 0   | SIP Purpose and Guidlines | WIP | Meta | 2019-09-30 | Text     |

## 1. What is SIP
SIP stands for Substrate Improvement Proposal. An SIP document describes new features of Substrate, or improvements of its processes to the Substrate community. The SIP should document conscise technical specification of the proposal and rationale behind it. The SIP author is responsible for building consenus within the community and documenting discussions and disagreements. Each SIP has a unique index number.

## 2. SIP Rationale
SIP is the primary mechanism for proposing new features and improvements, for collecting community input on an issue or idea, and for documenting specification and design decisions that go into Substrate. Each SIP is maintained as a text file in a versioned repository, hence its revision history is also the revision history of the proposal.

## 3. SIP Types
There are two types of SIP:
1. **Request for Change (RFC)** SIP: a request SIP describes functional chnages, improvements or new features on Substrate. For example SRC20 (ERC20-like) fungible asset token standard.
2. **Meta** SIP: describes a process surrounding Substrate or proposes a change to a process. For example the SIP itself.

## 4. SIP Workflow
```
[ 1. WIP ] -> [ 2. Draft ] -> [ 3. Accepted ] -> [ 6. Implemented ] 
                |                                         |
                --> [ 4. Rejected ]                      --> [ 7. Superseded ]
                |
                --> [ 5. Dropped ]
```

1. **WIP as Work in Progress**: once a SIP champion has asked Substrate community for whether an idea has any chance of support, he/she will submit a SIP as a pull request.
2. **Draft**: once the SIP is agreeable, an SIP editor will merge the PR. Subsequent PRs can be submitted to this SIP. SIPs ready for review should include implementation details and change status to **Draft**. 
3. **Accepted**: If an SIP is accepted, then status will change to "Accept". But if there are material changes or substantial unaddressed technical complaints, it'd revert to **WIP** with correction notes.
4. **Rejected**: an SIP would be rejected due to major, uncorrectable flaws.
5. **Dropped**: This SIP is no longer pursued by the original authors or it may not be a (technically) preferred option anymore.
6. **Implemented**: All proposed changes are implemented and merged.
7. **Superseded**: An SIP which was previously implemented but is no longer considered state-of-the-art. Another SIP will be in Implemented status and reference the Superseded SIP. An SIP cannot move on from this state.

## 5. Review Process
1. **Pull Request Review**: each participating SubstrateDAO member shall nominate 1 to 2 (TBD) reviewer for PRs. 
2. **SIP Review**: SIPs that are in **Draft** status shall be announced and communicated to community members. Periodic calls shall be organized to review these SIPs to decide next step. 

## 6. SIP Document Requirements

### 6.1 Required Content

TBD
1. Header: 

    * SIP: SIP number
    * Title: SIP title
    * Author: names of author(s)
    * Status: WIP/Draft/Accepted/Rejected/Dropped/Implemented/Superseded
    * Type: RFC/Meta
    * Created: date format in YYYY-MM-DD
    * Updated: comma separated list of dates in YYYY-MM-DD
    * Replaces: SIP number(s)
    * Superseded by: SIP Number(s)

3. Abstract
4. Motivation
5. Specification
6. Rationale
7. Backwards Compatibility
8. Test Cases
9. Implementation
10. Copyright Waiver

### 6.2 Format and Directory Structure
SIPs should be written in markdown format. SIP documents should reside in `[home]/SIPs/SIPS`. All assets should reside in `[home]/SIPs/assets` folder as `/SIP-Number` where `Number` is the SIP number.

## 7. References
Ethereum Improvement Proposal: https://github.com/ethereum/EIPs
Bitcoin Improvement Proposal: https://github.com/bitcoin/bips
Binance Chain Evolution: Proposal: https://github.com/binance-chain/BEPs

## 8. License
TBD

## Discussions
1. Decide SIP naming: SCIP (Substrate Community Improvement Proposal), SDIP (Substrate DAO Improvement Proposal), or SIP (Substrate Improvement Proposal)...
2. Decide SIP location: a separate SubstrateDAO github organisation, and folder structure
3. Decide on review process - norminated PR reviewers and process
4. Decide review process - SIP review process, call periods etc
