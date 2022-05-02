MIRRORZ  by Zwabo

Description:

MIRRORZ is a nice ambiant tool I did for my proper use. Could be interesting for the community, so here it is.

Unlike other reverse delays, the TRIGGER function of MIRRORZ  allows you to play backward the last chords/ melody you JUST played (not delayed), same for the LOOP function but looped.

Audio IN is permanently recorded in a 32 seconds buffer.

Control Ports:

TRIGGER : Default 0, Min 0, Max 1
LOOP : Default 0, Min 0, Max 1
DRY/WET : Default 0.5, Min 0, Max 1.
FILTER : Default 0, Min -100, Max +100 
SPEED : Default 1, Min 0.5, Max 2


These control ports are knobs.
About TRIGGER and LOOP : I don’t know how to change their control port property to “trigger” to make this plugin more “Plug ’n play”. Any help appreciated…

For now you have to use two Control to CV plugins in your pedalboard, i.e.:

-Footswitch 1  (momentary ON ) -> Control to CV -> TRIGGER 0-1 parameter
-Footswitch 2  (momentary ON ) -> Control to CV -> LOOP 0-1 parameter


How it works:

- Pressing footswitch 1 (momentary ON ) start reading audio backward from the last sampled position within the data/buffer , releasing footswitch 1 stop reading audio.

- Pressing footswitch 2 (momentary ON ) reads audio backward from the last sampled position within the data/buffer, releasing footswitch 2 loop the buffer segment just read. Pressing footswitch 1 stop the loop (if you keep footswitch 1 pressed , it reads audio backward from the last sampled position within the data/buffer)

- Dry/wet  obvious
- Filter  0 ->  -100 Low pass  ,  0 -> 100  High pass
- Speed  0.5 = /2   1=1  2= x2
