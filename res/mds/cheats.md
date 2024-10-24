
All Plugins (9)

[Cheats](https://github.com/zuckung/plugin-archive/blob/main/res/mds/cheats.md) (2) | [Gameplay](https://github.com/zuckung/plugin-archive/blob/main/res/mds/gameplay.md) (2) | [Graphics](https://github.com/zuckung/plugin-archive/blob/main/res/mds/graphics.md) (2) | [Outfits](https://github.com/zuckung/plugin-archive/blob/main/res/mds/outfits.md) (0)<br>
[Overhauls](https://github.com/zuckung/plugin-archive/blob/main/res/mds/overhauls.md) (0) | [Overwrites](https://github.com/zuckung/plugin-archive/blob/main/res/mds/overwrites.md) (0) | [Patches](https://github.com/zuckung/plugin-archive/blob/main/res/mds/patches.md) (0) | [Races](https://github.com/zuckung/plugin-archive/blob/main/res/mds/races.md) (2)<br>
[Ships](https://github.com/zuckung/plugin-archive/blob/main/res/mds/ships.md) (0) | [Story](https://github.com/zuckung/plugin-archive/blob/main/res/mds/story.md) (1) | [Weapons](https://github.com/zuckung/plugin-archive/blob/main/res/mds/weapons.md) (0) | [Uncategorized](https://github.com/zuckung/plugin-archive/blob/main/res/mds/uncategorized.md) (0)<br>

---

## Cheats

<p>2 plugins in this category.<p>


 

---

### automata.destruction.0percent
<img src='../../Working/automata.destruction.0percent/icon.png' height='100'></img><br>


[automata.destruction.0percent.zip](https://github.com/zuckung/plugin-archive/releases/download/Latest/automata.destruction.0percent.zip) | 44.09 kb | 2024-10-16 | [view files](https://github.com/zuckung/plugin-archive/tree/main/Working/automata.destruction.0percent/) <br>
Author: zuckung | Category: Cheats <br>
[https://github.com/zuckung/endless-sky-plugins](https://github.com/zuckung/endless-sky-plugins) (last commit 2024-06-07) <br>

>Modifies the self destruction chance of Sestor and Mereti ships to a value of 0.0 (0%). See the readme for details.

<details>
<summary>:blue_book: Plugin readme</summary>
<blockquote>### automata.destruction.0percent
<br>
<br>
Modifies the self destruction chance of Sestor and Mereti ships to a value of 0.0 (0%).<br>
<br>
Sestor 349/109/78/71/53/27/14 and Mereti 512/256/128/64/32/16/8 ships have a self destruction value of 0.0 (0%) now.<br>
You can easily change the values in automata.txt for each ship ('"self destruct" .0') to a value of your choice. I.e. 0.12 is 23%, 0.3 is 51%, 0.5 is 75%. Its calculated twice, first the chance for self destruction on boarding(i.e. 0.3) is 30%, then of the remaining 70% again 30% chance for self destruction on capturing. That makes 30% + 21% = 51% overall chance for self destruction on a capturing try.<br>
<br>
<br>
Changelog:<br>
<br>
2024-06-07<br>
text corrections (thx to TheGiraffe3)<br>
<br>
2023-10-17<br>
added plugin.txt<br>
<br>
2023-09-07<br>
changed icon<br>
changed about.txt<br>
changed readme<br>









</blockquote>
</details>

Status: tested with 0.10.2 <br>
Daily update check: <img src='../img/check.png' width='15' ></img><br>


---

### captureable.person.ships
<img src='../../Working/captureable.person.ships/icon.png' height='100'></img><br>


[captureable.person.ships.zip](https://github.com/zuckung/plugin-archive/releases/download/Latest/captureable.person.ships.zip) | 138.87 kb | 2024-10-16 | [view files](https://github.com/zuckung/plugin-archive/tree/main/Working/captureable.person.ships/) <br>
Author: zuckung | Category: Cheats <br>
[https://github.com/zuckung/endless-sky-plugins](https://github.com/zuckung/endless-sky-plugins) (last commit 2024-10-08) <br>

>Makes person ships capturable. See the readme for details.
>

<details>
<summary>:blue_book: Plugin readme</summary>
<blockquote>### capturable.person.ships
<br>
<br>
Makes person ships captureable.<br> 
<br>
<br>
Well, technically this plugin disables the person ships, and creates new ones which are captureable (with changed names to "<name> (disable me)", due to limitations of changing parts of the originals). Also adds all of them to the author government, adjusts some personalities and sets all frequencies to 1000. Changed "Tranquility" to have a weapon, so it doesn't flee. And changed "Zitchas" personality to "decloaked", so it doesn'tflee and regenerate while cloaked.<br>
So attacking one of them makes all your enemies, they all try to disable instead of destroying, and they all have the same spawn chance which is in average within 10 minutes.<br>
<br>
At Earth's job board you can find a repeatable job that displays which persons you have already killed, which are alive, and where to find them.<br>
After you've killed them all, you receive a small unique gift.<br>
<br>
I tested this plugin with 10x KIV349, all equipped with Mereti beam weapons, was probably an overkill on most. Boarding "Zitchas"(1000 crew) needed an Echo-Galleon, and I tried it with hand2hand outfits plugin. Maybe it works with nerve gas too.<br>
In cap_persons.txt you find the following line under gamerules: "#	"person spawn period" 2000". If you remove the "#" the spawning speed is increased to one spawn in max a  minute.<br>
<br>
<img src='https://raw.githubusercontent.com/zuckung/endless-sky-plugins/master/screenshots/capturable.person.ships01.jpg' width='400'>
<ul>
<li>"Michael Zahniser" (found everywhere | Kestrel + Finch)</li>
<li>"Cap'n Pester" (found everywhere | Quarg Wardragon)</li>
<li>"Marauding Max" (found everywhere | Marauder Fury)</li>
<li>"Captain Nate" (found everywhere | Vanguard)</li>
<li>"Tranquility" (found everywhere | Lampyrid)</li>
<li>"Power of the People" (found everywhere | Modified Osprey)</li>
<li>"Local God" (found everywhere | Ursa Polaris)</li>
<li>"Subsidurial" (found in uninhabited | Subsidurial)</li>
<li>"Prototype B3-CC4" (found in Ember Waste | Shooting Star)</li>
<li>"Rais Iris XVIII" (found everywhere | Marauder Bactrian)</li>
<li>"Zitchas" (found in Ember Waste | Heron + Peregrine + 4x Petrel + 32x Tern)</li>
<li>"Brick" (found everywhere | 3x Modified Boxwing)</li>
<li>"Gefullte Taubenbrust" (found everywhere | Modified Battleship)</li>
<li>"MasterOfGrey" (found in Hai space | Modified Ladybug)</li>
<li>"Patrol Team" (found everywhere | 6x Waverider)</li>
</ul>
<br>
<br>
Changelog:<br>
<br>
2024-10-08 <br>
proofreading and minor text changes (Vemenous-Repentile)<br>
changed status mission to fail on daily<br>
changed subsidural (1 outfit space, keystone and 300 fuel)<br>
<br>
2024-07-14<br>
fixed tranquility weapon space error<br>
removed fines from author government<br>
<br>
2024-06-07<br>
text corrections (thx to TheGiraffe3)<br>
<br>
2024-05-28<br>
adjusted mass and drag to be like in 0.10.7<br>
removed staying personality ftom Tranquility<br>
renamed persons to "name (C)", was "name (Capture me)"<br>
<br>
2024-04-06<br>
set person killed job back to earth only, less annoying when you are done<br>
added a mission with unique reward, after killing all person ships<br>
<br>
2024-03-23<br>
set "no person spawn weight" to 0<br>
added person destroyed check job to every planet with a job board<br>
added a gun to Tranquility so that it stays for fighting<br>
changed Zitchas personality, so that it doesn't cloak<br>
<br>
2024-03-14<br>
bugfixes<br>
added person destroyed check on Earth job board<br>
<br>
2024-02-02<br>
added 0.10.5 person "Patrol Team"<br>
<br>
2023-10-17<br>
added plugin.txt<br>
<br>
2023-09-15<br>
changed gamerules back, because it caused mass spawning<br>
changed some personalities<br>
<br>
2023-09-09<br>
changed all frequencies to 1000<br>
changed gamerules to prevent no spawning chance<br>
<br>
2023-09-08<br>
initial release<br>

</blockquote>
</details>

Status: complete on 0.10.2 <br>
Daily update check: <img src='../img/check.png' width='15' ></img><br>



[back to top](https://github.com/zuckung/plugin-archive/blob/main/res/mds/.md#)


