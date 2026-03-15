# Keyboard-pangeahandwire-rowan's

shapes based off of:
#3d files available here:
	- currently no space for magnetization modeled
	- thumb bridge attachment is weak.
	- bolts used are 2mm dia, varying lengths
	- heatset inserts are 3mm long

 

Most likely to suit those with slim long fingers & narrow/small palm ("pianist's hands")
(eventually) The userconfig(s) for my custom split keyboard (handwired) 
built partially w the cosmos generator w 5 deg curve, modified and thumb clusters added in CAD

# Design Decicisons & Goals
- Adjustable (hopefully--still WIP, first layout will likely be fixed fingers because of time)
- Split Columnar Layout
- wireless -> zmk firmware
- shallow to no keywells. starting w 5deg curve.
- Significant pinky stagger and possibly spread to match natural rest position.
- modified 3x6 + thumb layout. (2 vertically shifted outer pinkie keys) 
- magnetic bottom attachment for tenting.
- encoders x2 - possibly undo/redo, pgup/down but not fully decided
    - enc11 supported by zmc, unsure about other encoders eg. mouse-wheel
- handwired - PCB shipping is far more than the PCB printing, & cross border.
- enclosed wiring
    - conflists with adjustable intent; protective travel case another option if needed.
- Adjustable (WIP)
    - Afterthought attachment thumb cluster
        - intended to be adjusted as preferences emerge.
        - should remain on roughly same plane as fingers to avoid triggering de quervain's
        - Connect wiring to main potion with JST connectors.
        - include enough connections for 5-way swich/joystick/trackpad/ball to clusters
        - Case connection method still to be designed/determined. likely a plate with slots.
    - *considering* making it possible to shift column position, (see zebra/seismos keyboard, and Squalius' currently unnamed modular demo)
        - useful for determining ideal positioning, but also may be useful for long term preventative RSI action
    - mouse replacement (TBD)
        - a significant part of why the thumb cluster is detachable!
        - considering a palm/ball of hand trackball. unsure how it will work out, 
        - abs want to avoid thumb trackballs, and with finger trackballs I'd need to move hand off keys anyways.
        - have had pain with nubs before, but its possibly due to how implemented.

## Considerations: 
- Primarily intended to help decrease RSIs in the hand and wrist, but also in the elbow. 
- Intended to allow for better back/shoulder muscle use.
- ergenomics are more important that suitability for speed - but I do need to be able to keep up.
- Must be easily portable as I'll need to take it to classes with me via bus.
- must be suitable for programming - easy access symbols - currently using primarily html/css/javascript but looks like i'll be using other things at school.
#### Hypermobility 
- attempt to keep keys within "normal" range as extensions are more likely to cause injury.
    - remember that possible, and comfortable may not be ideal measures of appropriate range for me.
- Prolonged pressure on any one finger tends to cause strain, and more as extended as the bone post-joint becomes less supported by bone and more by tendon (thumb may be more or less resistant due to different joint structure)
- try to keep to three row layout: index and ring can easily reach a 4th row, but the joint feels off afterwards
  - decrease pinky vertical reach/drop
  - aim for low cental and outer column useage
- keep thumb cluster to few larger buttons.
- Keep split wide for all the usual reasons + help with weak scapula related muscles & overtight collerbone ones.
    - some concern here wrt cronic shoulder subluxation.
    - start *slowly* moving boards appart to allow time for alterations if it causes shoulder to act up. 
#### Former Cronic RSI
- of all sorts, not just carpal
- suspect things like tapdance are not optimal, but no actual information.
- *different* non-strained movements are helpful with RSIs
    - other than adjustable columns & swapable thumb that would be implemented in keyboard design/layout. I suppose just changing angles and tenting frequently?
    - keywells can discourage movement - may be better to use a flat stagger--testing needed.
- thumb primary movement is perpendicular(ish) to finger movement, making it clumsy in a keyboard plane. However out of plane thumb clusters may contribute to de quervain syndrome/trigger thumb/gatekeeper's thumb etc. Fulcrum's [https://github.com/dschil138/Fulcrum] thumb implementation might be a decent direction?
- thumb outward movement is more comfortable than inward, but I should probably stop that extension at ~45deg to fingers
- Avoid right-hand dominant layouts, as I need to rest/relieve some of the strain on that hand from mouse & art movements, my left hand has only ever had issues when I had to overcompensate for RSI flares in the right.
- Avoid overly thumb intensive layouts, as they seem to get irritated somewhat frequently already.
#### Current RSI/Strain
- surprisingly, currently primarily in my right thumb, pointer & middle fingers to varying mild degrees.
    - suspect this is due to mouse useage on suboptimal desks, so not a major consideration for ongoing use, but in the short term this is going to be unfortunately frequent.

## Layouts
- currently only very roughly tested on a semi-split row stagger board.
- as intent is for use on an column-stagger, I have not prioritized between any of these.
- recomended **against:** Engram, Engrammer, Beakl, Dvorak, carpalX, norman, workman (colemak(/colemak-DH?) best of stay similar to qwerty layouts - recomendd against for ero though apparently - too much index useage and redirects), halmak 

### Layout: The-1 
k m l u ?  v d r ' q
a t h e .  c s n o i
z p f j ,  b g w x y
- information: [https://docs.google.com/document/d/1yiCnIi1oagV1D8ZouMt-TRFRG8d6AfSBIwQkBvSflvY/edit?tab=t.0]
  - I don't know if this is the original writer's copy of the file or not
  - primary focus on what it calls splats, but sound like rolls & 2 key rolls. prioritizes inward direction
  - the logic behind it seems sound enough.
  - not fond of the ' location, may change to more accessible finger
 
### Layout: Sturdy
v m l c p  x f o u j
s t r d y  . n a e i 
z k q g w  b h ' ; ,
- very high rolls, low redirects. Decent in other metrics
- uses left ring finger heavily

### Layout: Canary Ortho
w l y p b  z f o u '
c r s t g  m n e i a
q j v d k  x h / , .
- information: [https://github.com/Apsu/Canary]
- Primary focus on high rolls (bidirectional)
- is at least somewhat right-hand dominant

### Hands Down Promethium
f p d l x   ; u o y b z 
s n t h k   , a e i c q 
v w g m j   - . ' = / 
      r       SPACE
  - (all) hands down are highly opinionated re hand balance! roughly equar right and left, stronger index/middle more than ring and pinkie
  - asymetrical - extra 2 pinkie on right
  - high rolls.
  - higher on SFBs, Scissors (u' and gl being worst) and weak redirects, FSV high on same finger skipgrams

### Layout: Kuntem (Kuntum w aei switched to aie)
v l n d k  j w o u ,
t s r h f  g c a i e ;
z x p b '  m y q / .
- niche due to  2 quirks: i (or e) and T on the pinky
- supposedly no good for Column...but I wanna try, or at least incorperate that pinky use thing, it feels right. Maybe a good start for a machine learning board a la [Atomic Frontier](https://github.com/AtomicFrontierCode/keyboards) (try and find a better algo though, optim for more variables)
- information: ??? only mention of design philosophy for it I can find: [https://www.reddit.com/r/KeyboardLayouts/comments/1jrz2iy/kuntem_layout/] [https://layouts.wiki/guides/start/recommendations/]
- layout opinion: pinky *use* is no more difficult than others - *movement* is
- note 6 keys in right homerow
- focus on combos

### Birdie
  l p d f   ' w o u 
t s n h m   g c a i e 
v z b k q   x y , . j 
      r       SPACE
- thumb "r"
-only 2 pinky fingers, period.
-like Kuntem, high pinky use, low movement
- main problems are SL (same finger bigram - cannot be alt-fingered b/c ortho) and BL (variable by amount of column stagger)

### Racket
f d l w j   ; b o u , 
s t h c y   q n a e i -
x k m g v   z p ' / . 
       r   SPACE
-Very low SFB, SFS, lateral strech and no major problem keys
- finger distribution towards favoring the weaker fingers (esp. left ring) more than most.
- S & F on left pinky may be too much. Can be solved w F & Q swap

### Layout: Canary Column
w l y p b  z f o u '
c r s t g  m n e i a
q j v d k  x h / , .
- information: [https://github.com/Apsu/Canary]
- high in 2-rolls
- uneven finger use distribution - high left index & right hand
- high SFSs

### Layout: Gallium Column
b l d c v  j y o u ,
n r t s g  p h a e i
x q m w z  k f ' ; .
- balanced consideration of layout metrics
- considered a good "battle tested" layout

### Layout: Bunya
b l m c z   x f o u ,
n r t d p   y h a e i - 
; j q g w   k v ' / . 
       s    space
- left thumb 's'
- fixes gallium's main problems (except B-R scissor)
- drawback: ss is a common repeat and thumbs are slow
- drawback: high lateral stretches

### APTV3
w g d f v  q l u o y 
r s t h k  j n e a i 
x c m p b  z , . / ; '
- balanced hand useage, low movement
- if dislike ' on thumb, move to /

### APTV3ex
x c d f b  q l u ' ;
r s t h k  j n a o i
w g m p v  z , . / y
           e
- sim to aptv3, but e on thumb


### Misc notes:
- ideas for combos, not alpha: [https://www.justinmklam.com/posts/2025/05/corne-keyboard/]
- KeymapDrawer (presentation) [https://github.com/caksoylar/keymap-drawer-web?tab=readme-ov-file]
- guide to ergo considerations for layouts **goes into symbols layer etc**: [https://ratoru.com/blog/choose-the-right-base-layout/]
    - abv rec'd reading for other symbol POVs:
          - designing a symbol later[https://getreuer.info/posts/keyboards/symbol-layer/index.html]
                  - provides list of layout optimizer tools!
          - prog lang symbol freq: [http://xahlee.info/comp/computer_language_char_distribution.html]
          - recomends arensito layout for programming, dead link. Discussion of it here though [https://www.spidersdreaming.com/gallery/keyboard] - seems for rowstaggered
- mostly for comment on text expanders: https://community.keyboard.io/t/keyboard-layout-philosophies/1732/7
- lots of links to good discussion & layouts: [https://www.reddit.com/r/KeyboardLayouts/comments/1my42c3/recommended_layouts/]
- jump to programming section of one rec: [https://getreuer.info/posts/keyboards/alt-layouts/index.html#which-layout-is-best-for-programming]
- [https://dreymar.colemak.org/]
- ergo guide: [https://dreymar.colemak.org/index.html]
- navigation (extend) notes: [https://dreymar.colemak.org/layers-extend.html]
- ergo guide: [https://forum.colemak.com/topic/2671-vipers-ergonomics-guide/#p23699]
- tips for learning new keyboard layout [https://www.youtube.com/watch?v=sI-a64EVPPU]
- layout weighting? design? not 100% sure: [https://github.com/O-X-E-Y/oxeylyzer]
- keyboard metrics analyser : [https://oxey.dev/playground/index.html]
- keyboard layout information (I think this is where i got the link to "the1" layout) [https://docs.google.com/document/d/1W0jhfqJI2ueJ2FNseR4YAFpNfsUM-_FlREHbpNGmC2o/edit?tab=t.2ztid8v3jw2i]
