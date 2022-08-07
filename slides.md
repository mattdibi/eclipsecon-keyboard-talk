---
theme: uncover
class:
- invert
paginate: true
size: 16:9
author: Mattia Dal Ben
transition: fade
---

![bg cover opacity:.7 blur:1px](media/uwldcrj8vca91.jpg)

## <!--fit--> 34 keys is all you need 
_An ergonomic mechanical keyboard journey_

<!-- _footer: Author: Mattia Dal Ben -->
<!-- _paginate: false -->

---

####  Who am I?

- Master degree in EE
- Work as SWE @ Eurotech
- Mechanical keyboard enthusiast and maker
- Designed the _Redox Keyboard_ and the _Yampad_

![bg right](media/yampad.jpg)

---

### What is this talk about?

- Sub 40%
- Ergonomic
- Low profile
- Open source
- Mechanical
- Keyboards

![bg fit left](media/drake-approves--disapproves.png)

<!--
* We're not gonna talk about your average custom mechanical keyboard
* We're gonna talk about small from factor (sub 40% i.e. 35 keys), ergonomic, low profile (choc), open-source(mostly), mechanical keyboards
* We're gonna talk about what firmware/software features/techniques make them a viable option (features that can be applied even to normal keyboards)
* ... and, above all, **why** should you want to try them.
-->

---

### Talk outline

1) _Hardware_
2) _Software_
3) _Layout_
4) _Miryoku_

<!-- 
1. _Hardware_: Advancement on keyboard physical layout.
2. _Software_: New features that make such keyboards viable
3. _Layout_: QWERTY is bad basically
4. _Miryoku_: Let's put it all together
-->

---

# <!-- fit --> 1. Hardware

---

![bg cover brightness:0.9](media/hardware/20220807_160901.jpg)

<!--
On the left you can see a Corona Model 4 that was introduced around 1920
On the right a  2020 MacBook Air

There's a century between these two and they use the same keyboard...
-->

---

# <!-- fit --> Why are we still stuck with this s***?

![bg blur opacity cover](media/hardware/20220807_160901.jpg)

<!--
Keyboard design essentially didn't change since 1880 when typewrites appeared. We're burdened by design choices due to mechanical/physical constraints that no longer exist. Nobody even question it...

... and this is stupid...
-->

---

# <!-- fit --> Let's try and fix that

---

# Split halves

> "Your wrist are not built to bend like that. Split the keyboard to have a more natural posture."

![bg opacity:0.8 blur](./media/hardware/dantambok-superme-mechanical-keyboard.webp)

<!--
Ulnar deviation occurs when your wrist is bent outward in the direction of your little finger. It is among the most common and potentially damaging keyboard postures and can lead to carpal tunnel syndrome and other serious repetitive strain injuries.

Your wrist are not built to bend like that. Split the keyboard to have a more natural posture.
-->

---

![bg](./media/hardware/dantambok-superme-mechanical-keyboard.webp)

---

# Thumb cluster

> "Why is your strongest finger used to press only a key?"

![bg opacity:0.8 blur](./media/hardware/Dygma-Raise-Split-Gaming-Keyboard-3.png)

<!--
Why is your strongest finger used to press only a key? This is dumb. Give it more keys!
-->

---

![bg](./media/hardware/Dygma-Raise-Split-Gaming-Keyboard-3.png)

---

# Columnar stagger

> "The row staggered layout is a heritage from the old typewriters that needed such an arrangement to prevent the percussors to get stuck."

![bg opacity:0.8 blur](./media/hardware/redox-1.jpg)

<!--
The row staggered layout is a heritage from the old typewriters that needed such an arrangement to prevent the percussors to get stuck. Such a design is not needed anymore and doesn't fit with the human hand conformation.
-->

---

![bg](./media/hardware/redox-1.jpg)

---

# Minimal

> "We are moving our keys to the fingers, we're not moving our fingers to the keys"

![bg opacity:0.8 blur](./media/hardware/1wubhh0.jpeg)

<!--
- Less distance between keys (minimal key travel) means fewer errors
- Less hand repositioning which means fewer errors (I found that most of my mistakes were due to repositioning my hand after moving away from the home row, these can't exists if you're always on the home row) Example of annoying movements: home row -> esc, home row -> arrow keys
- Improving typing habits: I've always used the pinkies incorrectly especially for pressing the "shift" key which made them hurt after a day of work. With the miryoku layout I am forced to use the index and to alternate between left and right hand (which is the correct way of doing it).
- The "limitation" of they keyboard made me discover new ways of typing: I can't keep backspace pressed to delete a word if I need to because this triggers the layer, due to this I discovered (and *actually started using*) the alt/cmd+backspace combinations which improved my typing habits again. This is now ingrained in my muscle memory and use it everywhere (like the alt+cmd arrow keys).
- Due to their placement (home-row mods) shortcuts are so much easier to type (see iTerm2 tab/split change)
- Portability (duh!)
- It is **fun**
-->

---

![bg](./media/hardware/1wubhh0.jpeg)

---

# Key wells and tenting

> "A moderate elevation of the thumb side of the hand dramatically reduces the pressure on the forearm muscles."

> "The concave key wells ensure the keys are reachable and mimic the curve drawn by our fingers."

![bg opacity:0.8 blur](./media/hardware/skeletyl.jpg)

<!--
Pronation in the forearm and wrist occurs when typing with your palms face down towards the worksurface. The majority of this turning involves the rotation of both forearm bones (ulna and radius).

Sustained pronation puts pressure on the forearm muscles and tissues which reduces blood circulation and can lead to fatigue and repetitive strain injuries (“RSI”). Research demonstrates that a moderate elevation of the thumb side of the hand dramatically reduces the pressure on the forearm muscles.

The concave key wells ensure the keys are reachable and mimic the curve drawn by our fingers.
-->

---

![bg](./media/hardware/skeletyl.jpg)

---

# <!-- fit --> 2. Software
