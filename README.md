# shamir-sharing-research
Findings on the implementations of Shamir secret sharing scheme and their compatibility

ssss CLI

s4 web app
  - sources Hashicorp's vault
  
SLIP39 implementations

banana-share

python cryptodome library

https://github.com/dsprenkels/sss-cli and the underlying C-code



## Questions:

Is the ordering necessary? What options for reconstruction of the original/master secret would remain?

When there is a share/shard, can we create another pieces for another secret? Should be possible, from my shallow intuition.

## Ideas:

Would be nice to have a challenge-response for sending the shares encrypted to the node/device which will put it together, perform an action a forget the parts. Sort of poor man's multi-signature.
