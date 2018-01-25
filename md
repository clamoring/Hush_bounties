## Hush Bounties 

Title: Electrum lite wallet front end  
Type: Front end  
Reward: 100 HUSH  
Details: Hush has been added to ElectrumX 1.2.1 and we have the back end complete. We need someone to write the front end. [Github](https://github.com/MyHush/hush/issues/80)

Title: Re-define Hush Release Process  
Type: Process  
Reward: TBD   
Details: We need to redefine the hush release process and update related documentation accordingly. This re-write is needed due to team changes and to fully sync devs. [Github](https://github.com/MyHush/hush/issues/77)

Title: Web wallet Getting Started page  
Type: Front end  
Reward: TBD  
Details: We need a page that explains to users how to use the web wallet and what happens during transactions. [Github](https://github.com/MyHush/myhushwallet/issues/9)


Title: Generating custom OP_RETURN data  - Open PR from Duke for 1.0.13  
Type: Back end  
Reward: TBD  
Details: The `createrawtransaction` RPC method in Hush does not support a `data` key to embed data into a raw transaction via OP_RETURN. A hush developer should be able to create custom raw transactions with data keys, so as to enable embedding data via OP_RETURN. [Github](https://github.com/MyHush/hush/issues/67)

Title: Fix 1.0.13 issues/to-do items  
Type: misc  
Reward: TBD  
Details: There are a number of open items that need to be fixed or improved. [Github](https://github.com/MyHush/hush/issues/46)

Title: Adjust auto-senescence parameters - done with 1.0.12 MyHush/hush@d95b3e8  
Type: Back end  
Reward: TBD  
Details: Nodes have an auto-senescence feature that causes versions more than roughly 18 weeks old to not run without a flag to override this. We need to adjust parameters to match HUSH block heights, and possibly make for a longer deprecation period or consider not enabling by default. [Github](https://github.com/MyHush/hush/issues/33)

Title: Clarify doc/authors.md file  
Type: Documentation  
Reward: TBD  
Details: This file lists Zcash contributors and commit counts. Old contributors are listed when they don't need to be, and new contributors are not listed when they should be. File needs updating or another solution found. [Github](https://github.com/MyHush/hush/issues/33)

Title: miner.myhush.org upgrades  
Type: Back end  
Reward: TBD  
Details: miner.myhush.org does not support SSL. To fully support SSL, we must support Secure WebSockets (WSS), which requires opening up new server ports, and new nginx configs and updating HTML/JS with relevant URL and code changes. Additionally, the Perl code that is the dynamic part of the codebase needs to be made into a CPAN module, to be testable and trivially distributable via-known-trusted channels like package managers. We also need to be able to payout to N addresses with arbitrary ratios, to enable many use cases. [Github](https://github.com/MyHush/hush/issues/18)
