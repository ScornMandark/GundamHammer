Hi all! OK, this mecha thing just won't let me go (shocker). It's based on Warfleets FTL, but hopefully feels a little more stompy. Please give it a gander, I'd really like some feedback to improve on it. If anyone likes it, I claim no copyright whatsoever, feel free to use it as you like (subject to the existing license usage of Warfleets FTL, of course).

HEX, of course, stands for whatever you like.  Heavy Endosteel eXterminators, Huge Electric eXtension, Hammer Every Xeno, take it for what you will :) 

Mecha HEX Core Rules: https://git.io/JilaI

[u][b]Replies:[/b][/u]

[b]Greedo:[/b]
Hey Scornmandark!
Love applying the OPR treatment to all the games I used to play in the 90s :) Battletech included. Awesome draft rules. So I'm bringing any feedback/suggestions with love.

For ease of reading, I would just rename Toughness as straight up "Armor" = "Arm" or even "Def", and change Evade to "2Hit".

The other thing, and this might make things too complex, is the neat thing about Battletech, and less generic combat...
These rules as written would allow a group to play a large battle of lots of mechs fighting all at once, since your mech is pretty much fine, damaged, or dead, which is cool. The detail of each mech is much less, so that you can field far more.

But if I'm commanding maybe a single platoon of 1-3 mechs, having more detail to the mech would make resource management more of a part of the game. My random suggestions would be 1) Different weapon systems, 2) damage location, and 3) heat management.

1) Different Weapon Systems: Since the mech is so large, it can have long range weapons and close range weapons. I think this is already handled and allows some fun customization of the mechs. I think this is handled in the upgrades.

2) Damage Locations: This makes a big difference as to where weapons are located, but also movement. i.e. If you blow the opponent's leg off, they can't move/turn anymore but can still fight in the direction they are facing. If you knock out their left arm, their left arm weapon is now gone, but they still have a right arm to shoot with. Each mech could have 4 damage locations (arms, legs, chest), and each has damage points associated with it... Trying to think of how to make this simpler but still track a more nuanced view of "damage".

3) Heat was an interesting aspect to Battletech. I just thought it was neat to blast away with all a bunch of heat generating lasers, but then you overheat and have to sit there to cool down, and it's a thing a true "mechwarrior" has to worry about. This might be the most complex aspect, and therefore we might want to abstract away.

What do you think? Does this add too much complexity?
Either way, great work!

[b]ScornMandark:[/b]
Hi!  Thanks for the detailed feedback, sorry for the late reply.  I keep expecting to get an email notification or something, but apparently not.

I'm trying to stick to the warfleets nomenclature at the moment - there's definitely some confusion possible if you start using armor when there's extra armor upgrades, but I definitely see your point.  I'll have to think about it some more.

I like your idea of skirmish type rules!  Maybe an advanced rules section :D

1) Since the weapons are currently somewhat grouped already, this is probably fine.  You can restrict certain mecha to different upgrades in different locations if you like, it's up to you.

2)  This is an interesting idea - there's value in the defender controlling what gets damaged to an extent - you don't want your large lasers getting popped before your extra armor upgrades :P  Still, it's a fun idea.  Maybe something like:

Skirmish Damage Allocation:
For every hit that lands on a mecha (i.e. not evaded or blocked), the attacker rolls a d6 for which servo takes that hit.  1-2 Left Arm, 3-4 Torso, 5-6 Right Arm.  The defender then assigns the damage from that hit to the upgrades in that location as per normal, and must assign all subsequent damage in a given servo to a damaged upgrade in that servo until that upgrade is destroyed.  Once all the upgrades in an arm servo are disabled, further damage to that servo must be assigned to the torso instead.  Once all the upgrades in the torso are disabled, further damage to that servo must be assigned to either arm with remaining upgrades (defender's choice).  Additionally, if all the upgrades in the torso are disabled, then the mecha may only take the Hold action and may not pivot.

3) Heat management was definitely one of the things I struggled with for a while, and which is why I sort of punted to the Overheat tag lol  I think there's still a way to make it work:

