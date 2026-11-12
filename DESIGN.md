# Math Buddy — Design

A cozy island adventure where math is how you help your friends.

## Big idea

- You make a buddy, explore Number Island, help the islanders
- Every problem helps someone: count carrots, share berries, fix a bridge
- Kind, not scary: nobody loses, nobody gets hurt

## Rules we keep

- **No timers.** Thinking slowly is fine
- **No losing.** Wrong answer = try again, and a picture pops up to help
- **Pictures first.** Every problem can be seen, not just read
- **Cheer up, don't fight.** Grumpy creatures become friends
- **Your choices matter.** They change the island and the ending
- **Short.** A round is 3–5 questions

## Math problem styles

Each place teaches one kind of thinking.

| Place | Math | How it looks |
|---|---|---|
| Plus Meadow | Adding, doubles, make 10, hidden number | Dots, ten frame, sticks of 10 |
| Berry Woods | Taking away, how many more, fair sharing | Crossed-out dots, deal berries onto plates |
| Square Garden | Square numbers, rows × columns, funny shapes | Tile grids, split an L shape in two |
| Mystery Peak | Mystery bags (early algebra), patterns | Balance scale, number hops |
| Crystal Cave | Times, turn-arounds, splitting big ones | Dot grids you cut into two easy pieces |
| Lighthouse | Everything mixed | — |

- **Tricks over memorizing**: doubles, make 10, split 7 × 6 into 5 × 6 + 2 × 6
- **Step-by-step problems**: big ones broken into 2–3 small steps
- **Story problems**: use island friends and their stuff
- **Levels 1–3 per place**
  - 4+ right first try → harder next time
  - 2 or fewer → easier next time

## RPG elements

- **Buddy**: name, color, hat, shirt, glasses, extras
- **Calling**: Wizard (Brains), Knight (Power), Explorer (Luck)
- **Stats**
  - Brains → Zaps (make a wrong answer vanish)
  - Power → Super Cheers (cheer twice as much)
  - Luck → bonus shells
- **XP and levels**: right answers give XP; each level = +1 to a stat you pick
- **Shells**: island money; buy clothes at Shelly's shop
- **Gear**: some clothes give stat bonuses
- **Friends who join** (one at a time)
  - Bun — swap a question
  - Pip — extra shells
  - Professor Hoot — extra Zap
  - Echo — one oops still counts
  - Misty — bonus shells after a round
- **Cheer-up challenges**: "boss fights" with a Grumpy meter; each right answer shrinks it
- **Things to collect**: 4 Light Gems, 12 critters, 6 treasures, 6 dig spots, clothes

## World

- **Number Island**: small island, river down the middle, lighthouse out at sea
- **The storm**: knocked out the Lighthouse; its 4 Light Gems flew away
- **Friends**
  - Captain Gull — dock, your guide
  - Shelly — village shop and inn
  - Bun — meadow, lost her carrots
  - Pip — woods, ate Bun's berries
  - Grandma Tess — garden got squashed
  - Professor Hoot — peak, studies mystery bags
  - Bea — beaver, broken bridge
  - Echo — shy bat in the cave
- **Grumpies** (each sits on a gem): Bramble Knot, Weed Wiggler, Wind Sprite, Crystal Golem, Fog Gobble
- **Time of day**: morning → afternoon → evening → night; different critters come out
- **Locked places**
  - Cave needs the bridge (Bea) and the lantern (Hoot)
  - Lighthouse needs all 4 gems

## Story

1. Storm! Lighthouse goes dark
2. Help friends, cheer up grumpies, find 4 gems
3. Sail to the Lighthouse, meet the Fog Gobble
4. Fog was just lonely → you choose what happens

**Choices**

- Pip: share your snack, or help give the berries back
- Garden: sunflowers, roses or pumpkins
- Bridge: bouncy rope or strong stone
- Fog: stay on the island (becomes Misty) or float home

## How it's built

- One file: `index.html` — no build, no server
- Progress saves in the browser, on that device only
- Push to `main` → live at https://brianlow.github.io/math-buddy/ in about a minute

## Ideas for later

- New places: clock tower (time), market (money), pizza shop (fractions)
- Level 4 for kids who zoom ahead
- More to do after the ending
- Critter Book rewards for finding them all
