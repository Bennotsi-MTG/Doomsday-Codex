# Conjurer's Bauble piles

At the time of writing (July 2017) this is still a relatively new card 
to play around with. Histroically Sensei's Divining Top held a place as
a standard 4-of in the deck to act as deck filtering and a 'free saved'
card draw for Doomsday piles. More information on how this was used can 
be found in the <a href="https://github.com/Bennotsi-MTG/Doomsday-Library">Doomsday Library</a>. 

Conjurer's Bauble was identified as the closest equivalent for use in 
Doomsday storm or Laboratory Maniac piles that would allow a free draw
that was also resistant to having to discard as a result of using Lion's
Eye Diamonds. In can be included as a singleton copy to act as a replacement SDT 
element however it has some interesting properties when multiples are 
available in a deck. 

The most basic use of the card is of course simply as a cantrip that costs 1.
It can also be used as a free cantrip if already in play however this does of
course results in less storm being available for use. In any of the common piles
that require a non-specialist cantrip (such as Brainstorm) this can be used 
instead of any others.


## Storing a draw with CB

Let's simply start off by looking at the basic function of Conjurer's 
Bauble as simply a tool to draw cards when using LED.   

Example:
```
GP:
-> IU, CB, GP, LED, LM.                  BBB+UU1 (6)      
```

Here you can see we can use CB to enable a draw card effect to be present
even after we have activated an LED for mana.

This is most applicable when you have Conjurer's Bauble in your deck
alongside an additional cantrip in hand post-Doomsday. You can use
the cantrip to draw into the pile and save the Bauble draw for when
you are deeper into the pile. This is effective, especially when you 
have to start the pile with low mana resources.  

This is also enables things like Double Doomsday piles.

Example:
```
CB in play+GP:
-> IU, LED, LED, BW, BW                  BBB+1UUR (7)         13 Storm
-> IU, LED, GP, LED, BW
```

This has some overlap with what is described in the <a href="https://github.com/Bennotsi-MTG/Doomsday-Codex/blob/master/double-doomsday.md">Double Doomsday section</a>. Just as historically you could with Sensei's 
Divining Top, Conjurer's Bauble may be used save the draw for the 
second pile in the play line.

As can be observed, from the two above examples, it is much more effective
to use CB when using IU as opposed to either TW or AoI (Both of which
can allow the use of LED without needing to discard).     
This is not however the true strength of CB.   


## Using CB to retrieve the 'Finisher'

This is where we start to discuss the real differences of Conjurer's Bauble
and Sensei's Divining Top. We also get to read the rest of the text on
Conjurer's Bauble other than "T, Sacrifice ~: Draw a card."   
Conjurer's Bauble allows you (as a may effect) to target a card in your graveyard
and stack it at the bottom of our deck. Alongside the deck manipulation
a resolved Doomsday provides, this lets us do some nifty tricks.

The first is to ignore the downside of Lion's Eye Diamond.   

Example:
```
CB in play+BW+GP:
-> LED, IU, LED, LED, GP                  BBB+0 (3)         9 Storm

CB in play+ToA+GP:
-> LED, IU, LED, LED, GP                  BBB+0 (3)         8 Storm
```

I know often you can find yourself with a key business spell in hand 
and no Brainstorm to move it with. You could use the GP to draw into
a Brainstorm however that then starts adding costs to the pile. 
As you can see, both piles above cost no mana beyond the initial
BBB for Doomsday. 

The way the piles work is to utilise CB to send the business spell
back from the Graveyard to your hand. In the first example above,
you use the GP to draw into the pile. You then play and activate 
the LED with the BW still in hand. With the mana now floating you 
activate CB sending BW to the bottom of your deck to draw IU.   
You have now created a normal -> IU, LED, LED, GP, BW pile!

We can also use this effect to play our finisher spell multiple times.
Even on a pass-the-turn pile.

Example:
```
ToA+DR+LED:
-> IC, DR, DR, LP, CB                  2B (3)         8+9 Storm
```

