#### DISCLAIMER: This is experimental code, aka joke or trolling code.  It is not meant to be used for production or taken seriously at all.

### [@devtooligan](https://twitter.com/devtooligan) supports creative experimentation on the blockchain as a path towards innovation.

# E-VENT-RC20.SOL

A hyper-cursed ERC20 implementation where all of the logic lives inside the arguments of function calls to `emit()`.

Authored by [@danielvf](https://github.com/DanielVF), a Baphomet witch and master of curses.  His original incantation [here](https://gist.github.com/DanielVF/ab8e083539da1e162a442dbe9cef5b16).

 
### tldr;
This pattern was used in [ArtGobblers](https://github.com/artgobblers/art-gobblers) for "[brevity](https://twitter.com/transmissions11/status/1622798627629572096?s=20&t=9qpMggKbBrpf8kXyjQcGQQ)". Note: This is not intended as a gas optimization!

[Horsefacts](https://twitter.com/eth_call) and I started joking about it and taking it to the extreme.  Months later it resurfaced with a [tweet](https://twitter.com/z0r0zzz/status/1622170338112188416) from [Ross](https://twitter.com/z0r0zzz) and I decided to put a [0.1 eth bounty](https://twitter.com/devtooligan/status/1622768367596888064) out for an ERC20 implmentation with all logic in `emit()` that passes Solmate tests.


In case you're confused (and you should be), heres some Twitter threads:

 - https://twitter.com/eth_call/status/1573734826422816768
 - https://twitter.com/devtooligan/status/1573818445447106560
 - https://twitter.com/clemlak/status/1622971215034957824
 - https://twitter.com/danielvf/status/1622943096773218304
 - https://twitter.com/devtooligan/status/1622768367596888064
 - https://twitter.com/z0r0zzz/status/1622170338112188416
