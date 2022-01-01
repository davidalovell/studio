# To do

## Next
- Work on switching sequencer
- Write email to monome

## Later
- Work on Vox/Seq
- Earthsea/Morphagene learning
- Work on TSNM script

## Switching sequencer script
- Work on switching sequencer idea
- Document different ways of doing it
- Try sequencing seq.action_on
- Try sequencing seq.advance_on
- Bass sequence to suggest chords
- Play minor pentatonic starting from the major 3rd degree of a major 7th chord
- Play minor pentatonic starting from the major 7th degree of a major 7th chord

## Vox/Seq
- Add comments to help with how to use user properties
- Add comments to say you need a nil handler in vox.action
- ?Add seq.return_on (to complement seq.action_on and seq.advance_on)
  - This could integrate with seq.skip and seq.prob anbut may require a rewrite
- Save vox, seq as github libs and leave alone
- Save these in their own folder on norns
- Read docs on how to include lib not in folder on norns

## Earthsea/Morphagene
- Read docs and play
- Couple this with Morphagene
- Reverb
- Distortion
- Feed into Digitakt
- Write a helper document

## TSNM helper script
- input[1]: cv
- input[2]: gate
- output[1]: clock
- output[2]: lfo: use triple attenuator
- output[3]: lfo
- output[4]: lfo
- txi.input[1]: left = off/ reset, centre = start, right = clear scale
- txi.input[2]: tempo
- txi.input[3]: bass pattern
- txi.input[4]: w/ pattern
- txi.param[1]: bass: 0-1 = off, 1-9 = volume
- txi.param[2]: lead: 0-1 = off, 1-9 = volume - ?create your own way of cycling notes
- txi.param[3]: harmony: 0-1 = off, 1-9 = volume
- txi.param[4]: w/: 0-1 = off, 1-9 = volume

## Email
Updated to crow 3.0
Every time I uploaded a script, crow would fail to respond after doing so
I would have to restart the case in order to get crow to respond
Upon doing so the new script had uploaded and would work straight away
Shorter scripts would sometimes work without having to do this
But, sometimes live-coding long lines of code (e.g. clock.run(...stuff...)) would cause the same problem
Downgrading to crow 2.0 solved the problem, but I wanted to use all the features of crow 3.0 so decided to live with the problem at that point

I can write some lines of code into druid
But if I wrote commands like print('something') would produce nothing
But if run from within a loop, for example, would sometimes print but would be interspersed with <crow connected>, often multiple times

Things to try again:
1. A different cable
2. The same script with the isms case
3. Reconnect the Txb

<!-- Hi folks,

I'm having an odd i2c time and am looking for some help.

I have an Intellijel Palette case that has crow, TXo, JF, two w/ and a TXb. It mostly works, but I found some strange behaviour with the two w/.

They both follow commands sent from crow if they are in w/syn mode. I have even been able to address them separately using the method described here: https://llllllll.co/t/mannequins-w-2-beta-testing/34091#alternate-ii-address-4.

However, when either of them is set to w/del or w/tape and I sent an ii message to change a parameter the whole system freezes. No more messages can be sent or received from crow.

I have tried a few i2c-type things:
1. All modules in series, then with the addition of the TXb
2. All modules in parallel connected to the TXb - exactly the same

Next I plan to disconnect everything but the w/ and crow and reconnect everything one at a time. Then I'm going to have a look at the TXb, which actually sits within the case.

It is super strange that when in w/syn mode everything works perfectly. I'm using w20b7 firmware.

Incidentally, I have an issue with crow which means I have to do a hard reset after I run or upload a script. I've always wondered if this was i2c related.

Thoughts? Anyone?
Thank you! -->

## Astrabel
### Website
- home
  - add photo
- posts
  - add photo to first post
  - create a new post about recordings and process from last night + photo
- audio
  - media player with playlist of all audio
- about
  - write an about section
  - Instagram link
  - Soundcloud link
- section about pork & beef

### Instagram
- Come up with a plan for posting pictures and videos

### Soundcloud
- Tidy up page
- Better photos
- Just a block of colour at the top?
