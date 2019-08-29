This is the ReadME File for the E-Voting System Using Blockchain
----------------------------------------------------------------
Contract Address:-
0xf15a7dFA45C126f9825455cA1A890aED5631BFf9
----------------------------------------------------------------
File Structure:-
E-Voting.sol => This file contains the solidity code for the smart contract

ABI.txt => This File contains the ABI for the smart contract execation

UTC--2019-06-21T08-25-27.608Z--80da195ff0442ed15abee87d08694270176d34f3 => This is Keystore File and Owner of the deployed contract the address is mention above

UTC--2019-08-10T09-38-09.930Z--d07c8e760fbe5dffe0bac2afe787f360e7413f13 => This is another Keystore File use to test the contract
-----------------------------------------------------------------
Password for the Keystore File

UTC--2019-06-21T08-25-27.608Z--80da195ff0442ed15abee87d08694270176d34f3 => Abc@@##123

UTC--2019-08-10T09-38-09.930Z--d07c8e760fbe5dffe0bac2afe787f360e7413f13 =>hello123456
-----------------------------------------------------------------
About Deployed Contract:-
The Token in this contract is "ERC20 Token" and named as "NEW TOKEN FOR VOTING (TKFVoteNew)". The TotalSupply for it is 10(TKFVoteNew). And currently all the supply is with the owner.There is one candidate named "OSP" and the current votes are "2". There are no any candidate in it. There are two functions which can only execuate by the owner, that are:- addcandidate(which is used to add candidates in the list), transfer(which is used to transfer the token to vote and enables the VoteE value which is used for 2 way authentication). To execuate the voteForCandidate function there are certain parameters to be noted:-
1)There should by Token(TKFVoteNew) to execuate your vote.
2)The account should have the VoteE value true.
The Token and the the VoteE value can only send and change the value by the owner respectively. 