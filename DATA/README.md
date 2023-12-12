## Dataset Source<a name="dataset-source"></a>

The dataset utilized in this project is "The Complete Pokémon Index," sourced from Kaggle. This dataset provides comprehensive information on over 800 Pokémon, encompassing 41 attributes. The data is publicly available on Kaggle, and no license is required for usage.

### Field Descriptions<a name="field-descriptions"></a>

#### Data File
- **URL (Type: string):** The web address for the data containing the dataset, including the protocol, host name, and subdomain. Some URLs may include parameters or named anchors.
- **Authors (Type: string):** The dataset's author obtained information from pokemondb.net and serebii.net through web scraping. Kaggle serves as the publisher.

#### Dataset
- **Pokedex Number (Type: integer):** The entry number of the Pokémon in the National Pokedex order.
- **Name (Type: string):** The Pokémon's name in various languages, including English, German, Japanese, Korean, and French.
- **Type (Type: string):** The Pokémon's primary and secondary types, with 18 possible types such as Normal, Fire, Water, etc. Pokémon can have dual types.
- **Classification (Type: string):** Describes the Pokémon based on defining biological characteristics, displayed in English with two or more texts.
- **Generation (Type: string):** Indicates the number of generations the Pokémon was first created, with a current total of 8 generations.
- **Legendary (Type: string):** Denotes the Pokémon's legendary status, indicating rarity and power.
- **Height (Type: float):** The height of the Pokémon in meters.
- **Weight (Type: float):** The weight of the Pokémon in pounds or kilograms.

#### Pokemon Stats
- **Hit Points (HP) (Type: integer):** Represents the Pokémon's health and maximum damage it can receive before fainting.
- **Attack (Type: integer):** Indicates the damage a Pokémon deals with physical moves.
- **Defense (Type: integer):** Represents the Pokémon's resistance to damage from an opponent's physical move.
- **Special Attack (Type: integer):** Shows the damage caused by a Pokémon using special physical moves.
- **Special Defense (Type: integer):** Represents the Pokémon's resistance to damage from a special move.
- **Speed (Type: integer):** Determines the order of actions in battle.
- **Total (Type: integer):** The sum of HP, Attack, Defense, Special Attack, Special Defense, and Speed.
- **Average (Type: float):** Calculated by dividing the total by the number of Pokémon base stats fields (Total/6).

### Data Context<a name="data-context"></a>

The Pokémon game, organized into a Pokedex, spans nine generations across various games. This analysis focuses on data from the perspective of Nintendo GameBoy and Switch formats. Pokémon can be bought, traded, or caught in the wild within the game context. The analysis excludes items altering Pokémon characteristics and does not differentiate between...