Skirmish Heat Management:
Every weapon generates 1 point of heat per upgrade requirement when used in an attack.  Weapons with Overheat count as having double their upgrade requirements (overriding the standard Overheat effect).
Each unit can dissipate 1 point of heat per TUS (Torso Upgrade Slots for mecha, Total Upgrade Slots otherwise).  Each Heat Sink upgrade can additionally dissipate 2 points of heat.  Desert and other Hot maps count the unit's TUS as halved, rounding up.  Ice and other Cold maps count the unit's TUS as 1.5x, rounding up.  Ending your movement in water counts the unit's TUS as 1.5x, rounding up.
At the end of every unit's activation, add up the total generated heat and add it to any remaining heat from the previous round.  Subtract from that all of the unit's dissipation, giving you a new heat total (minimum 0). 
If the resulting heat is more than the unit's TUS, then unit temporarily shuts down.  It counts as being an Easy Target, and may only take the Hold action the next time it activates without pivoting.
If the resulting heat is more than 2x the unit's TUS, then in addition to shut down it takes 1 damage for every point of heat over 2x the unit's TUS.

It sounds a little complex, but I think it'll be pretty straightforward.  +1/+2 heat per weapon upgrade that fired depending on if it's Overheat tagged, + any remaining heat from the previous activation.  -1 Heat per TUS, -2 per heat sink, modified by environment, minimum 0.  If the remaining heat is over TUS, shutdown.  If 2x over TUS, heat damage!

What do you think?  This would fall into the "Other Ways to Play" section, but I like it!

[b]Greedo:[/b]
Scornmandark, this is awesome!

Yeah, I think you could make 2 sets of FTL rules, 1 for large fleets (and modified for the mech rules), and another one, for a single squadron of ships/mechs. Much like Grimdark Future, and Grimdark Future Firefight.

I could definitely have a standard "mech blueprint" that like you said moves excess damage from arm to torso etc. (much like Battletech, or even Warjacks in Warmachine). And we just have small, medium, and heavy mechs with different damage amounts in each limb. The weapon gets lost when the last damage point in that limb is destroyed, but the weapons themselves don't actually have any damage points. Just to keep it simpler. And each position has a maximum number of "spaces" to assign upgrades. Each upgrade either takes up 1 space, or might have to be assigned a certain "size", so really big weapons take up a lot of room.

That will prevent people putting all their weapons in the torso :) Can't put weapons in the legs.

To encourage putting weapons in the arms, you could have "fire arcs" on the left, right, and forward, although that might get too complex.

Heat is very complex, so will noodle on your ideas, before I comment :)

[b]ScornMandark:[/b]
There's already a selection of mech sizes, with different numbers of upgrade slots. And, since it's still FTL based, upgrade slots = hit points. The different weapon upgrades take different numbers of slots, so that's already ready already! :)

Here's what I'm thinking as a heat example:

Let's take a Light Mech - 2 Torso Upgrade Slots, 1 Upgrade Slot in each arm. It has 1 Medium Laser upgrade in each arm, an Extra Armor and a Heat Sink in the torso.
It takes some shots at a nearby target, firing both lasers. Since each is 1 Upgrade Slot and also Overheat, each one generates 2 heat, for a total of +4 Heat that action.
It's 2 Torso Upgrade Slots cancels 2, and the heat sink cancels 2 more. Net Heat Gain of 0.

Now a Heavy Mech - 4 Torso Upgrade Slots, 3 in each arm. It carries a Heavy Laser (2 slots, Overheat) and Medium Laser (1 slot, Overheat) in each arm; 2 Medium Missiles (1 slot each) and 2 Heat Sinks in the torso.
Alpha Strike! Firing everything it's got, it immediately generates 12 heat from the lasers alone (6 upgrade slots x2 for Overheat), plus 2 more from the missiles. +14 heat!
It's 4 Torso Upgrade Slots cancel 4, the heat sinks cancels 4 more. That leaves 6 heat remaining. Since that's higher than the Torso Upgrade Slots, the Mech immediately shuts down!
On it's next activation, it will cancel 8 more, so it can only fire a few guns unless it wants to shut down again.

I feel like it's one of those interactions that gets wordy on the page, but probably pretty easy once you do it 2 or 3 times. I could be wrong, though.

