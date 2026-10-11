# Brick Breaker

A browser brick-breaker game with **455 levels**. Open `index.html` in any browser to play — no install or build step.

The board is tall (480 × 720), leaving plenty of open space between the bricks and your paddle so you have time to react, and it scales to fill your screen. The final level, 455, gets a double-width paddle to make it a little easier.

Levels 1–10 are a warm-up. **Level 11 starts Hard mode**: the ball jumps to 25% faster, the paddle shrinks by 20%, bricks get two extra hits (up to 7), unbreakable bricks double, power-ups drop half as often, and the wall starts falling right away. Bosses get 50% more health and bomb faster.

Every level is harder than the one before it:

- the ball gets faster (330 → 1128 px/s) and the paddle gets smaller (135 → 41 px)
- bricks take more hits to break (up to 7); their colour shifts from coral to violet the tougher they are, and they crack as you damage them
- dark riveted iron bricks appear from level 6 and can't be broken
- from level 11 the whole wall creeps down toward you, faster each level, and costs a life if it reaches the glowing red line
- power-ups get rarer

**Boss fights** every 25 levels (25, 50, 75 … 450): a giant brick with eyes that slides around and drops bombs. Don't let a bomb touch your paddle. The first boss takes 45 hits; each one after takes 9 more (up to 198), moves faster and bombs more often. Below a third of its health it gets angry and speeds up.

The look is gritty neon: a grainy dark backdrop with soft colour glows, rough chipped bricks, a glowing paddle and ball with a light trail, tumbling debris, and a dotted aiming guide that sweeps back and forth before each launch — fire when it points where you want the ball to go. It renders sharply on high-resolution screens.

Your highest level is saved in the browser, so you can continue where you left off.

**Jump to any level:** add `#level-` and a number to the end of the page address, for example `…/allcancel.coma/#level-455`. Play then starts on that level, and every level up to it is unlocked in the level select.

**Level select:** press **Choose level** on the start or game-over screen to see all 455 levels in groups of 25, with each group's boss level marked. Any level up to your highest is unlocked and can be replayed. Beating a level earns stars, kept at your best: ★★★ for losing no lives on it, ★★ for losing one, ★ otherwise. The header shows how many levels you've unlocked and completed, and your total stars.

**Controls:** move with the mouse, touch, or ← → / A D · launch with click, tap, or Space · pause with P · mute with M or the speaker button.

**Sound:** every sound is synthesised live in the browser (no audio files): paddle and wall bounces, brick hits and breaks (pitch rises with brick toughness), clinks off steel, power-up jingles, a fiery whoosh for the fireball, boss hits, bomb drops and explosions, the creeping wall's rumble, and level-up, game-over and victory tunes. Sound starts after your first click or key press, and the mute setting is remembered.

**Power-ups:** W wide paddle · M multi-ball · S slow ball · F fireball · ♥ extra life

**Fireball (F):** for 8 seconds the ball bursts into flame and smashes straight through bricks in one hit, however tough, without bouncing. Unbreakable bricks still stop it, and against a boss each hit counts triple. It flickers just before it runs out. A fireball is guaranteed to drop at least once every 20 broken bricks (or every 10 boss hits), so you'll see it on every level. Catch the orange F with your paddle to use it.
