# Project Genesis: A High-Fantasy RTS

## 1. Core Concept

A high-fantasy, real-time strategy game where players command one of four unique factions in a struggle for dominance over a world rich with magic and ancient power. The game will focus on macro-economic management, strategic base-building, and tactical battles where unit abilities and synergy are key to victory.

## 2. Core Gameplay Loop

1.  **Gather Resources:** Collect the fundamental resources, **Aetherium** and **Eldritch Ore**, to fuel your economy and military.
2.  **Establish Foothold:** Construct a multi-tiered, defensible base with dedicated production facilities.
3.  **Produce & Upgrade:** Train a diverse army of melee, ranged, and specialty units, and research powerful upgrades to gain a tactical advantage.
4.  **Explore & Expand:** Scout the mystical landscape to secure additional resources and discover hidden map objectives.
5.  **Engage in Conflict:** Command your army in intense, strategic battles, using each unit's unique abilities to outmaneuver and defeat your opponent.

## 3. Technology Stack

* **Game Engine:** Unity
* **Programming Language:** C#
* **AI for Coding:** Gemini Code Assist (integrated with VS Code)

## 4. First Task: Game Engine Setup & "Hello, World!"

Create the foundational Unity project and a simple C# script to test our development environment. This will be the very first step in bringing our project to life.

## 5. Factions

-   **The Human Kingdom:** A versatile and disciplined force, masters of siege and holy power. Their strength lies in powerful, well-rounded units and battlefield-altering buffs and healing.
-   **The Dwarven Confederacy:** An engineering and defense-focused faction. They rely on heavy armor, powerful siege weaponry, and the ability to fortify positions, turning the battlefield into a slow, grinding war of attrition.
-   **The Dark Elf Conclave:** A shadowy faction that focuses on stealth, speed, and powerful, but fragile units. They master dark magic and assassination, winning battles through curses and deception.
-   **The Vampiric Horde:** A relentless and aggressive faction. They rely on overwhelming numbers, life-draining abilities, and powerful transformations, gaining strength from their opponent's losses.

## 6. Resources

### Primary Resource

**Aetherium:** A luminous, crystalline material representing the raw materials of the world. It is the fundamental building block for all factions and is gathered from deposits found across the map.

### Secondary Resource

**Eldritch Ore:** A rare, pulsating mineral that contains concentrated magical energy. It is a highly contested resource that is the key to a faction's most powerful technologies and spells. How each faction refines and uses it is unique to them:

* **Human Kingdom:** Refined into **Divine Essence** at their cathedrals for powerful holy abilities.
* **Dwarven Confederacy:** Purified into **Technium** at their forges for advanced mechanical units.
* **Dark Elf Conclave:** Corrupted into **Soul Shards** at their arcane altars to cast powerful curses and dark spells.
* **Vampiric Horde:** Transformed into **Ichor** at their blood altars, providing potent healing and life-stealing abilities.

---

## 7. Faction Tech Trees

### The Human Kingdom

A versatile, well-rounded faction with a focus on powerful units, healing, and discipline.

#### Main Building Tiers

* **Tier 1:** Sanctuary - The basic command center and worker training hub.
* **Tier 2:** Citadel - A fortified command center that unlocks Tier 2 units and buildings.
* **Tier 3:** Cathedral - The ultimate headquarters that unlocks the final tiers of units and upgrades.

#### Tier 1 - Foundations & Low-Tier Units

* **Barracks (Melee):**
    * **Unit:** Footmen - Basic, inexpensive, and fast-to-train melee infantry. The backbone of your early army.
* **Archery Range (Ranged):**
    * **Unit:** Hunters - Low-cost, low-damage ranged units for early-game scouting and harassment.
* **Flight School (Air):**
    * **Unit:** Mounted Scouts - Very fast, unarmed air units for scouting and carrying intelligence.

#### Tier 2 - Mid-Tier Units, Upgrades, & Siege

* **Barracks (Melee):**
    * **Unit:** Crusaders - Heavier and stronger than Footmen. They are the core of your mid-game army.
* **Archery Range (Ranged):**
    * **Unit:** Marksmen - Upgraded versions of Hunters with longer range and higher damage.
* **Flight School (Air):**
    * **Unit:** Sky Knights - Mid-tier air units equipped with bows. They can attack both ground and air targets.
* **Siege Workshop (Siege):**
    * **Unit:** Ballista - A mid-range, anti-armor unit for battlefield support. It excels at piercing heavy armor.

#### Tier 3 - High-Tier & Elite Units