I just updated my Warfleets-based Mecha game again, and I'd love some feedback on 1.2. I overhauled the movement, ramming, and jump rules, changed how many vehicles you can take, and a few other tweaks. I left in vehicles and structures for now, but we'll see how it goes. Please give it a gander! No Skirmish rules yet, still trying to hammer down the core rules.

[b]badskeelz:[/b]
Hello! First off, thank you for the work you've done in creating HEX. There's a couple of BattleTech fans in my gaming group, but none of us have the time or patience to wade through and learn those old rulebooks. An OPR-ified mech game immediately garnered interest. We played our first two games of it this morning - my friend's relatively balanced lance of three lights and a medium, versus my own SLAMHOG lance of an assault, a medium, and two vehicles. The first game was a decisive victory for the balanced lance (not helped by the SLAMHOG assault having no guns with a range of over 3 hexes). The second game I retooled my assault into a gun platform and brought two heavy vehicles with heavy lasers, played them better, and got a draw out of it. SLAMHOG is a ponderous beast.

My lance was pretty simplistic and heavy, so I don't have a whole lot of insight in to the more complicated rules. I did find the Heavy Vehicles to be capable of earning their points back with careful deployment and target selection, but also very fragile. I'm definitely the kind of player who would bring ten Heavy Vehicles in a 200pt game if I was allowed, so I think the "one vehicle per mecha" and "vehicles cannot capture objective" rules to be pretty close to where they need to be.


My friend, being a more seasoned Mechwarrior with a much more balanced and intricate lance, has his own observations. I have bolded what I think were the salient points. On the subject of jumping:



imo, you should be able to turn for free while jumping. it was a thing in mechwarrior

RAW, that is not in Mecha Hex

RAW, turning costs the same points while jumping, as it does on the ground

you already have incentive to not jump all the time if you don't need to, from the -1 to hit

it'd help make light mechs a little more dangerous vs big slows

as you can jump over their heads, turn in mid air, and shoot in the back

again a tactic from mechwarrior

...

i think the section on Jumping could be rewritten, because i don't quite understand how it works

and i'm even looking at an old battletech rulebook


"as [the mech] lands, the player can face the 'Mech in any direction desired, at no extra cost"

That's from BattleTech, for jumping

"A jumping 'Mech also ignores facing: it can jump in any direction for the same MP cost, regardless of its initial facing, and when it lands it chooses any facing desired."

Again, BattleTech.

i would like clarification on 1) Jumping and facing 2) and also if you must only Jump in straight lines, or if you can do twisty moves


He also questioned the utility of having multiple JumpJet upgrades:

in Btech/mechwarrior, what determines whether you can do that kind of move

is how many jumpjets you have

with lots of jumpjets and good piloting you can change direction mid-air

i've done it in MW:O

but you're sacrificing armor, ammunition, guns, something

for the jumpjets

in Mecha:Hex you are, but it's binary

either you have jump jets or you don't

On the subject of Mech height for line-of-sight:

it'd be good to drop a blurb clarifying how tall mechs are.

in Battletech, I'm reading, mechs are Level 2 in height

so if Level 1 terrain intervenes between Target and Attacker, the Attacker still has LOS but target has cover

(in our game*, you could have still shot the panther)

it could literally be a 1 sentence blurb

"If you are using leveled terrain, consider mechs to be 2 levels tall for purposes of LOS."

The game he is referencing was our second one: his Panther, the lone survivor of his lance, picked up one of the two objectives and ran behind a level 1 hill. SLAMHOG was unable to engage and destroy the Panther due to a combination of range and line-of-sight (as I assumed a level one hill blocked it), ending the game in a draw.

So to recap, he has questions about Jumping and Facing; how Jumping itself works (whether it must be straight lines, or if you can hop around flanks); the binary nature of the JumpJets upgrade; Mech height clarification for purposes of line of sight.

We definitely had fun, and I think I'll work with him to homebrew some expanded jumping rules. Looking forward to playing again.

[b]ScornMandark:[/b]
Thanks for taking the time to play test and give feedback!

