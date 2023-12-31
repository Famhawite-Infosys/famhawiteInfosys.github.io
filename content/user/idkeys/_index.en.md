---
title: "Identification Keys"
date: 2022-10-31
lastmod: 2022-10-31
draft: false
weight: 52
authors: ["Katie Pearson"]
keywords: ["checklist","keys","identification","character","state","ID"]
---

{{< notice info >}}
This page describes how to navigate identification keys built in to checklists in Symbiota portals. View our documentation about [checklists](https://biokic.github.io/symbiota-docs/user/checklist/), [editing characters and character states](https://biokic.github.io/symbiota-docs/user/idkeys/admin/), and [editing character states applied to taxa](https://biokic.github.io/symbiota-docs/user/idkeys/edit/). {{</ notice >}}

### Structure of Identification Keys

Identification keys are built from a list of **characters** that each have multiple **states**.

**Characters** are categories of traits that are shared across all members of a taxon (e.g., "average wing length" or "leaf phyllotaxy").

A **state** is the specific trait that is shared within the taxon (e.g., "3-15 mm" or "opposite", for each of the characters above). At this time, states can only be categorical (i.e., you cannot enter a number value).

![Character and Character States Example](/symbiota-docs/images/charactervsstate.jpg)

Setting up identification keys in a portal requires the administrator to import or add character and state values (see ID Keys Administrator instructions [here](https://biokic.github.io/symbiota-docs/user/idkeys/admin/). Then, an identification keys editor can assign certain state values to certain taxa (see ID Keys Editor Instructions [here](https://biokic.github.io/symbiota-docs/user/idkeys/edit/)).

### Using Identification Keys

{{< notice note >}}
Identification keys are not turned on and/or configured in all portals and require extensive configuring in order to be used across many taxa. To access this feature, contact your portal administrator. {{</ notice >}}

Identification keys can be used within checklists to identify a taxon within the list that possesses certain character states. A user can click the character states that match those of their sample/individual of interest, and the taxon/taxa with the same character state(s) will be displayed on the checklist.

![Identification Keys Example](/symbiota-docs/images/idkeys1.jpg)

Note that the taxa you will see on the left will **only** include those that were in the original checklist.

### Related Resources

{{< youtube GMk2WkE3Hno >}}
