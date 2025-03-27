Data Dictionary
Board Game Analysis: Board Game Geek, Adam Bartoszek and Judd Jacobs

| Field | Datatype | Description |
|-------|----------|-------------|
| ID | float64 | Unique ID assigned to a board game added to BoardGameGeek |
| Name | object | Name of the board game |
| Year Published | float64 | Year board game was originally published |
| Min Players | int64 | Minimum number of players needed to play the game |
| Max Players | int64 | Maximum number of players who can play the game |
| Play Time | int64 | Expected play time |
| Min Age | int64 | Minimum recommended age to play the game |
| Domains | object | List of gameplay types - can include more than one |
| objectid_jj | float64 | the ID from BGG for items specifically in Judd's collection |
| own_jj | float64 | A flag to represent if Judd own's the item |
| bggrecagerange_jj | object | Recommended Age range from BoardGameGeek from Judd's library |
| itemtype_jj | object | Description of if the game is a standalone or expansion of an existing game for Judd's library |
| objectid_ab | float64 | the ID from BGG for items specifically in Adam's collection  |
| own_ab | float64 | A flag to represent if Adam own's the item  |
| bggrecagerange_ab | object | Recommended Age range from BoardGameGeek from Adam's library |
| itemtype_ab | object | Description of if the game is a standalone or expansion of an existing game for Adam's library |
| objectid_comb | float64 | Combined objectid from both Adam and Judd's datasets |
| bggrecagerange_comb | object | Combined bggrecagerange from all three datasets |
| bggrecagerange | object | Recommended age range from BoardGameGeek's dataset |
| DisplayMapping | object | Created to assist in mapping age range for better display |
| AggregateMapping | object | Mapping various age ranges to larger buckets for easier aggregation |
| Judd | int64 | A flag created is Judd owns the game |
| Adam | int64 | A flag created is Adam owns the game |
| BGG | int64 | A flag created is BGG owns the game (set to 1 since BGG data is considered all known games) |