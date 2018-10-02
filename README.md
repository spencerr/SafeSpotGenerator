# SafeSpotGenerator

Utility to determine spots within Runescape that you can safely range monsters from a distance behind objects.

SafeSpot#generateSafeSpots(RSNPC...) finds all safespots with 8 tiles for the given npcs and returns a HashMap<RSNPC, ArrayList<RSTile>> which lists the valid safe spots per ncp.
  
SafeSpot#generateSafeSpots(int, RSNPC...) finds all safespots with x tiles.

