[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
# Order Up Mod
> :warning: This mod is a work in progress and the author is new to Minecraft Modding, Java programming, and just about every other skill required to be successful in this endeavor.

---
Order Up! Create your dream food franchise service that exchanges good eats with customers for materials, technology, magic, and renown. Your customers will get pickier as you get more efficient, so explore for as many unique ingredients as you can find (and farm) to continue fulfilling their orders and progressing in the mod. You may question their unusual orders occasionally, but the customer is always right. Give them what they want to ~exploit the products of their labor~ acquire important resources. Inspired by restaurant-themed games and cartoons including Spongebob, Overcooked and Dave the Diver's Sushi restaurant, and late Capitalism humor.

- Food is currency!
- Obtain a business license to craft an `Order Counter`
- Place an `Order Counter` in a village to get started. Upgrade your `Order Counter` to remotely accept and deliver orders!
- Receive higher tier materials by completing unusual or picky requests
- Place a `Billboard` with `Fliers` to control your menu, increase orders, and close up shop
- Exploration is rewarded with `Special Order Fliers`, new customers, and more challenging orders!
- Different customers might appear depending on what you make available or which orders you fulfill.
- Watch out for Shady Customers that appear and make orders when you collect... non-traditional ingredients. They also have surprisingly sophisticated technology!
- Your `Franchise SOP` is missing some pages... if you stumble upon them, be sure to explore them!

## General development plan:

### Blocks
- Order Counter: This is the main block of the mod that connects you to your customers and their orders.
- Billboard: Use fliers on a billboard to promote your franchise or announce closures within a village.
- R.O.D.S.: The Remote Ordering and Delivery System is an advanced verion of the Order Counter that allows you to fulfill orders from anywhere using questionably dubious proprietary technology.

### Items
- `Franchise SOP`: A crusty copy of corporate's new-hire materials. It appears to be damaged and is missing some pages...
- `Business License (counterfeit)`: We all have to start somewhere!
- `Business License (legitimate)`: A real business license! You aren't exactly sure how this one is different from your other one... yet.
- `Marketing Flier`: Helps spread the word in a new village that you are accepting orders! Marketing fliers help increase the number of orders you receive at the order counter.
- `Closure Flier`: Removes marketing fliers from billboard. Stops order generation.
- `Special Order Flier`: Dungeon loot sometimes contains ancient promotional materials. You think you can spin these old ideas into your revenue stream by placing them on a billboard.
- `Menu Flier`: If you want to serve more of a particular item, craft the item with a marketing flier and add it to the billboard. The item itself won't be consumed but the marketing flier will be.

### Logic and Game Mechanics
- `Renown`: Renown is a combination of metrics that determine how well known your franchise is. Higher renown attracts more orders. Renown will unlock tiers of knowledge in the mod's book and each tier's respective crafting recipes. Occasionally tiers will require a certain number of certain types of orders be completed.

#### Order Types
  - `Basic orders`: Basic requests are simple to fill, usually vanilla minecraft food or mod-specific foods if a villager with a modded profession is making the request.
  - `Unusual orders`: Some customers have unusual requests. Don't ask questions and you may end up with more interesting rewards.
  - `Picky orders`: Some customers have difficult requests to fulfill. Meet their needs and they will certainly reward you well. The proportion of picky customer requests increase over time as you complete basic customer requests. You'll need to keep exploring and farming new ingredients to keep up with demand!
  - `Shady Orders`: Occasionally, a shady customer might place an order at your counter when you collect unique or unusual ingredients. If you can deliver what they are asking for, these orders can be some of the most rewarding!
 
## Compatibility
This mod will be playable in vanilla minecraft, but savvy pack developers can take advantage of configuring this mod to include other foods, mobs, etc. More on this later! I'd like to use this mod for the following:
- Food mods
- Mods that add new villagers and villages
- Mods that add NPCs, humanoid mobs
- Rare items included in dungeon loot
- Eventually an Order Up themed modpack


