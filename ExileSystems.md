ExileSystems API docs
===================

----------


game_1_getNextNumber($name);
---
Accepts a name of a player in game 1 (str).
Returns a random number for game 1 (int).

---
generateID();
---
Accepts nothing.
Returns a random inmate ID tag (str).

---

getRandomAdvert();
---
Accepts nothing.
Returns an array.
```$title = $array[0];```
```$desc = $array[1];```
```$link = $array[2];```

---
isVIP($player);
---
Accepts a player.
Returns true/false.

---
getKitDescription($id);
---
Accepts kit id (int).
Returns a description (str).

---
getVIPKits();
---
Accepts nothing.
Returns an array of int.

---
getKitById($id);
---
Accepts kit id (int).
Returns unknown.

---
getKitsForPlayer($player);
---
Accepts player.
Returns an array.

---
kitList($page, $player);
---
Accepts page number and player.
Returns kit list to player.

---
applyKit($player, $id);
---
Accepts player and kit id.
Adds kit to player.

---
AddPlayer($player);
---
Accepts player.
Creates a new player record.

---
getPlayer($player);
---
Accepts player.
Returns an array from table `identity`.
```$title = $array[0];```
```$desc = $array[1];```
```$link = $array[2];```

---
getID();
---
Accepts id?.
Returns unknown.

---
getPRank($player);
---
Accepts player.
Returns player rank.

---
getPDeny($player);
---
Accepts player.
Returns an array.

---
getPID($player);
---
Accepts player.
Returns an id (str).

---
getKicks($player);
---
Accepts player.
Returns an int.

---
getPCoins($player);
---
Accepts player.
Returns an int.

--
addKick($player);
---
Accepts player.
Updates database.

---
getGroup($player);
---
Accepts player.
Returns str.

---
getOwnedCell($player);
---
Accepts player.
Returns cell manager cell.

--
sendBigMessage($player, $message, $message2, $lines);
---
Accepts a lot.

---

