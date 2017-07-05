# The Basics

This section explains the basic Doomsday piles that attempt to end the game directly with a lethal Tendrils of Agony. 
Fortunately, these piles will also be the piles that you will execute most frequently and likely win most of your 
games with.

However, there will be times where you will build piles that win with Laboratory Maniac, or build up a higher storm 
count with a Time Spiral or double-Doomsday pile, or build a pile that plays around Pyroblast on one of your draw 
spells, or even optimize for the highest probability of being successful against a Surgical Extraction in your 
opponent's hand.

Before this becomes too intimidating, let's first consider the most 
simple Doomsday piles. And since this is the starting point for reading 
about Doomsday piles in general, we will first explain a bit about the notation 
that we use when writing down piles. 

## Notation

| Shorthand | Cardname |
| --------- | ---- |
| TW | Three Wishes |
| AoI | Act on Impulse |
| IU | Ideas Unbound |
| LED | Lion's Eye Diamond |
| GP | Gitaxian Probe |
| BW | Burning Wish |
| ToA | Tendrils of Agony |
| LM | Laboratory Maniac |
| BS | Brainstorm |
| P | Ponder |
| LP | Lotus Petal |
| DD | Doomsday |
| DR | Dark Ritual |
| IC | Infernal Contract |
| CB | Conjurer's Bauble |

Mana costs are represented as follows:  
W White - U Blue - B Black - R Red - G Green  
1 one generic mana  
BBB means three black mana  
1UU means two blue mana and one generic mana

Consider the following example of a Doomsday pile in this notation:
```
-> IU, LED, GP, LED, BW(ToA) BBB+1UU (6) 8 Storm
```
This means that IU is the top card and BW is the bottom card. BBB+1UU 
represents the mana cost, (6) is the converted mana cost. 8 Storm 
represents the amount of storm that executing this pile will generate, 
this includes the Doomsday you've cast to create this pile as well as 
the Tendrils of Agony (including the non-copy original spell) at the end 
of the pile. The original Tendrils is included for simplicity, because 
we simply count to ten if we want to cause 20 lifeloss. I will 
frequently leave out the wishtarget for BW at the end of the pile, 
because it is obvious that it is used for Tendrils of Agony.

## Basic Doomsday Piles

The Doomsday piles that we will explain here are all based on using either
Ideas Unbound or Three Wishes as the big draw spell. We will first consider the single 
cantrip piles, followed by the double cantrip piles.

### Single cantrip piles

There are basically two variants to this pile. You either have a spell 
that draws a single card in hand ready to cast, or an 
Conjurer's Bauble in play. For the moment, the difference does not 
really matter and we'll just assume that you have a GP in hand.

*Ideas Unbound*

GP in hand:
1. cast Doomsday build: -> IU, LED, LED, GP, BW(ToA)
2. cast GP, draw IU
3. cast IU, draw LED, LED, GP
4. cast LED
5. cast LED
6. cast GP, sacrifice both in response LEDs for RRR+BBB, draw BW
7. cast BW, get ToA from sideboard
8. cast ToA

This pile has cost you BBB+UU and 4 life and results in 8 storm, that 
is 16 lifeloss. Note that UU is often paid for by a Lion's Eye 
Diamond. With a Dark Ritual and a Lion's Eye Diamond preceding the 
Doomsday you already generate enough storm to cause 20 lifeloss. If you 
are low on life you'll need more mana to cast GP for mana instead of life.

*Three Wishes*

GP in hand:
1. cast Doomsday build: -> TW, LED, LED, GP, BW(ToA)
2. cast GP, draw TW
3. cast TW, exile LED, LED, GP
4. cast LED, sacrifice it for RRR
5. cast LED, sacrifice if for BBB
6. cast GP, draw BW
7. cast BW, get ToA from sideboard
8. cast ToA

This pile has cost you BBB+1UU and 4 life and results in 8 storm, that 
is 16 lifeloss. Like with Ideas Unbound, the mana cost for the draw spell
1UU is often paid for by a Lion's Eye 
Diamond. The most important difference is that Three Wishes does not
actually draw but exiles the cards, which means that Lion's Eye Diamond's
activation cost will not affect your ability to cast the cards 'drawn'
with Three Wishes.
If you are low on life can also build -> TW, LED, LED, BW, X and directly
'draw' Burning Wish with Three Wishes, this will produce once less storm.

### Double cantrip piles

*Ideas Unbound*

2x GP in hand:
1. cast Doomsday build: -> LED, IU, LP, LED, BW(ToA)
2. cast GP, draw LED
3. cast LED, sacrifice LED for UUU
4. cast GP, draw IU
5. cast IU, draw LP, LED, BW
6. cast LP, crack for R
7. cast LED
8. hold priority, cast BW, sacrifice LED for BBB, wish for ToA
9. cast ToA

This pile has cost only BBB+1 and 4 life to execute and results in 9 storm, that 
is 18 lifeloss. This pile is quite efficient when it comes to mana.
We use the additional cantrip to draw a Lion's Eye Diamond before executing the rest of the pile
and use that Lion's Eye Diamond to pay for much of the rest of the pile.
We basically turn our additional Gitaxian Probe into a Lion's Eye Diamond with Doomsday.
One difficulty in this is that Ideas Unbound actually draws Burning Wish before we can
use the second Lion's Eye Diamond in the pile to pay for the red mana. Therefore,
one of the Lion's Eye Diamonds in the pile is replaced with a Lotus Petal, which
together with one blue mana left from the first Lion's Eye Diamond pays for the Burning Wish. 
The second Lion's Eye Diamond is sacrificed for black mana and pays for all but 1 mana of Tendrils of Agony.

*Three Wishes*

2x GP in hand:
1. cast Doomsday build: -> LED, TW, LED, LED, BW
2. cast GP, draw LED
3. cast LED
4. hold priority, cast GP, sacrifice LED for UUU, pass priority, draw TW
5. cast TW, exile LED, LED, BW(ToA)
6. cast LED, sacrifice LED for RRR
7. cast LED, sacrifice LED for BBB
8. cast BW, wish for ToA
9. cast ToA

This pile is very efficient at BBB and 4 life for 9 storm.
The key idea is that strictly speaking, we only needed TW, LED, LED, BW in our single cantrip pile. Meaning
that if we shift this 4 card pile to the bottom, we can put any card on top. In this case we put a Lion's 
Eye Diamond on top, which we draw with Gitaxian Probe. The Lion's Eye Diamond then pays for the Three Wishes,
which exiles the other two LEDs and the Burning Wish we need to produce all the mana we need and cast Tendrils.


## Variations

That's it for the basic and most common piles that end with Tendrils of Agony. There are many variations of each pile 
and it doesn't really make sense to list them all. In each of the above piles you may replace Gitaxian Probe with a 
Ponder, or simply use blue mana to pay for it rather than 2 life.

As for the other piles out there, there are countless piles that use 
Brainstorm to draw some cards and put some other cards back. This 
particular trick allows you to exchange cards in hand with cards that 
you've tutored up with Doomsday. As you can imagine this results in a 
large number of combinations of Brainstorm + some other cards in hand 
that enable different Doomsday piles for different mana costs and storm 
counts.

## Get Started

You now have sufficient information to start practicing! Just take a proven decklist and start goldfishing trying to 
figure out what piles to build and how to execute them. There are several documents available that list Doomsday 
piles which you can use to get to know more piles. These are very important tools when learning to how play the deck. 
See the [DDFT Pile Document](https://github.com/Bennotsi-MTG/ddft-pileDoc/blob/master/README.md).



