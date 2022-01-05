# To do

## Next
- Work on TSNM script
- Work on switching sequencer script
- Work on website
- Work on Vox/Seq

## TSNM helper script
### input[1]:     cv
done
### input[2]:     gate
done
### output[1]:    clock
done
### output[2]:    reset gate or lfo
to do
### output[3]:    lfo
to do
### output[4]:    lfo
to do
### txi.input[1]: left = gate off + sequencer off + reset, centre = on, right = clear w/ scale + w/ sequencer off
left - working for gate, but need to also turn off sequencer, this may also help sync the sequencer to the gate
centre - working
right - working for clear w/ scale, but need to turn the sequencer off too
### txi.input[2]: tempo
done

### txi.input[3]: bass pattern
### txi.input[4]: w/ pattern
### txi.param[1]: bass: 0-1 = off, 1-9 = volume
### txi.param[2]: lead: 0-1 = off, 1-9 = volume - ?create your own way of cycling notes in JF
### txi.param[3]: harmony: 0-1 = off, 1-9 = volume
### txi.param[4]: w/: 0-1 = off, 1-9 = volume








## Switching sequencer script
- Work on switching sequencer idea
- Document different ways of doing it
- Try sequencing seq.action_on
- Try sequencing seq.advance_on
- Bass sequence to suggest chords
- Play minor pentatonic starting from the major 3rd degree of a major 7th chord
- Play minor pentatonic starting from the major 7th degree of a major 7th chord

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

## Vox/Seq
- Add comments to help with how to use user properties
- Add comments to say you need a nil handler in vox.action
- ?Add seq.return_on (to complement seq.action_on and seq.advance_on)
  - This could integrate with seq.skip and seq.prob anbut may require a rewrite
- Save vox, seq as github libs and leave alone
- Save these in their own folder on norns
- Read docs on how to include lib not in folder on norns
