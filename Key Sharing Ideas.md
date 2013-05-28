How to share a private key amongst trustees
===========================================
* Initial ideas about 3 trustees holding different 2/3 key is a no go. It reduces the effort needed by 1 trustee to brute force the other part of the key. Also very hard to come up with schemes for 3/4 3/5 4/6 etc.

* Use http://en.wikipedia.org/wiki/Shamir%27s_Secret_Sharing

* I can design a process which could generate a number of pieces of a shared secret such that >50% of the pieces can unlock the private key.

* I could even design a process for spending the coins (it would have to temporaily store each secret piece until the last trustee confirmed, it would also be difficult to cryptographically erase database/memory so it has weaknesses, but may be secure enough for our needs).

* I could design a process that retires wallets by listening to the block chain and automatically transfering all incoming transactions to the new wallet.

weaknesses
==========
* Trustees still need to trust administrator to design process correctly and not be corrupt. Other Not for Profit organisations have the founder hold the private key, so this is a better solution.
* http://www.coindesk.com/liberty-focused-non-profits-find-a-friend-in-bitcoin/
* This is also a problem the BABG is set up to address and find better solutions for.

* Server hosting process could get hacked.