I like the idea of facing any direction during and after a jump, and the wording could probably be cleared up.  I'm not as about thrust vectoring jumps - it starts getting a little beyond fast and simple.  I don't want jump jets to be an auto include, some units don't have them for a reason.

That's a good idea about calling out heights, too.  Mecha are level 2 unless otherwise noted, vehicles level 1, etc.

Here's my suggested Jump overhaul wording, did this help clear it up?

Jump: Models that can Jump may choose to Jump during any movement except Hold. The model may ignore the Overlapping rule, may turn as many facings as they choose before and after the move for zero speed points, and aren't affected by terrain they pass over. All other rules for their move action still apply. Models that Jump may move up as many levels as they have speed points for during a move, and after the move they must Fall to the level of the hex they entered last. (Models that can Jump only take a maximum of 1 damage from
Falling.) Until its next activation, the model gains Cover, Reinforced Frame, Reinforced Hydraulics, and all weapons gain Indirect.

OK, with your suggestions combined, I am CAPTAIN.... wait, no. Mecha:HEX v1.3, feedback plz!

I need to build out the factions for my Mecha Hex game. What do you think about these? Any tropes I missed?

Grimdark: Empire Titans, Orky fighta's, Havoc Behemoths, Xenos Constructs

Gritty Robots: Establishment, Rebellion, Ostensibly Neutral

Super Robots: Defenders, Combiners, and Transformers

Kaiju: Monsters, Xenos, Hordes

FightTech: Inner Sphere Soldiers, Clan Crusaders, Mercenary Bands

That covers most of the ideas I can think of - anything I'm obviously missing?

My plan is to introduce supermassive entries for most of these, to accommodate proper Kaiju vs Super Robot fights. Different factions will have different army bonuses, like Warfleets. Plus, structure destruction is already baked in! Open for suggestions 😁


[b]gravitydog:[/b]
REF: Experimental Armor: When taking a point
of damage roll one die, on a result of 5+ the
damage is ignored. 2 upgrade slots.

Is this meant to work on any damage taken like regeneration? or is it just 1 damage point per round or attack? Should it be listed as "limit 1"?

Did a play through solo. good fun.

[b]jayb0t:[/b]
I really like your rules and want to try them. I have a question regarding the rules for Heat Sinks though. If you have 1 Heat Sink you cancel up to 3 Overheat results per turn. However, even 1 or 2 Overheat result will destroy the heat sink at the end of the activation. Is that correct?

What is the interaction with more Heat Sinks and Overheating, for example 2 Heat Sinks and 4 Overheating results? I read the rules as if all 4 Overheating results are canceled, but only 1 Heat Sink is destroyed.

Thank you for elaborating!

[b]gravitydog:[/b]
For the heat sink rule interpreted cancel 3 overheat results as canceling out the heatsink destroyed also. so with one heatsink it would take 4 overheats to loose a heatsink.

[b]ScornMandark:[/b]
Hi all! Sorry for the lack of reply, I never get notified when there's a reply on this thread.

For experimental armor, yes, I intended it to be like regeneration, so roll for each wound.

For heat sinks, I'd intended that each one cancels up to three overheat results. If there are any uncanceled overheats after taking in to account all your heat sinks, then you take a damage and break a heat sink. Do you run hot for more damage? Or lower the damage output for heat protection?

I think it's fantastic you are having fun with it! My GundamHammer indexes are almost done, so I'm looking forward to faction books next.

[b]grumpymuppet:[/b]
I'm looking to play this tonight!

I'm a mechwarrior fan, but we'll be using 40k dreads as models.

I'm thinking we'll use 1 hex = 3" for movement and 1hex = 4" for weapon ranges, to suit the scale.


It seems that the location of upgrades is irrelevant - am I correct?

[b]ScornMandark:[/b]
Great!  How'd it go?  Sorry I didn't reply sooner.  That sounds like a pretty epic battle, and that sounds like a good upscaling.  In general yes - the location of any given upgrade isn't critical.  Just once all upgrades on a unit are blown up its destroyed.  I've got some sort of competitive rules I'm working on that make it a little more important, like lose the torso and you're out, but for the base rules it's not too important.

[b]talarius:[/b]
Mecha HEX gets mainstream coverage… www.youtube.com/watch?v=cCDHbi4-pbY

