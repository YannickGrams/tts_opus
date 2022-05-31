# tts_opus

Hey Cameron,

It probably won't make much sense without knowing what I'm trying to accomplish in TTS (and it probably won't make much sense even then.)
But the troublemaker is the Round End Button.

I'm trying to get it to refill a public market of 5 cards by clearing the bottommost card, then sliding all remaining cards down to fill in any gaps.
Lastly, it draws from the deck to fill the topmost space.

There's no issue if no cards are taken from the market during the round, i.e. if all 5 spaces are full at the end of the round.
In that situation, it correctly clears the bottommost card, slides the rest down and draws a new card from the deck.

But if cards are taken from the market during the round, then there will be additional spaces in the market.
I know how to check for spaces in the market, but I don't know how to do it recursively such that cards will move down to fill the lowest row available.

Not sure if any of that makes sense; I can screenshare in Discord so you can see what I'm actually trying to get done in TTS, if you'd like.

Thanks so much for your help!
