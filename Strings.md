# POGO Oragnizing Strings

Listed below are strings I use to organize my Pokémon storage after a day of catching. The following strings allow me to automate the process of labeling pokemon to trade / check ivs / transfer to professor Willow. 

## Step 0 - Creat tags

I use the following tags for organizing
- #trade : Self-explanatory
- #check : I tag mon to check for pvp ivs later. Used when I don't have time to individually check atm but know that the mon have decent pvp ivs
- #.LC : little cup
- #.GL : great league
- #.UL : ultra league
- #.ML : master league


## Step 1 - Pvp Ivs

```licki,pachiri,spritz,vulla,chanse,shadow,+scrafty,+dubwool,+cofagr,+joltik,+forretr,+primeap,+runeri,skarmo,+nineta,+pidgeo,+ferrotho,+cradily,weezing,+jell,+lantu,+pelipp,+seakin,+dewg,+fros,0-1attack&2-defense&2-hp&!#.&!#trade&age0-7&!favorite&!#.check```

This is the string I use to filter out mon to check for pvp IVs. I select all in it and temporarily tag them with `check`.

**Explanation**
- `0-1attack&2-defense&2-hp` filters out anything with 0-5 bar attack, 6-15 bar defense, and 6-15 bar hp
- `licki,pachiri,spritz,vulla,chanse,shadow,+scrafty,+dubwool,+cofagr,+joltik,+forretr,+primeap,+runeri,skarmo,+nineta,+pidgeo,+ferrotho,+cradily,weezing,+jell,+lantu,+pelipp,+seakin,+dewg,+fros` are top ranked Pokémon in each league that have rank 1 ivs not covered by the generic low attack and high defense + hp IVs above. Most of them require hundo for UL or IVs like 7/15/15 for Alolan Ninetales in UL. Note, this will not filter out *all* pokemon listed above, but rather only those with potential to be good pvp IVs (high defense and high hp).
- `!#.` filters out pokemon I haven't already tagged as `#.LC`, `#.GL`, `#.UL`, and `#.ML`
- `!#trade` filters out pokemon I haven't tagged to trade
- `age0-7` filters out the pokemon that apply in the last week so I don't get pokemon of all time
- `!favorite` filters out pokemon that are not starred
- `!#.check` filters out pokemon not tagged as check

## Step 2 - Pokémon for trade


