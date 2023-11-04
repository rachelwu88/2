# Create a Smart Contract
This is a two part assignment, with grading broken down as follows:
 * [Part One](#part-one-proposal) - 2 points **Due In Class**: __Wednesday, November 15, 2023__
 * [Part Two](#part-two-contract-creation) - 8 points **Due on Github**: __Wednesday, December 6, 2023, 11:59PM Eastern Standard Time.__

Smart contracts are immutable computer programs that run deterministically in the context of an Ethereum Virtual Machine as part of the Ethereum network protocol.  Your assignment is to propose a contract and then to create that contract, in Solidity, on the Ropsten Network.  You can refer to [Solidity by Example](https://solidity.readthedocs.io/en/v0.5.13/solidity-by-example.html) for inspiration.  You may work in groups, with no more than six people and you must declare your grouping in Part One. You can organize into groups using Discord: discord.com/invite/vBCTZ54a

## Part One: Proposal

**Due In Class**: __Wednesday, November 15, 2023__

Your proposal must include the following:
 * [ ] Group Members (if any) in `README.md`
 * [ ] Purpose of Contract in `README.md`
 * [ ] Interface of Contract with function and event headers
 * [ ] Proper Styling of Interface. [Reference](https://solidity.readthedocs.io/en/v0.5.13/style-guide.html)
 * [ ] Submission as listed below

### Submission - Part One
* Update repository
```bash
git checkout master
git pull
```
* Create a branch on this github repo [firstname_lastname.assignment04.part_one] 
```bash
git checkout -b wendy_mock.assignment04.part_one
```
* Create directory assignment "FirstName_LastName_Assignment04" 
```bash
cd Assignment04
mkdir Wendy_Mock_Assignment04
```
* Add and Commit proposal files: `README.md`, `Contract-Interface.sol`
```bash
cd Wendy_Mock_Assignment04
git add README.md
git add Contract-Interface.sol
git commit -m "submitting assignment04 part one"
```
* push assignment branch to this repository
```
git push origin wendy_mock.assignment04.part_one
```
* Create a pull request with your submission, replacing `wendy_mock.assignment04.part_one` with your branch name:
```
https://github.com/wendymock/csci49379-fall2023/pull/new/wendy_mock.assignment04.part_one
```

## Part Two: Contract Creation

**Due on Github**: __Wednesday, December 6, 2023, 11:59PM Eastern Standard Time.__

Your contract must include the following:
 * [ ] Commits of multiple members (as applicable)
 * [ ] Interface from Proposal
 * [ ] Tests that demonstrate functionality of contract. [Reference](https://michalzalecki.com/ethereum-test-driven-introduction-to-solidity/)
 * [ ] Proper Styling of Contract. [Reference](https://solidity.readthedocs.io/en/v0.5.13/style-guide.html)
 * [ ] Submission as listed below


### Submission - Part Two
* Update repository
```bash
git checkout master
git pull
```
* Create a branch on this github repo [firstname_lastname.assignment04.part_two] 
```bash
git checkout -b wendy_mock.assignment04.part_two
```
* Add and Commit contract and test files: `Contract.sol`, `Contract-Test.sol` to same directory used for Part One
```bash
cd Assignment04/Wendy_Mock_Assignment04
git add Contract.sol
git add Contract-Test.sol
git commit -m "submitting assignment04 part two"
```
* push assignment branch to this repository
```
git push origin wendy_mock.assignment04.part_two
```
* Create a pull request with your submission, replacing `wendy_mock.assignment04.part_two` with your branch name:
```
https://github.com/wendymock/csci49379-fall2023/pull/new/wendy_mock.assignment04.part_two
```