* **Order of the Sun (Tech Building):** Produces the ultimate melee unit.
    * **Unit:** Paladin - An elite melee unit with high health and damage, and a powerful healing ability.
* **Arcane Spires (Tech Building):** Produces the ultimate ranged unit.
    * **Unit:** Arcane Archers - High-tier ranged units that fire magical arrows that pierce armor and can be upgraded to deal splash damage.
* **Celestial Beacon (Tech Building):** Produces the ultimate air unit.
    * **Unit:** Solar Angels - The ultimate air unit, dealing immense magical damage to both ground and air targets.
* **Divine Catapult (Unit):** A slow, powerful, high-tier siege weapon that deals area-of-effect damage to break up enemy formations. This unit requires a `Siege Workshop` to be built and trained.

#### Unit Upgrades

* **General Upgrades (Armory):**
    * `Forged Plating`: Increases the armor of all ground units.
    * `Sharpened Blades`: Increases the damage of all melee units.
    * `Precision Archery`: Increases the range and accuracy of all ranged units.
* **Unit-Specific Upgrades (Abilities & Specializations):**
    * `Shield Wall` (Footmen): An active ability that significantly increases armor but reduces movement speed.
    * `Shield Bash` (Crusaders): An active ability that allows them to stun an enemy for a short period.
    * `Arcane Volley` (Marksmen): An active ability to fire a volley of arrows that can pierce through multiple enemies.
    * `Aura of Glory` (Sky Knights): A passive ability that grants a small attack bonus to all nearby allied units.
    * `Battlefield Rally` (Paladin): A powerful active ability that grants all nearby allied units a large temporary attack and defense boost.
    * `Magical Containment` (Arcane Archers): A passive ability that gives their attacks a chance to temporarily silence enemy spellcasters.
    * `Divine Storm` (Solar Angels): A powerful area-of-effect spell that calls down a storm of light.

---

### The Dwarven Confederacy

An engineering and defense-focused faction, relying on heavy armor, powerful siege weaponry, and the ability to fortify positions.

#### Main Building Tiers

* **Tier 1:** Stronghold - The basic mining and military outpost.
* **Tier 2:** Fortress - The main hub for mid-game production.
* **Tier 3:** Iron Bastion - The ultimate defensive bastion that unlocks the final tiers of units and upgrades.

#### Tier 1 - Foundations & Low-Tier Units

* **Warrior's Hall (Melee):**
    * **Unit:** Miners - Your basic, inexpensive melee infantry. They're good for early-game combat.
* **Forge (Ranged):**
    * **Unit:** Crossbowmen - Basic ranged units. Their crossbows are slow but deal high damage.
* **Engineer's Guild (Specialty/Tech):**
    * **Unit:** Tinkerers - A specialty unit that can set up small, automated turrets for defense.

#### Tier 2 - Mid-Tier Units, Upgrades, & Siege

* **Warrior's Hall (Melee):**
    * **Unit:** Iron Guard - Heavily armored warriors who can form a temporary shield wall.
* **Forge (Ranged):**
    * **Unit:** Riflemen - Mid-tier ranged units armed with high-impact rifles.
* **Engineer's Guild (Specialty/Tech):**
    * **Unit:** Artificer - A mid-tier support unit that can boost armor and repair units to full health.
* **Workshop (Siege):**
    * **Unit:** Mortar - A mid-tier siege unit with a high-arcing projectile that's effective for hitting units behind cover.

#### Tier 3 - High-Tier & Elite Units

* **Iron Heart Foundry (Tech Building):** Produces the ultimate melee unit.
    * **Unit:** Runemaster - The elite melee unit. They have passive magical resistance and are incredibly tough.
* **Ordnance Hall (Tech Building):** Produces the ultimate ranged unit.
    * **Unit:** Cannoneers - The high-tier ranged unit. They are armed with miniature cannons that deal devastating area-of-effect damage.
* **Automaton Workshop (Tech Building):** Produces the ultimate specialty unit.
    * **Unit:** Golem - The ultimate specialty unit. A slow, incredibly durable construct.
* **Siege Tank (Unit):** The ultimate siege weapon. It is a slow, heavily armored tank with a flamethrower that's good at destroying light units up close. This unit requires a `Workshop` to be built and trained.

#### Unit Upgrades

* **General Upgrades (Engineering Bay):**
    * `Dwarven Grit`: Increases the armor of all ground units.
    * `Masterwork Forging`: Increases the damage of all melee units.
    * `Rune-Infused Ammunition`: Increases the range and accuracy of all ranged units.
