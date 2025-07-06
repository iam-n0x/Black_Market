# BlackMarket 2.6.23

This mod enables weapons trading for GAMMA, with some caveats. If you want to sell weapons, you will have to repair them and find a buyer 
who wants that type of weapon.

## Changelog

See [`CHANGELOG.md`](CHANGELOG.md) or [`Changelog_BM.txt`](Changelog_BM.txt).

## Credits (in no specific order)

Original Idea/Author @SalamanderAnder on [G.A.M.M.A discord](https://discord.gg/stalker-gamma).

- @zredvenomz
- @iceking79
- @gentlemangoose
- @VVLàD
- @Dyshes
- @strangerism
- @rasde
- @Wulfos3
- @firehome
- @markuzkiller
- @bvcx
- @TheMrDemonized
- @Grok
- @RavenAscendant
- @artifax
- [Anomaly Discord](https://discord.com/invite/c4RuJNs)
- [G.A.M.M.A Discord](https://discord.gg/stalker-gamma)
- and every goddamn dude that made this possible.

## Installation

- Remove any old versions of this mod.
- Install with MO2 at the end of your load order.

## What it does

The mod combines aspects of GAMMA economy with Trader Overhaul, with a twist.

1. Weapon traders have been categorized into a tier system. They are organized by WP/NATO preference (in line with GAMMA lore), 
and then each category is ranked into a 3 tier system based on base weapon price.

   *Most* traders that have chosen to purchase weapons have a Faction preference AND a Tier preference. 
   "Unlawful" factions may have traders who will buy any weapon. This is subject to change, 
   although I feel it is somewhat balanced since unlawful playthroughs have additional difficulties like less trader access.

2. Trade with random stalkers is back on the table (if you disabled it in your mod loader)
   - Stalkers are willing to buy ANY weapon (assuming they will trade with you at all, this depends if they have anything to sell)
   - Random stalker money amounts have been slightly increased
   - The amount of starting money stalkers have available for trading is tied to their rank when spawned (a default feature)
   - Random stalker buy coefficient has been slightly lowered. They will offer you the lowest offer for your goods compared to any trader, 
   only 10% of the value.

***IMPORTANT***

In order for the money limit changes to take effect, a new game is required. Unfortunately those numbers are generated when the AI is spawned, 
using the character_desc XML files.

That being said, the mod will STILL WORK on an old save. Random stalkers will just have a little less money on average available to trade.

---

The goal here is to facilitate a "black market" for weapons.

I tried to assign the tiers in a way that makes sense given trader's faction, location in the zone, and economics for each area.

For example

- in Cordon, Sid and Loris aren't going to risk getting caught by the military trading weapons — especially since nobody in Cordon really 
has any money to BUY weapons anyway. 
- The flea market guys are a bit more bold, but it still makes no sense for them to buy some crazy expensive tacti-kool-aid rifle when 
everyone around them has very few Rubles for trading anyway. So they stick to buying low tier stuff.
- Monolith and the Military on the other extreme wouldn't be affected by the ban.

  We can assume the Military is still allowed to procure weapons, and they might even be ENCOURAGED to buy weapons as a sort of 
  buy-back program, if the EU/UN is actually serious about trying to clean up the zone. 
  And of course the Monolith — why would the C-consiousness care one bit about the laws of the EU and UN?

So hopefully these features are logical and balanced. I just think not being able to sell guns at ALL doesn't really make sense.

With imports limited, stalkers in the zone would be more willing than ever to trade weapons within the zone. This implementation 
aims to create that opportunity, where you still have to invest money into tools to repair the weapons you want to sell, 
just like how you have to invest in the artefacts melter to make better condition artefacts to sell.
