Forked From https://github.com/Karbovanets/Karbowanec-Blockchain-Explorer

# Turtle Block - A Turtle Coin Blockchain Explorer
# This repository requires a modifed version of Turtle Coin
    The RpcServer does not output the difficulty by default on `f_blocks_list_json`
    and requires a change to the tempalte file to output it.

Most of my changes can be viewed by searching for NOTE

## Most Interesting Notes Include
 - Removed white version of the site, because i didnt have a pure green logo +
   nobodys eyes desrve that (could easily be re-enabled)
 - Updated a foreach loop on getPoolTransactions() on homepage because it didnt
   work