In this instance we can play ToA twice. Draw IC for turn. Play DR to play IC.
Play out all your spells resulting in (2BBBBBB) mana being left. Cast ToA with
storm count of 8 (2BB remaining). Then activate CB to return ToA to hand to cast
it again for storm count of 9. This results in 17 copies of ToA being available
across the pile. This example does require some quite specific circumstances
but it does help illustrate tricks you can do with it. Even a low initial storm 
count of 5 for the first copy allows for a total of 11 storm in total. 


## Using CB to extend the pile

You can use the theory of retrieving a card above to help build your pile up.   
Five card decks do have limits even if we get to choose all five cards.   
CB allows you to extend that to a pseudo-six cards.

Example:
```
CB in play+GP:
-> LED, IC, LED, LP, BW                  BBB+1 (4)         8 Storm
```

Normally double cantrip piles into using Infernal Contract/Cruel Bargain/Meditate 
would mean you draw yourself to death however with the CB in use, you can 
use the same trick as with the IU pile. Use the GP to draw into the pile. 
Cast and crack the LED for BBB. You then use the CB to send the LED to the 
bottom of your deck and draw IC. Using BBB you now can draw the rest
of the stack; LED, LP, BW, LED allowing you to storm to victory.


## Using 2 CBs in a loop

This section of discussion is one of the strongest arguments advocating
the use of CB, especially in multiples. The more astute of you may have noticed
one key inefficiency of two  of the piles discussed already.   
I will copy them again here for convenience:

Example:
```
CB in play+BW+GP:
-> LED, IU, LED, LED, GP                  BBB+0 (3)         9 Storm

CB in play+ToA+GP:
-> LED, IU, LED, LED, GP                  BBB+0 (3)         8 Storm
```

If you notice, both result in wasted mana being left over. With the BW example
you are left with U and with the ToA example you are left with U[B/R][B/R] left 
over. Is there a way we can maximise the use of this mana?  
What if we were to swap the GP in the piles with a CB?

Example:
```
CB in play+BW+GP:
-> LED, IU, LED, LED, CB                  BBB+0+X (3+X)      9+X Storm

CB in play+ToA+GP:
-> LED, IU, LED, LED, CB                  BBB+0+X (3+X)      10+X Storm
```

Suddenly the two piles look very different notation wise. Both now have
a variable X value in their respective mana costs and storm generated values.
We also see suddenly that the ToA pile, traditionally having a lower storm
count than its BW cousin has suddenly overtake it in terms of storm generated.

This is because we can make use of a Bauble loop. Much like the historic 
looping of two SDT to generate storm we can do the same thing here.
With the BW example; Post Doomsday you use the GP to draw LED. Play and 
use LED dumping BW into the Graveyard. Now instead of sending BW to the 
bottom of your deck when you crack it to draw IU, don't target anything.
Draw IU and cast it drawing LED, LED, CB. You should have U floating from 
the first LED which you now use to cast CB. Cast the LEDs and crack them 
for BBB, RRR. Now you can use the new CB to send BW to the bottom of your 
deck to draw it and cast it with the LED mana up.

Simple enough right?

What about if you had some extra mana available before you cast the first GP?

What you can do is instead of targeting BW straight off with the second CB, 
you can instead target the first one used to draw the IU. This lets you loop
your two CBs costing only 1 mana for each loop. This means that you can directly
convert excess mana into extra storm on a 1:1 basis.

This also explains why the ToA pile above now has a greater storm count. 
The pile still has 2 mana left over after casting and using all of its LEDs
so you can use that to generate two CB loops. As a result the ToA pile
gains +2 storm compared to it's normal default.

These tricks with CB allow for a number of iterations based on these simple
concepts. They are most suited for use with either IU or IC as AoI/TW act
exactly the same way as IU but for one additional mana. They also facilitate 
piles with ToA over BW.

As CB enables many low mana cost, high storm piles it is perfect to use it for pass-the-turn piles.

Example:
```
Pass the turn.
CB in play+ToA:
-> LED, IC, LED, LED, CB                  BBB+1+X (4+X)      12+X Storm
```


