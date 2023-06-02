# Victoria 3 multiplayer mod compilation
Features marked as **Experimental** may be pulled from release or banned mid-game. It's reserved for things that sound like a good idea but are tough to test without a real multiplayer environment.


**Diplomatic actions:**

1. State transfer (
Transfer state by marking them with a 0 cost decree. You need to have positive authority.
2. Increase/decrease autonomy allows to change between puppet, dominion, protectorate. Decreasing autonomy allowed only on player subjects. (Experimental)
3. Transfer subject
4. Guarantee Independence - one way defensive pact that doesn't require the other party to accept. It makes it so the guarantor can always be on the defensive side of the diplomatic play.
5. Customs unions are no longer overlord>subject relation. They are more of an economic tool and Two GPs can be in a customs union now
6. Transfer cash.

**Unincorporated States change:**
- state expected SoL from -33% to -40%
- poor strata expected sol -3
- middle strata expected sol -2
- construction sector max throughput bonus (from economies of scale) -80%
- max amount of barracks -75
- starting wages -33%  
  
**Colonial explotation Law**

No longer a flat 10% bonus to throughput. It now provides a modifier dependant on level of colonial institution:
- 4/8/12/16/20% bonus to throughput of agriculture, ranching, plantations, mining, logging, fishing, whaling and oil extraction 
- increased mortality of 1/1/2/2/3% per Turmoil
- increased mortality of 3/4/5/6% for laborers, machinists, farmers and peasants

**Technology**

1. vanilla 1.2 values (1.3 made tech cheaper)
2. restructured miilitary tree to delay some tech. Costs stay the same, moved the tree around.
- Trench works now also require Handcranked Machine Gun

These changes are aimed at delaying lategame tier 5 army tech and making it a progression. In Vanilla Infiltrators, Flamethrowers and Chemical warfare are parallel tech with Chemical Warfare being clearly the best option for most Multiplayer wars.
- Stormtroopers (Infiltrators) are now a Tier 4 technology, same requirements (Wargaming, Trench Works)
- Flamethrowers additionally require Stormtroopers
- Chemical warfare requires Flamethrowers and Concrete fortifications

3. New Oil Extraction technologies (after Pumpjacks). 
- Oil Extraction I (Tier 4). Output 10%, Throughput 10%
- Oil Extraction II (Tier 5). Output 25%, Throughput 25%
- Oil Extraction III (Tier 5). Output 25%, Throughput 25%
- Oil Extraction IV (Tier 5). Output 25%, Throughput 25%
- Oil Extraction V (Tier 5). Output 25%, Throughput 25%

4. Oil boost added to existing techs (2% output & throughput each)
  - mechanized farming
  - conveyors
  - combustion engine
  - oil turbine
  - central planning
  - macroeconomics
  - paved roads

**Pop growth**
  - min_birthrate 0.0017 to 0.0020
  - max_birthrate 0.0045 to 0.0050

**Suez & panama canals are actually good** (experimental)
Upgradeable. Balanced for having up to lvl 10 canal (will be a game rule). Values for full employment:
1. Country-wide:
  - 5000 minting
  - 0.2 industrialists approval
  - 5 tax capacity
  - 1000 convoys

  2. State modifiers:
  - 10 infrastructure
  - 5% migration pull

3. 450 transportation goods output, 100 tools input, 50 paper input. Hires 800 clerks, 800 machinists, 50 capitalists

**Military:**
- lower attrition (min 0.05>0.02, max 0.15 > 0.1)
- trench infantry -5 def
- concrete fortifications 40 to 35% def
- 1 naval invasion per strategic region at a time

**Africa resources & arable land increase**
10% flat increase in arable land and resources (wip, experimental)


**New oil wells** by Otto
- 70 in indonesia
- 10 in Japan
- 20 in Burma
- 10 in Austria
- 25 in Argentina
- 15 in Peru
- 15 in Colombia
- 40 in Venezuela
- 5 in the West Indies
- 290 in the USA

**China AI Buff**
- 50 construction, agriculture & resources throughput

**Bank of Netherlands**
- netherlands can have bigger gold reserves

**Ports fix**
- convoys from ports reverted to pre 1.3

**Japan Meiji Restoration Events**
In vanilla, Japan gets events for military, production and society where some of the options give increase to tech spread for 2.5 years. 
- duration changed to 5 years and added a 10% tech cost reduction.
- additional tech boosts also happen when Meiji Restoration is complete

**Universities**
- Can only build new universities if there is less than 100 in the country