* **Unit-Specific Upgrades (Abilities & Specializations):**
    * `Ironclad Defense` (Iron Guard): An active ability that significantly boosts the armor of the Iron Guard for a short time.
    * `Overcharge` (Artificer): An active ability to temporarily increase the attack damage and armor of a single allied unit.
    * `Rune of Fortification` (Runemaster): A passive ability that gives the Runemaster a bonus to armor and health when they are near a friendly building or wall.
    * `Emergency Field Repair` (Tinkerers): An active ability that instantly restores a small amount of health to a single unit or building.
    * `Volatile Rounds` (Cannoneers): A passive upgrade that gives their shots a chance to cause a small explosion on impact, dealing a small amount of area-of-effect damage to nearby enemies.
    * `Static Aura` (Artificer): A passive ability that creates an aura around the Artificer, slightly slowing the attack speed of all nearby enemy units.
    * `Flamethrower Overload` (Siege Tank): An active ability that temporarily increases the range and damage of the tank's flamethrower.

---

### The Dark Elf Conclave

A shadowy faction that focuses on stealth, speed, and powerful but fragile units. They master dark magic and assassination, winning battles through curses and deception.

#### Main Building Tiers

* **Tier 1:** Shadow Sanctum - The central hub where workers are trained.
* **Tier 2:** Shadow Keep - A mid-game fortress that unlocks Tier 2 units and buildings.
* **Tier 3:** Oblivion Spire - The ultimate hub that unlocks the final unit tiers.

#### Tier 1 - Foundations & Low-Tier Units

* **Assassins' Guild (Melee):**
    * **Unit:** Shadow Stalkers - Fast melee units with a passive ability to turn invisible when not attacking.
* **Coven (Ranged):**
    * **Unit:** Dark Archers - Basic ranged units. Their arrows inflict a temporary poison effect that slows enemies.
* **Shadow Spire (Specialty/Tech):**
    * **Unit:** Witch - A basic caster that can inflict curses on enemy units to reduce their armor or movement speed.

#### Tier 2 - Mid-Tier Units, Upgrades, & Siege

* **Assassins' Guild (Melee):**
    * **Unit:** Bladedancers - Extremely fast, high-damage melee units with low health.
* **Coven (Ranged):**
    * **Unit:** Shadow Casters - Mid-tier ranged units that cast curses to temporarily reduce enemy unit armor and damage.
* **Shadow Spire (Specialty/Tech):**
    * **Unit:** Mind Flayer - A mid-tier specialty unit that can temporarily mind-control a single enemy unit, forcing it to fight for you.
* **Plague Workshop (Siege):**
    * **Unit:** Bone Catapult - A mid-range siege unit that hurls corrosive sludge, damaging enemy armor.

#### Tier 3 - High-Tier & Elite Units

* **Assassins' Guild (Melee):**
    * **Unit:** Executioners - The elite melee unit. They deal bonus damage to enemy heroes and high-tier units.
* **Coven (Ranged):**
    * **Unit:** Soul Reavers - The elite ranged unit. Their scythes can hit multiple enemies and inflict a powerful bleeding effect that deals damage over time.
* **Shadow Spire (Specialty/Tech):**
    * **Unit:** Necromancer - The ultimate specialty unit. They can resurrect fallen units from both factions.
* **Oblivion Spire (Tech Building):** Produces the ultimate air unit.
    * **Unit:** Void Drake - A powerful air unit with a magical breath attack that slows and damages enemies.
* **Siege Golem (Unit):** A high-tier, lumbering siege unit. Its primary function is to lay down corruption fields that damage buildings and units over time. This unit requires a `Plague Workshop` to be built and trained.

#### Unit Upgrades

* **General Upgrades (Dark Altar):**
    * `Poisoned Blades`: Increases the damage of all melee units.
    * `Shadow Weaving`: Increases the armor of all units.
    * `Vile Enchantments`: Increases the attack speed of all ranged units.
* **Unit-Specific Upgrades (Abilities & Specializations):**
    * `Backstab`: A passive ability for `Shadow Stalkers` that grants a bonus to their first attack when invisible.
    * `Blood Frenzy`: A passive ability for `Bladedancers` that increases their attack speed as their health gets lower.
    * `Curse of Weakness`: An active ability for `Shadow Casters` that temporarily disables an enemy unit's special abilities.
    * `Mind Harvest`: A passive ability for `Mind Flayers` that allows them to instantly drain a portion of an enemy's health to restore their own.
    * `Pestilence Scythes`: A passive ability for `Soul Reavers` that makes their attacks infect enemies, causing them to deal less damage and spread the infection to nearby units.
    * `Raise Dead`: An active ability for `Necromancers` that resurrects a small group of fallen infantry units.
    * `Unstable Corrosion`: An active ability for `Bone Catapults` that allows them to fire an extra-damaging projectile that also slows units in the impact area.

