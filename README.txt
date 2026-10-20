KAASHII — VISIBLE MESSAGE COLOURS (CH 3 + 4)  +  DARK EDGE SHADE ON THE BACKGROUND

Nothing was removed or changed anywhere else: fonts, layout, text, buttons, navigation, animations, music are as before.

1) MESSAGE BOX COLOURS (chapter 3 moods + chapter 4 gifts)
   Every message box has the same style: tinted fill + coloured border + glow, one colour per option.
   Chapter 3 : Dil heavy hai -> aqua blue | Bahut thak gayi hoon -> amber | Akela feel ho raha hai -> mint | Kuch cute chahiye -> pink
   Chapter 4 : Kind words -> pink | Biryani break -> saffron | Purple & green -> violet-to-green | Ghumne ka mood -> teal
               Soft day -> golden yellow | Care note -> pink | Cute cats -> lime | Sirf Aapka Raaz -> sky blue
   To change a colour: edit the r,g,b numbers in the "--tc" lines in the CSS block "VISIBLE MESSAGE BOX COLOURS".

2) BACKGROUND EDGE SHADE (new)
   The same deep indigo-blue that is at the top of the sky (about rgb 38,14,116) now also darkens the LEFT and RIGHT
   borders all the way down, plus a light touch in the centre.
   It sits on the sky photo but UNDER the stars, petals, hearts and the card.
   Added: one CSS block "BACKGROUND ONLY" at the end of <style>, and one line <div class="edge-shade"></div> right after <body>.
   To make it stronger / softer: change the alpha numbers in that block (edges .66 / .38 / .16, centre .20).
   To remove it: delete that CSS block and the one <div class="edge-shade"> line.

Replace the repository index.html with this index.html. Keep purple-sky.jpg and music.mp3 in the repository root.
