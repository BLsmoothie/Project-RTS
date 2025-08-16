# Real-Time Strategy Game Project Plan

## 1. Core Concept

A high-fantasy real-time strategy game. Players will command one of four distinct factions, gathering resources, building bases, and leading armies to victory.

## 2. Core Gameplay Loop

1.  **Gather Resources:** Collect primary and secondary resources to fuel your economy.
2.  **Build Infrastructure:** Construct a base with essential buildings for unit production and research.
3.  **Produce Units:** Train and upgrade units from your military structures.
4.  **Explore and Expand:** Scout the map to find resources and engage enemies.
5.  **Engage in Combat:** Command your army in real-time battles against opponents.

## 3. Technology Stack

* **Game Engine:** Unity or Unreal Engine (to be decided later).
* **Programming Language:** C# (for Unity) or C++ (for Unreal Engine).
* **AI for Coding:** Gemini Code Assist (integrated with VS Code).

## 4. First Task: "Hello, World!"

Create the foundational game project and a simple script to test the engine setup. This will be our first step into actual development.

## 5. Factions

- **The Human Kingdom:** A versatile, well-rounded faction.
- **The Dwarven Confederacy:** A slow, powerful, and technology-driven faction.
- **The Dark Elf Conclave:** A faction focusing on dark magic and shadow tactics.
- **The Vampiric Horde:** An aggressive, life-draining faction.

## 6. Resources

### Primary Resource

**Aetherium:** A universal resource representing the raw materials of the world. It is a fundamental building block for all factions and is gathered from deposits found across the map.

### Secondary Resource

**Eldritch Ore:** A rare and powerful magical mineral found in limited quantities. It is a highly contested resource that is the key to a faction's most powerful technologies and spells. How each faction refines and uses it is unique to them:

-   **Human Kingdom:** Refined into **Divine Essence** at their cathedrals.
-   **Dwarven Confederacy:** Purified into **Technium** at their forges.
-   **Dark Elf Conclave:** Corrupted into **Soul Shards** at their arcane altars.
-   **Vampiric Horde:** Transformed into **Ichor** at their blood altars.

## 7. Faction Tech Trees

### The Human Kingdom

A versatile, well-rounded faction with a focus on powerful units, healing, and discipline.

#### Main Building Tiers
* **Tier 1:** Sanctuary
* **Tier 2:** Citadel
* **Tier 3:** Cathedral

#### Tier 1 - Foundations & Low-Tier Units
* **Barracks (Melee):**
    * **Unit:** Footmen - Basic, inexpensive, and fast-to-train melee infantry.
* **Archery Range (Ranged):**
    * **Unit:** Hunters - Low-cost, low-damage ranged units.
* **Flight School (Air):**
    * **Unit:** Mounted Scouts - Very fast, unarmed air units for scouting.

#### Tier 2 - Mid-Tier Units, Upgrades, & Siege
* **Barracks (Melee):**
    * **Unit:** Crusaders - Heavier and stronger than Footmen. Unlocked via a `Training Regimen` upgrade.
* **Archery Range (Ranged):**
    * **Unit:** Marksmen - Upgraded versions of Hunters with longer range and higher damage. Unlocked via a `Precision` upgrade.
* **Flight School (Air):**
    * **Unit:** Sky Knights - Mid-tier air units equipped with bows. Unlocked via a `Aerial Combat Training` upgrade.
* **Siege Workshop (Siege):**
    * **Unit:** Ballista - A mid-range, anti-armor unit for battlefield support.

#### Tier 3 - High-Tier & Elite Units
* **Order of the Sun (Tech Building):** Produces the ultimate melee unit.
    * **Unit:** Paladin - An elite melee unit with high damage and a unique ability to briefly buff nearby units.
* **Arcane Spires (Tech Building):** Produces the ultimate ranged unit.
    * **Unit:** Arcane Archers - High-tier ranged units that fire magical arrows that pierce armor.
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
* **Tier 1:** Stronghold
* **Tier 2:** Fortress
* **Tier 3:** Iron Bastion

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
    * **Ironclad Defense** (Iron Guard): An active ability that significantly boosts the armor of the Iron Guard for a short time.
    * **Overcharge** (Artificer): An active ability to temporarily increase the attack damage and armor of a single allied unit.
    * **Rune of Fortification** (Runemaster): A passive ability that gives the Runemaster a bonus to armor and health when they are near a friendly building or wall.
    * **Emergency Field Repair** (Tinkerers): An active ability that instantly restores a small amount of health to a single unit or building.
    * **Volatile Rounds** (Cannoneers): A passive upgrade that gives their shots a chance to cause a small explosion on impact, dealing a small amount of area-of-effect damage to nearby enemies.
    * **Static Aura** (Artificer): A passive ability that creates an aura around the Artificer, slightly slowing the attack speed of all nearby enemy units.
    * **Flamethrower Overload** (Siege Tank): An active ability that temporarily increases the range and damage of the tank's flamethrower.