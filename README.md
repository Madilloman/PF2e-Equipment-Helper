# PF2e Equipment Helper

Search and rank Pathfinder Second Edition equipment by class, level, budget, activation, skills and passive effects.

**Try it:** https://madilloman.github.io/PF2e-Equipment-Helper/

> ⚠️ This is a beta prototype. Expect rough edges, and please report anything that looks wrong.

## Feedback

- **Found a bug?** [Report a bug](https://github.com/Madilloman/PF2e-Equipment-Helper/issues/new?template=bug_report.yml)
- **Item data looks wrong?** [Report a data problem](https://github.com/Madilloman/PF2e-Equipment-Helper/issues/new?template=data_error.yml)
- **Have an idea?** [Suggest a feature](https://github.com/Madilloman/PF2e-Equipment-Helper/issues/new?template=suggestion.yml)

A free GitHub account is needed to open an issue.

## Key features

### Browse
Pick a **class**, **character level** and **budget (gp)**, and the app lists items you can afford at your level. You can also set an item level range, search item names and descriptions, and sort results by item score, level or price (ascending or descending).

- **Popular for this class:** Each class has a curated list of well-regarded gear, based on a class gear guide with star ratings. Choosing "Popular for this class" shows those items, and ranks them higher when you sort by item score.
- **What to look for:** A short guide box for the selected class that explains which kinds of gear matter most, and lists the items the guide recommends.
- **Filters:** Narrow results by item type, rarity, trait, worn slot, bulk, usage, hands, range, reload, content (Legacy or Remaster), weapon and armor details, activated abilities (action type, frequency, duration), and passive effects (bonus type, skill bonus, saving throw bonus, invested). A **Resistances and Immunities** section filters by resistance type, resistance value and immunity type. Each filter can include or exclude values.
- **Item score:** A button shows or hides a score on each result card. Hover over the score to see which tags added to or subtracted from it.
- **Hide items:** Hide any item you don't want to see again. Hidden items have their own tab, where you can restore them.

### Class Preferences
Every class has default preferences that decide how items are scored. You can change them: add a preference (such as a bonus type, skill, trait or "Popular for this class"), give it a weight, and set the highest weapon category your class is proficient with so higher-category weapons are scored down. Preferences can be reset to the defaults, and exported, shared or imported with a preferences code.

### Saved Item Lists
Save items to named lists, such as a shopping list for the next level or a party loot wish list. Add an item to a list from its result card, create as many lists as you like, and see the total gold value at the top of each list. Lists can be exported to and imported from a file. They are stored in your browser.

### Presets and sharing
Save your current filters as a named preset, or copy a share code that someone else can paste in to load the same filters.

### Item details
Result cards show level, price, bulk, traits, usage, hands, range, reload and activation details, plus a link to the item's entry on Archives of Nethys.

## How it works

The whole app is a single self-contained page (`index.html`) that runs in the browser. It has no server, account or tracking. Saved presets stay in your own browser.

Item data is a snapshot as of 11/16/2026 from the open-source [Foundry VTT PF2e System](https://github.com/foundryvtt/pf2e). Tags are assigned by text matching, so there may be edge cases where they do not align with the item; check the [Archives of Nethys](https://2e.aonprd.com/) link to confirm item details.

## Legal

See [NOTICE.md](NOTICE.md).

PF2e Equipment Helper uses trademarks and/or copyrights owned by Paizo Inc., used under Paizo's Community Use Policy ([paizo.com/licenses/communityuse](https://paizo.com/licenses/communityuse)). We are expressly prohibited from charging you to use or access this content. PF2e Equipment Helper is not published, endorsed, or specifically approved by Paizo. For more information about Paizo Inc. and Paizo products, visit [paizo.com](https://paizo.com).
