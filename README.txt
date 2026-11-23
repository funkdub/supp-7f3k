VFXStudio: Visual Effects Generation with Scene Interactions
Supplementary video results. Open index.html in a browser, or play the files directly.
Every clip: 8 fps, 49 frames, H.264. The page makes no external request.

== Interaction control ==
11 clips of 4 input images, VFXStudio only, 720x480: one image and one effect per group, rendered with
different relation tables. Showcase scenes, seed 42; they enter no table.
File names: <image>__<edit>.mp4
  def                  default relation table
  smid / shi           response strength scaled by the factor given below
  dXXX                 response direction of every responding object set to XXX degrees
                       (counter-clockwise, 0 = right, 90 = up)
  r180                 default directions reversed
still_<image>.jpg is the first frame of the clips of an image, that is the input image.
-- Explode the green jar (effect onset frame 12)
w_jars__def.mp4	Default
w_jars__shi.mp4	Strength x2.0
w_jars__d090.mp4	Direction 90 deg
-- Explode the green pepper (effect onset frame 12)
peppers__def.mp4	Default
peppers__shi.mp4	Strength x2.5
peppers__d180.mp4	Direction 180 deg
-- Explode the brown soap (effect onset frame 12)
soap__def.mp4	Default
soap__shi.mp4	Strength x2.5
soap__r180.mp4	Direction reversed
-- Crumble the green soap (effect onset frame 8)
soapw__def.mp4	Default
soapw__smid.mp4	Strength x2

In the comparison clips below, method names are printed above each panel; clips without printed names show VFXStudio only.

== Single-VFX ==
single_deflate_3.mp4	Red sports car deflates like a balloon.
study_08.mp4	Levitate the teddy bear, while the teddy bear next to it stays on the ground.
single_harley_2.mp4	Give the girl a Harley Quinn look with pigtails.
single_venom_3.mp4	Turn the man into Venom.
single_venom_4.mp4	Turn the penguin into Venom.
cmp_venom.mp4	Turn the man into Venom.
-- Interaction with neighbouring objects
w_globe__def.mp4	Explode the snow globe.
citrus__def.mp4	Explode the lime.
toys__def.mp4	Explode the red bucket.
study_02.mp4	Explode the bottle on the left, and the pastry next to it is pushed away.
study_20.mp4	Explode the donut on the left, and the donut next to it is pushed away.

== Multi-VFX ==
cmp_vases.mp4	Dissolve the carved vase, crumble the tall vase, and Inflate the small vase.
cmp_blocks.mp4	The R block melts, the A block levitates, and the D block crumbles, while the E block stays still.
study_12.mp4	Levitate the person on the bottom-right and the elephant on the left.
mul_06.mp4	Deflate the chair, dissolve the suitcase, and change the setting to winter.

== Additional results ==
-- One object under several effects, choice of target, three effects at once
extra_one_01.mp4	Explode the striped ball.
extra_one_24.mp4	Explode the orange and melt the glass.
-- Effects together with a background style
extra_style_15.mp4	The blue beach hut melts, and the scene turns into a rainy day.
extra_style_16.mp4	Explode the yellow beach hut and change the setting to winter, while the blue and red beach huts stay still.
extra_style_22.mp4	Melt the banana, levitate the apple, and turn the background into an oil painting, while the wine glass stays still.
extra_style_23.mp4	Melt the banana, levitate the apple, and change the setting to winter, while the wine glass stays still.
-- Further cinematic scenes (input frames are film stills)
f_chips__def.mp4	Explode the pile of chips.  [film still: Casino Royale]
f_top_l__def.mp4	Levitate the spinning top.  [film still: Inception]
f_falcon_l__def.mp4	Levitate the spaceship.  [film still: Star Wars]
f3_idol_m__def.mp4	Melt the golden idol.  [film still: Raiders of the Lost Ark]
f3_apple_x__def.mp4	Explode the green apple.  [film still: Oppenheimer]
f3_apple_m__def.mp4	Melt the green apple.  [film still: Oppenheimer]
f3_gate_c__def.mp4	Crumble the park gate.  [film still: Jurassic Park]
f3_house_l__def.mp4	Levitate the model house.  [film still: Beetlejuice]

== Image credits ==
Photographs: COCO and Wikimedia Commons. Wikimedia Commons images, with author and licence:
3 Hourglasses Wellcome L0011331.jpg. Wellcome Collection, CC BY 4.0
5-pin bowling pins (4177654894).jpg. Benjamin J. DeLong, CC BY 2.0
A row of beach huts on Western Esplanade, Hove.jpg. Robert-brook, CC0
Apple orange smoothie (34365737850).jpg. Easy Healthy Smoothie, CC BY 2.0
Bars of pure Marseille and Aleppo soap, 2024.jpg. DimiTalen, CC0 (one scene uses it zoomed out, with the added border filled in synthetically)
Billiards table 1.JPG. MarkBuckawicki, CC0
Cucurbita pepo 2013 G1.jpg. George Chernilevsky, Public domain
Four barrels by the sea.jpg. W.carter, CC0
Honey Cake (Unsplash).jpg. Toa Heftiba heftiba, CC0
Its beach time.jpg. Nina Matthews, CC BY 2.0
Lawn Chairs 2-G and 2-H -- Meadowlark Botanical Gardens Vienna (VA) 2012 (7276605626).jpg. Ron Cogswell, CC BY 2.0
Lemon & Lime Series (3047085290).jpg. THOR, CC BY 2.0
Milk churns pair.jpg. Martin Bishop, CC BY 2.0
Mother Nature, Summer (Unsplash).jpg. Autumn Goodman auttgood, CC0
Pair of Teacups and Saucers LACMA 26.1.4.1-.4 (2 of 4).jpg. Chamberlain's Factory (England, Worcester, 1788-1852), Public domain
Percolator coffee and kettle on the stove top.jpg. Emily Allen, CC BY 2.0
Read' Spelled out in wooden learning blocks with stacked blocks in the background. - 51070730562.jpg. perpetual.fostering, CC BY 2.0
Salted caramel macaron on plate, profile, February 2011.jpg. saaleha bamjee, CC BY 2.0
Schneekugel Wikipedia25 WMAT-2026 004 Eule.jpg. Manfred Werner (WMAT), CC BY-SA 4.0
Set van drie tonvormige potjes, Manufacture de Céramiques Décoratives de Hasselt, 1895-1954, SMU.2023.0058.00, Het Stadsmus.jpg. Manufacture de Céramiques Décoratives de Hasselt (1895-1954), CC BY-SA 4.0
Sitting And Smiling (Unsplash).jpg. Brooke Cagle brookecagle, CC0
Teacup and saucer.jpg. Unknown artist, CC0
Teapot and mug on table (Unsplash).jpg. Jorge Garcia jorgeblah, CC0
The Perfect Cupcake (Unsplash).jpg. Brooke Lark brookelark, CC0
Three bell peppers 2017 A.jpg. Fructibus, CC0
Three Milk Churns.jpg. Irish American Mom, CC BY 2.0
Vases-Wedgwood-BMA.jpg. Elwyn James, Michael Dillon, David Puxley, CC BY 3.0
Film stills: Beetlejuice, Casino Royale, Inception, Jurassic Park, Oppenheimer, Raiders of the Lost Ark, Star Wars.