---

### The Vampiric Horde

A relentless faction that relies on overwhelming numbers, life-draining abilities, and powerful transformations.

#### Main Building Tiers

* **Tier 1:** Blood Spire - The central hub where units are drained for resources and workers are trained.
* **Tier 2:** Vampiric Keep - A mid-game stronghold that unlocks Tier 2 units and buildings.
* **Tier 3:** Throne of Blood - The ultimate command center that unlocks the final unit tiers.

#### Tier 1 - Foundations & Low-Tier Units

* **Carrion Pit (Melee):**
    * **Unit:** Ghouls - The basic, inexpensive melee unit. They gain a temporary boost to their attack speed after killing an enemy unit.
* **Blood Crypt (Ranged):**
    * **Unit:** Blood Archers - Basic ranged units. Their arrows inflict a bleeding effect that damages enemies over time.
* **Fleshcrafters' Den (Specialty/Tech):**
    * **Unit:** Plague Doctor - A mid-tier support unit that can heal and buff allied units, and also inflict a powerful disease on enemies.
* **Pestilence Workshop (Siege):**
    * **Unit:** Mortar - A mid-range, area-of-effect unit that hurls explosive projectiles.

#### Tier 2 - Mid-Tier Units, Upgrades, & Siege

* **Carrion Pit (Melee):**
    * **Unit:** Bloodfiends - A mid-tier, fast melee unit with a powerful life-draining attack.
* **Blood Crypt (Ranged):**
    * **Unit:** Ghoul Throwers - A ranged unit that throws plague-infested corpses, dealing area-of-effect damage to enemies.
* **Fleshcrafters' Den (Specialty/Tech):**
    * **Unit:** Plague Doctor - A mid-tier support unit that can heal and buff allied units, and also inflict a powerful disease on enemies.
* **Pestilence Workshop (Siege):**
    * **Unit:** Mortar - A mid-range, area-of-effect unit that hurls explosive projectiles.

#### Tier 3 - High-Tier & Elite Units

* **Carrion Pit (Melee):**
    * **Unit:** Vampire Lords - The ultimate melee unit. They have very high health and armor, and their life-draining attack is incredibly powerful.
* **Blood Crypt (Ranged)::**
    * **Unit:** Blood Reapers - The elite ranged unit. Their scythes can hit multiple enemies and inflict a powerful bleeding effect that deals damage over time.
* **Fleshcrafters' Den (Specialty/Tech)::**
    * **Unit:** Bone Golem - The ultimate specialty unit. A slow, incredibly durable unit that can temporarily boost the armor of nearby units.
* **Throne of Blood (Tech Building)::** Produces the ultimate air unit.
    * **Unit:** Bat Rider - A fast-flying unit that can drop explosive bat bombs on enemies.
* **Siege Trebuchet (Unit):** A high-tier, lumbering siege unit. Its projectiles inflict a powerful plague that damages buildings and units over time. This unit requires a `Pestilence Workshop` to be built and trained.

#### Unit Upgrades

* **General Upgrades (Pestilence Workshop):**
    * `Blood-Infused Armor`: Increases the armor of all ground units.
    * `Carrion Rush`: Increases the movement speed of all melee units.
    * `Infected Ammunition`: Increases the damage of all ranged units.
* **Unit-Specific Upgrades (Abilities & Specializations):**
    * `Swarm`: An active ability for Ghouls that summons a small group of additional Ghouls for a short time.
    * `Infection`: A passive ability for Blood Archers that gives their arrows a chance to infect enemies, causing them to deal less damage.
    * `Plague Cloud`: An active ability for Plague Doctors that creates a temporary cloud that heals allies and damages enemies.
    * `Essence Drain`: A passive ability for Vampire Lords that greatly increases the amount of life they drain from each attack.
    * `Blood Ritual`: An active ability for Blood Reapers that allows them to instantly drain a large amount of life from a single enemy unit, healing themselves and other nearby friendly units.
    * `Plague Aura`: A passive ability for Plague Wagons that slows and damages nearby enemy units.
    * `Explosive Bats`: An upgrade for Bat Riders that allows them to drop a powerful bomb that deals area-of-effect damage.