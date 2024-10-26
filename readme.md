# Player Data Repository

This repository contains a JSON file with player data that is used in the sports player management site [Pha07](https://pha07-khbmh.surge.sh/). The data includes various details about cricket players, making it easy to manage and display player information on the site.

## Where This Data Is Used

The player data is utilized in the [BPL Dream Six](https://pha07-khbmh.surge.sh/) website, where users can view player profiles, manage selections, and make a dream team of six players.

## JSON Structure

The JSON file consists of an array of player objects. Each object contains the following properties:

- **id**: Unique identifier for the player (integer).
- **name**: Name of the player (string).
- **age**: Age of the player (integer).
- **team**: National or club team of the player (string, includes flag emoji).
- **role**: The player's role (string, e.g., Batsman, Bowler).
- **price**: Market price of the player (float).
- **points_per_match**: Average points scored by the player per match (integer).
- **batting_type**: Type of batting (string, e.g., Right-hand bat).
- **bowling_type**: Type of bowling (string, typically "N/A" for non-bowlers).
- **isAllRounder**: Boolean indicating if the player is an all-rounder (boolean).
- **image**: URL of the player's image (string).

### Example Player Object

```json
{
  "id": 1,
  "name": "Virat Kohli",
  "age": 35,
  "team": "India 🇮🇳",
  "role": "Batsman",
  "price": 10.5,
  "points_per_match": 75,
  "batting_type": "Right-hand bat",
  "bowling_type": "N/A",
  "isAllRounder": false,
  "image": "https://www.sportsadda.com/static-assets/waf-images/d4/f6/21/16-9/ED18fuD724.jpg?v=1.6&w=420%20420w"
}