[b]menacing:[/b]
300 views in a month is mainstream?

[b]talarius:[/b]
Well, it’s all relative. 300 people that had likely not heard of Mecha HEX before that episode, but yeah, point taken.

[b]yungairfryer:[/b]
I really, REALLY love what you've made here. Your game is quite possibly even easier to understand and play than Grimdark Future: Firefight; and yet you really packed a lot into that one page!
That being said, as a lifelong MechWarrior fan who plays MechWarrior: Online almost daily, I have a LOT of ideas for ways to add depth to your game and help it better recreate the feel of BattleTech, without making it any more complicated or hard to understand. I'll divide the various ideas I have into separate sections.

Idea 1: Pinpoint Damage

In MW, WHERE you deal damage is extremely important. Certain weapons let you deal all of your damage to one specific area, rather than spreading out the damage over the whole mech. Because these weapons are very powerful, they have huge drawbacks to balance them out, like high heat, limited ammo, or slow firing speed.
In your game, I think you can represent this in a simple but effective way, by adding a new Pinpoint Damage rule to certain weapons:

Pinpoint Damage:

Upon a successful hit, the attacker chooses which slot is destroyed.

Ignore the Ammo Box rule. In other words, destroying an enemy's weapon with the Ammo Box rule deals no extra damage.

I would then add the Pinpoint Damage rule to the Particle Cannon, the Rail Gun, and the Light Gatling.
I would also, at the risk of running the perfect simplicity of your linearly scaling weapons system, consider adding a new weapon, with stats something like this, so that medium-range pinpoint brawling becomes a possibility:

Snub Particle Cannon: 6 Hex / Atk 3 / Str 2 / Slot 2
Overheating, Deadly, Pinpoint

Idea 2: More Equipment/Weapons

There are several classic items in MW/BT that are absent in Mecha: HEX. I think the game would be a lot more interesting if they were added in.

Equipment: Targeting Computer / 2 Slots

+1 Hex range for all weapons. You can take multiple T-COMPs, and their effects will stack.

Weapon: TAG Spotting Laser / 6 Hex / Atk 2 / Str 2 / 1 Slot

Upon successfully landing a hit on an opponent, place a small cardboard circle next to them. They are now "Tagged". For as long as they are Tagged, all Missile weapons gain +1 to hit against them, and ignore all terrain penalties. Upon landing a successful hit on them with a missile weapon, remove the TAG marker.
Your Mecha may only equip one TAG Laser, and may only TAG one enemy at a time; if you TAG a second enemy while you already have a TAG on another enemy, remove the TAG from the first enemy.

Enemy Mechas and vehicles can only have one TAG marker on them at a time.

Equipment: Anti-Missile System / 2 Slots

Ammo Box

Missile attacks (except Artillery) on this Mecha or any friendly unit up to 2 Hexes away have -1 to hit. AMS's stack, and can reduce a Missile Weapon's chance to hit to as low as 5+.

[b]ScornMandark:[/b]
Thanks very much!  I do want to preface this with the idea that it's mostly an FTL reskin, and I like a lot of the systems involved.

1)
Part of the reason of allowing the defender to choose the upgrades to get damaged is to more accurately represent the randomness involved in most combat scenarios.  Unless you're taking a called shot with a pretty hefty attack penalty, that sort of targeted damage is represented by a number of high strength deadly shots.  Since further damage must be assigned to a damaged weapon, it already has that kind of effect.

The other part of the reason is to force the defender to start making hard choices.  Let's face it, the first hit always gets assigned to the extra armor (hence the point of taking it), and the first called shot would always bypass said armor lol  To avoid stacks of special rules on top of special rules, I feel like it's appropriate right now to have the defender assign the damage.

Overall, I think pinpoint weapons would really break the balance of the game as it stands and take some of the tactics away from the defender.  

2)
I like the AMS, but probably an upgrade rather than a weapon, so limited to one per model, and any target within 1 hex.

TAG laser also really great, I like it.  It wouldn't do any damage on it's own, but it's a good upgrade.

Not too sure about the T-COMP, I think it might unbalance, especially if it applies to all weapons on the unit.  I'll need to think about that one.