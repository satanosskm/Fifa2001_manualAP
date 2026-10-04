# FIFA 2001 (PS2) — Archipelago Manual

This Archipelago manual is adapted from an earlier [FIFA 98 (PS1) manual](https://github.com/satanosskm/Fifa98RTWC) I previously created. It has been revised for FIFA 2001 on PlayStation 2.

---

## Compatibility
- **Primary target:** PlayStation 2 (FIFA 2001)
- **Likely compatible:** PC ports with similar feature sets
- **Not tested / may differ:** PlayStation 1, Game Boy Color

## How to play
Play friendly matches using teams allowed by the unlocked leagues, under unlocked settings.

You start every run with a few things already unlocked: one random league, one random time, one random weather, one random stadium, one random gamespeed, and the Amateur difficulty. Everything else has to be found in the multiworld.

## Checks
- **Goals:** 1 check per cumulative goal, up to the number of goals you chose in the options
- **Leagues:** 1 check per league defeated (19 leagues)
- **Settings:** 1 check per unlocked setting item (stadiums, weathers, difficulties, time, gamespeeds)

Goals unlock in blocks of 10: the first 10 goals need nothing, and each new block of 10 goals costs 5 more medals. Scoring is easy at first, and the last goals of a run are the expensive ones.

## Items
- Medals: as many as there are goals (**50** by default)
- Leagues: **19**
- Weathers: **2**
- Stadiums: **5**
- Time (day/night): **2**
- Difficulties: **3**
- Gamespeeds: **4**

## Goal
- **Main objective:** obtain the required number of medals out of the total. By default: **40 medals** out of 50.

## Options

Two options let you shape the run. They are in English, in the FIFA 2001 player options of your yaml.

*Goals and Medals Count*

How many goals and medals the playthrough contains, from **10** to **100**, **50** by default.
Goals above that number (and their checks) are removed from the run, and the number of medals matches it. This is the option I wanted from the start: it is now in the game.
The minimum is 10 and not 1, because goals are unlocked in blocks of 10 and below that every goal would be free.

*Victory Percentage*

The percentage of the medals you need to reach the Victory check, from **10 %** to **100 %**, **80 %** by default.
The result is rounded up. A few examples:

| Goals and Medals Count | Victory Percentage | Medals needed |
| --- | --- | --- |
| 50 | 80 % | 40 |
| 50 | 100 % | 50 |
| 30 | 50 % | 15 |
| 25 | 25 % | 7 |
| 10 | 10 % | 1 |

The minimum is always 1 medal, so a run can never be won before you score anything.

## Install

1. Download the file `manual_fifa2001_satanos.apworld` (the latest one is on the Releases page of this repository).
2. Put it in the `custom_worlds` folder of your Archipelago installation, for example `Archipelago/custom_worlds/`. Create the folder if you do not have it yet.
3. Restart the Archipelago launcher. The game now appears in the list of games under the name `Manual_Fifa2001_Satanos`.
4. Create your multiworld, pick the game for your player, set the two options above if you want something other than the defaults, and generate.
5. Download the patch file you get (it ends in `.apmanual`).
6. Open the Manual client from the Archipelago launcher, load that patch file, and connect to the server.
7. Play, and check your locations off in the client as you go.

There is nothing else to install: no ROM, no patch tool, no extra software. If you have never used a Manual game before, the general guide is here: https://github.com/ManualForArchipelago/Manual

## Notes

- Gamespeeds are included in this version (added since the FIFA 98 manual).
- The option to customize the number of medals/goals is now in the game, together with the victory percentage.

---

## Version française

# FIFA 2001 (PS2) — Archipelago Manual

Ce manuel Archipelago est adapté d'un [manuel FIFA 98 (PS1)](https://github.com/satanosskm/Fifa98RTWC) que j'avais créé auparavant. Il a été revu pour FIFA 2001 sur PlayStation 2.

---

## Compatibilité
- **Cible principale :** PlayStation 2 (FIFA 2001)
- **Probablement compatible :** les versions PC aux fonctionnalités proches
- **Non testé / peut différer :** PlayStation 1, Game Boy Color

## Comment jouer
Faites des matchs amicaux avec des équipes autorisées par les championnats débloqués, dans les conditions débloquées.

Au début de chaque partie, vous avez déjà quelques déblocages : un championnat au hasard, un moment de la journée au hasard, une météo au hasard, un stade au hasard, une vitesse de jeu au hasard, et la difficulté Amateur. Tout le reste est à trouver dans le multiworld.

## Checks
- **Buts :** 1 check par but cumulé, jusqu'au nombre de buts choisi dans les options
- **Championnats :** 1 check par championnat battu (19 championnats)
- **Conditions :** 1 check par item de condition débloqué (stades, météos, difficultés, moment de la journée, vitesses de jeu)

Les buts se débloquent par paliers de 10 : les 10 premiers buts ne demandent rien, et chaque nouveau palier de 10 buts coûte 5 médailles de plus. Marquer est donc facile au début, et les derniers buts d'une partie sont les plus coûteux.

## Items
- Médailles : autant que de buts (**50** par défaut)
- Championnats : **19**
- Météos : **2**
- Stades : **5**
- Moment de la journée (jour/nuit) : **2**
- Difficultés : **3**
- Vitesses de jeu : **4**

## But de la partie
- **Objectif principal :** réunir le nombre de médailles demandé sur le total. Par défaut : **40 médailles** sur 50.

## Options

Deux options permettent de régler la partie. Elles sont en anglais, dans les options du joueur FIFA 2001 de votre yaml.

*Goals and Medals Count*

Le nombre de buts et de médailles de la partie, de **10** à **100**, **50** par défaut.
Les buts au-delà de ce nombre (et leurs checks) sont retirés de la partie, et le nombre de médailles suit. C'est l'option que je réclamais depuis le début : elle est maintenant dans le jeu.
Le minimum est 10 et pas 1, parce que les buts se débloquent par paliers de 10 : en dessous, tous les buts seraient gratuits.

*Victory Percentage*

Le pourcentage des médailles qu'il faut obtenir pour débloquer le check de victoire, de **10 %** à **100 %**, **80 %** par défaut.
Le résultat est arrondi au supérieur. Quelques exemples :

| Goals and Medals Count | Victory Percentage | Médailles nécessaires |
| --- | --- | --- |
| 50 | 80 % | 40 |
| 50 | 100 % | 50 |
| 30 | 50 % | 15 |
| 25 | 25 % | 7 |
| 10 | 10 % | 1 |

Le minimum est toujours de 1 médaille : une partie ne peut donc jamais être gagnée avant d'avoir marqué.

## Installation

1. Téléchargez le fichier `manual_fifa2001_satanos.apworld` (le plus récent est sur la page Releases de ce dépôt).
2. Placez-le dans le dossier `custom_worlds` de votre installation Archipelago, par exemple `Archipelago/custom_worlds/`. Créez le dossier si vous ne l'avez pas encore.
3. Relancez le launcher Archipelago. Le jeu apparaît alors dans la liste des jeux sous le nom `Manual_Fifa2001_Satanos`.
4. Créez votre multiworld, choisissez le jeu pour votre joueur, réglez les deux options ci-dessus si vous voulez autre chose que les valeurs par défaut, et générez.
5. Téléchargez le fichier de patch obtenu (il se termine par `.apmanual`).
6. Ouvrez le client Manual depuis le launcher Archipelago, chargez ce fichier de patch, et connectez-vous au serveur.
7. Jouez, et cochez vos checks dans le client au fur et à mesure.

Il n'y a rien d'autre à installer : pas de ROM, pas d'outil de patch, pas de logiciel supplémentaire. Si vous n'avez jamais utilisé un jeu Manual, le guide général est ici : https://github.com/ManualForArchipelago/Manual

## Notes

- Les vitesses de jeu sont incluses dans cette version (ajoutées depuis le manuel FIFA 98).
- L'option pour personnaliser le nombre de médailles et de buts est maintenant dans le jeu, avec le pourcentage de victoire.
