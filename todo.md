# To do

## Next
- TSNM system exploration
- Design an Isms set up
- Work on switching sequencer script
- Work on website
- Work on Vox/Seq

## TSNM system exploration
- Just patch and explore

- Use the arp in unlatched mode
- Learn TSNM live settings

- Learn how to use the TSNM sequencer mode

- Record loops by hand, improve your timing
- Practise sound-on-sound loops
- Practise layering loops that slowly fade out
- Sync'ed delays

## Switching sequencer script
- Work on switching sequencer idea
- Document different ways of doing it
- Try sequencing seq.action_on
- Try sequencing seq.advance_on
- Bass sequence to suggest chords
- Play minor pentatonic starting from the major 3rd degree of a major 7th chord
- Play minor pentatonic starting from the major 7th degree of a major 7th chord

## TSNM video or llllllll post
- Have a think about this

## Website
- home
  - add photo
- posts
  - add photo to first post
  - have a look through some audio and upload
- audio
  - media player with playlist of all audio
- about
  - write an about section
  - Instagram link
  - Soundcloud link
- section about pork & beef

## Vox/Seq
- Add comments to help with how to use user properties
- Add comments to say you need a nil handler in vox.action
- ?Add seq.return_on (to complement seq.action_on and seq.advance_on)
  - This could integrate with seq.skip and seq.prob anbut may require a rewrite
- Save vox, seq as github libs and leave alone
- Save these in their own folder on norns
- Read docs on how to include lib not in folder on norns

## Isms
### Aims
- A flexible set up for patching
- But a clear idea of what everything is for
- Start with a basic patch that you can build from

### Basic patch
- Isms LFO is the master clock (for now)
- Clock into Teletype
- Teletype trigger out to Ansible clock in
  - OR clock Ansible from Teletype via ii (less reliable)
- Teletype is the only ii leader
- Teletype queries Kria CV
- The best way to get gates from Kria is via patch cables into Teletype
- Teletype uses the metro script to get FB values and send them to ER-301

### Modules and functions
- Crow
  - Main clock from Digitone via Norns

- Ansible (Grid)
  - ?Kria
  - ?Meadowphysics
  - Clock from Crow

- Ansible (Arc)
  - ?LFOs
  - Not sure how I will use this yet
  - I need to have a look at all the apps

- Teletype
  - Clock from Crow
  - Metro to send Sweet Sixteen data to ER-301
  - Sequencer
  - Harmony
  - Rewatch DR tutorial video

- TXo
  - ?Envelopes
  - ?LFOs
  - ?Wavetable oscillators

- TXi
  - Control for TXo or Teletype params
  - ?Attack/release time
  - ?LFO rate/depth
  - ?Wavetable oscillator control

- ER-301
  - Update firmware
  - Learn how to record direct
  - Learn how to use sample records
  - Download trash echo and other stuff

- Sweet Sixteen
  - To control the ER-301
  - Voltage offsets
  - Attenuators

- JF 1
  - Linked with ansible

- JF 1
  - ?Envelopes
  - ?LFOs
  - ?Harmonic oscilator via Teletype
  - ?Big fat VCO
  - Just type voice

- Mangroves
  - Two voices
  - Complex oscillator with Cold Mac

- Sisters
  - Spectral mixer
  - Pinged percussion

- Cold Mac

- W/ 1
  - W/syn
  - Controlled from kria
  - or TT

- W/ 2
  - W/del

- Morphagene
  - Use it as a sound source
  - Use it as a live processor
  - Use it to record loops
  - Learn how to use button combos
  - Learn how to use reels
  - CV control with crow or txo
  - Use it with a sequencer