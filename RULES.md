# Bracket F

_The F is for Fox - Fair and Balanced (but not really)_

## Goal

"Bracket F" is meant to be another ["Bracket"](https://edhrec.com/guides/edhrec-guide-to-commander-brackets) of Commander play, so all of the [normal Commander rules](https://magic.wizards.com/en/formats/commander) about play and color identity still apply.

We are broadly targeting a [Bracket 4 power level](https://edhrec.com/guides/edhrec-guide-to-commander-brackets#what-does-a-bracket-x-deck-look-like-bracket-4-optimized), but with modifications to the legal card pool and Game Changer rules.

The goal of _this_ variant is to allow for competitive, lethal, and "serious" games of Commander while avoiding some of the unfun play patterns of higher bracket Commander (as determined by the genius minds who created these rules, who are obviously correct and not biased).

## Card Pool Restrictions

<!-- Our "lever" for changing play patterns is the legal card pool. The brackets already have fairly complicated, semi-fluid, community-influenced rules about what is and isn't allowed in each bracket, so what's one more set of convoluted card selection restrictions?

This section will start with the lists of restrictions (or affordances) by type, a "smell test" sentence, and examples below each restriction for what is or isn't allowed by that restriction. It will be followed by an explanation for why those choices were made, since we figure the most important thing for 99% of people reading this is "what cards can I play" and not our philosophizing about what is or isn't fun.

One thing to note: you'll see a lot of "innately" in the restrictions. If you find a way to give all your creatures haste or flash to skirt around the restrictions, that's fair play. Our rules apply to the "default" mode of playing the card, not counting how it combos with other potential pieces you have. -->

### Tutors

> Tutoring for lands is fine, tutoring for your win-con is not

- #### Land tutors on lands are universally allowed, non-land land tutors must be worse than innately mana neutral on the turn you play it.

  * ✓ [Fetch lands](https://scryfall.com/card/mh3/220/flooded-strand) are fine
  * ✓ [Cultivate](https://scryfall.com/card/m21/177/cultivate) is fine because you go down in mana to use it (costs 3 to play, brings in two tapped lands)
  * ✓ [Archangel of the Ruins](https://scryfall.com/card/eoc/63/angel-of-the-ruins)'s Plainscycling is fine because it costs 2 to bring a Plains to hand, meaning even with a land for turn you're down 1
  * ✗ [Crop Rotation](https://scryfall.com/card/ulg/98/crop-rotation) is banned because you can tap a land to pay for its cost, sacrifice that land, and then get a fresh, untapped land in its place leaving you net neutral on mana for the play

- #### All tutors that innately immediately tutor are banned

  * ✗ [Demonic Tutor](https://scryfall.com/card/cmm/150/demonic-tutor) is banned because as soon as you cast it you can tutor to your hand.
  * ✗ [Entomb](https://scryfall.com/card/ody/132/entomb) is banned for the same reason, but with the graveyard.
  * ✗ [Tolaria West](https://scryfall.com/card/tsr/286/tolaria-west)'s Transmute too.
  * ✗ [Wishclaw Talisman](https://scryfall.com/card/fdn/617/wishclaw-talisman) is banned because as soon as you play it you can activate its ability to search for a card
  * ✓ [Land Tax](https://scryfall.com/card/soc/153/land-tax) is allowed because it meets the above land tutor restrictions and can't be used until your next upkeep
  * ✓ [Fauna Shaman](https://scryfall.com/card/m11/172/fauna-shaman) is allowed because its tutor ability requires a tap, meaning you need to wait until your next upkeep before using it
  * ✓ [Urza's Saga](https://scryfall.com/card/mh2/259/urzas-saga) is fine because you need to wait until the 3rd chapter of the Saga triggers to tutor

- #### Tutors with a cost to cast/activate of >=6 are allowed regardless of the above restrictions

  * ✓ [Burning-Rune Demon](https://scryfall.com/card/khm/81/burning-rune-demon) is fine. Go nuts.
  * ✓ [The World Tree](https://scryfall.com/card/khm/275/the-world-tree)'s WWUUBBRRGG ability is fine

- #### No tutors in the Command Zone even if they meet the above restrictions

  * ✗ [Zur the Enchanter](https://scryfall.com/card/csp/135/zur-the-enchanter) is banned as a Commander

### Mass Land Destruction / Denial

> Non-basic hate is always fine, unbounded MLD is not

- #### Non-basic hate is allowed

  * ✓ [Blood Moon](https://scryfall.com/card/8ed/178/blood-moon) turning all nonbasics into Mountains is fine
  * ✓ [Winter Moon](https://scryfall.com/card/mh3/213/winter-moon) preventing nonbasics from untapping is fine
  * ✓ [Ruination](https://scryfall.com/card/cmd/134/ruination) destroying all nonbasics is fine

- #### Generic MLD must have a specific, printed ceiling of lands it effects

  * ✗ [Armageddon](https://scryfall.com/card/5ed/7/armageddon) is banned because it says "destroy all"
  * ✗ [Winter Orb](https://scryfall.com/card/5ed/408/winter-orb) is banned because it prevents untapping of "all but 1"
  * ✗ [Death Cloud](https://scryfall.com/card/dst/40/death-cloud) is banned because X is unbounded and targets lands specifically
  * ✗ [Stasis](https://scryfall.com/card/me4/64/stasis) is banned because it prevents all untapping (which includes lands)
  * ✓ [Wildfire](https://scryfall.com/card/usg/228/wildfire) is fine because it specifically destroys **4** lands

- #### ALTERNATIVELY, generic MLD can have a specific, printed _floor_ of lands it will leave unaffected that is >=3

  * ✓ [Planetary Annihilation](https://scryfall.com/card/eoc/12/planetary-annihilation) is fine because specifies that each player chooses **6** lands and sacrifices the rest

- #### Generic MLD that meets the above restrictions must also be innately symmetric

- #### Cards that give players a choice about what permanents to mass destroy are fine, even if it might lead to MLD

  * ✓ [Torment of Hailfire](https://scryfall.com/card/hou/77/torment-of-hailfire) is allowed because, assuming something else catastrophic hasn't just happened, its either a win-con or a board wipe before its specifically MLD

### Combos

> Do whatever you want with 1 tiny restriction

- #### Combos that only involve your commander and one other card are banned

  * ✗ [Lavinia, Azorious Renegade + Knowledge Pool](https://commanderspellbook.com/combo/3903-4469/) is banned

- #### Everything else is fair game

  * ✓ [Sanguine Bond + Exquisite Blood](https://commanderspellbook.com/combo/690-3966/) is fine
  * ✓ Whatever other fucked up thing you can come up with is fine

### Game Changers

> Try to make it fun, and participate

- #### Any GC covered by an above rule remains banned by that rule

  * ✗ [Gifts Ungiven](https://scryfall.com/card/chk/62/gifts-ungiven) is already covered by the no immediate tutors rule, and so is banned

- #### Game Changers that are lands are banned

- #### You can have either [Rhystic Study](https://scryfall.com/card/pcy/45/rhystic-study) or [Smothering Tithe](https://scryfall.com/card/wot/87/smothering-tithe) but not both

- #### [Teferi's Protection](https://scryfall.com/card/plst/C17-8/teferis-protection) and [Thassa's Oracle](https://scryfall.com/card/thb/73/thassas-oracle) are banned

  * C'mon man you gotta play the game

- #### You are allowed to have 3 Game Changers that meet the above restrictions

## Open Questions v1

- MV for tutors should be lower? Maybe 5 is fine? Like, should WUBRG alt casting cost shit let you tutor?
- Does the MLD stuff even matter? Its a lot of rules and restrictions but ... would people even run this stuff? How many decks actually get advantage from MLD? If someone does build their whole deck around this maybe its just fine to let them win once and then they'll stop playing it because its not fun?
- Idk do tithe and rhystic just suck? Are they just always going to be the best ramp and draw in every deck that can play them no matter what?
- How many game changers? 1? 3? Unlimited? I think the current GC rules have axed a bunch of the shittiest ones, so maybe its fine now, but I really don't want to see 10 deck slots in every deck be GCs because they're STILL generically strong