## Using CB to play around hate

CB has a few niche cases that allow it to mitigate opposing hate cards. Whilst
many of its uses do have a weakness to severe Graveyard hate such as Rest in Peace,
it can help against some of the softer hate cards or corner case scenarios.

Surgical Extraction is very effective against Doomsday. It not only takes out 
potential key cards from being used but also forces the player to shuffle their
Library thereby destroying the order they had stacked it. CB can help protect the 
pile / deck by acting as a blocker. When Surgical Extraction is cast on something in
your Graveyard, you can respond by sending the target card to the bottom of the deck
thus causing the Surgical to 'fizzle' with no valid target. 

The main trick with this is timing. You obviously cannot use the CB as part of the main
pile itself so it must sit on the sidelines waiting. You also cannot use it at the wrong
time as that could lead to (as an example) instances of drawing both an LED and the IU
you intended to cast with the LED mana. Most of the time a player will attempt to Surgical
in response to you trying to draw into your Doomsday pile. If you can plan around this 
you should be able to null and void their Surgical.

Example:
```
CB in play+GP:
-> AoI, LED, LED, GP, BW                  BBB+2R (6)         8 Storm
```

If they cast Surgical in response to GP, you can use CB to send the target back into 
the deck. If they cast it in response to AoI you can do the same trick. Once AoI
has resolved, it does not matter if they cast Surgical as we have one card left in 
our Library and no copies of it to extract in the Graveyard.

A simple use of CB is simply as a non-U cantrip. Often players will
bring in Pyroblasts/Red Elemental Blasts to disrupt the combo targeting the
IU or other cantrips used to draw into the piles. CB can act as a simple 1 
mana "Draw a card" spell that nullifies the R-blasts completely. Especially
when paired with AoI or IC.

Example:
```
CB in play:
-> IC, LED, LED, BW, CB                  BBB+1+X (4+X)      7+X Storm
```

The last use I wish to present is in regards to Shelldock Isle + Emrakul Piles.
You can use CB to protect the pile against a couple of Legacy staples that are also
incidentally hate cards against such piles.

Example:
```
Pass the turn:
-> SI, Emrakul, DR, DD, LM                  BBB+U (4)      
```

This is a very basic SI pile. The idea is it contains SI to play to then Hideaway 
Emrakul, the Aeons Torn with a second Doomsday or Laboratory Maniac as Insurance at 
Emrakul or SI being dealt with. If all goes well you should be able to get two turns 
worth of 15/15, Annihilator 6 attacks in. 

There are a few cards that can hamper this plan. Jace, the Mind Sculptor and Goblin Guide 
to name a couple. You can play around these cards by making a subtle alteration to the pile.

Example:
```
Pass the turn:
-> CB, SI, DR, DD, Emrakul                  BBB+U (4)      
```

Adding CB means you can play around the cards all mentioned above. If they Jace 'fateseal'
you then it does not matter if they choose to keep the CB there or to send it to the bottom.
Goblin Guide no longer draws you a card and thus causes you to lose a turn worth of attacking.
When you draw CB you simply play it and use it to draw into SI. You can target the Doomsday 
that you used to make the pile with in order to give yourself an additional turn worth of 
Emrakul attacks.
More information on SI + Emrakul piles may be found in the <a href="https://github.com/Bennotsi-MTG/Doomsday-Codex/blob/master/shelldock-emrakul.md">Shelldock section</a>.

## Summary  

1. CB can be used to save a draw when using LED for mana   
2. CB can be used to retrieve cards for multiple use in a pile   
3. CB can be used to extend a pile   
4. CB can be used to get around some hate cards   

Hopefully this will allow a greater understanding of how to play through more of the piles that make up the <a href="https://github.com/Bennotsi-MTG/DDFT-PileDoc">Pile Document</a>. Remember as with anything it is better to learn the concepts presented here more so than to try and rote learn piles and of course, practice makes perfect.  

I would strongly advise only running 1 or 2 CB with BW variants, if any, and with ToA variants running 3 or 4.  

