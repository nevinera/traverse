# Dungeons

Each Campaign has its own directory, and there's an extra directory for development that doesn't have
a campaign to go in yet (flexible dungeons that could be used wherever we need them, enemies that we might
want to add to something later).

The campaign directory has a file for each dungeon, which contains a map, notes about the dungeon, any extra
rules, player objectives, etc. It also should have the full stats of all enemies found in that dungeon, copies
from the monsters file. All monsters should be present (and identical) in the dungeon *and* in the monsters toplevel
directory, which includes the full stats of every monster we have (for reuse). The monster descriptions in the
dungeon file, however, may include information about what items the monster is carrying, and any special rules
that may come into play that are specific to this dungeon.
