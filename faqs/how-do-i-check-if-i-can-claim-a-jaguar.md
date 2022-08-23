# How do I check if I can claim a Jaguar?

### There are 2 ways to check if an [Ape](../nft-collections/ape-gang.md) has a [Jaguar](../nft-collections/jaguar-gang.md) claim

Sometimes Opensea's metadata is not updated, so we recommend always checking claims on both Opensea and Etherscan to double check Jaguar claims.

### 1. Opensea

All Apes have a 'Jaguar Claim' stat on Opensea, check your Ape to see if it has a claim.

You can filter a search on Opensea to show Apes with between 0 claims (none) up to 8 claims (maximum) if you would like to purchase an Ape with remaining claims.

### 2. Etherscan

You can check if an Ape has already claimed it's Jaguars directly on the contract via etherscan.&#x20;

This method cannot tell you the number of Jaguar claims an Ape has, only if the Ape does or does not have Jaguar claims remaining.

How?

1. Go to the contract: [https://etherscan.io/address/0xfbb4d05f34967cfa406dcffbbf0b51e5f842d6a3#readContract](https://etherscan.io/address/0xfbb4d05f34967cfa406dcffbbf0b51e5f842d6a3#readContract)
2. Click on "isClaimed".
3.  Enter the tokenID for the Ape you would like to check for Jaguar claims.

    _Find the tokenID by visiting the Ape's individual etherscan page._
4. Click "Query". You will receive either "false" or "true.

True means:

* Ape has already claimed it's Jaguars and cannot claim any more.

False means

* Ape has not claimed it's Jaguars yet, OR
* Ape has no Jaguar claims because they didn't win any in [Gang Wars](../play-to-earn-games/gang-wars.md).

On it's own the Etherscan method is not very useful, but when combined with using Opensea it will save you from making mistakes.
