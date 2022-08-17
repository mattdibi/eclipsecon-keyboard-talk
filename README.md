# EclipseCON 2022 Keyboard Talk

## 34 keys is all you need: an ergonomic keyboard journey

### Description

In the latest years the custom mechanical keyboard scene has blown up significantly, reaching mainstream status among (not only) software developers. Nevertheless there's an overlooked niche of this hobby that greatly benefits from the open source ecosystem and the online community: ergonomic mechanical keyboard.

In this talk I'll walk you through the deep end of the custom ergonomic mechanical keyboard rabbit hole and explain why 34 keys is all you need (really!) and what are the benefits of such a keyboard.

### Detail

In this talk I'll focus on various aspect of modern keyboards and their outdated design and walk through the improvements the open source community brought to this field.

- Hardware: Physical layout and how to improve on a design that dates back to the 19th century. Columnar stagger, split keyboards, thumb clusters and splay will be the keywords for this section.
- Software: How the open source keyboard firmwares changed how we use the keyboard. I'll talk about advanced firmware features like layers, mod-taps, caps word and combos.
- Layout: Functional layout and how the QWERTY layout was designed to slow you down (really!). I'll talk about modern alternatives like Dvorak, Colemak-DHm and Miryoku which leverages the more advanced features of modern firmwares.

Finally I'll put everything together and talk about my current daily driver: a 34-keys bluetooth split keyboard powered by the open source ZMK firmware and the Miryoku layout.

---

## Building the presentation

These slides are using [Marp](https://marp.app/) Markdown Presentation Ecosystem. Usage documentation can be found [here](https://marpit.marp.app/). Example [here](https://speakerdeck.com/yhatt/marp-basic-example?slide=20) and [here](https://raw.githubusercontent.com/hahnec/marp-recipes/master/marp_recipes.pdf).

For building the slides in this repository using the [official Docker image](https://hub.docker.com/r/marpteam/marp-cli/) use the following commands:

```bash
git clone https://github.com/mattdibi/eclipsecon-keyboard-talk.git
```

```bash
cd path/to/eclipsecon-keyboard-talk
```

Convert slide deck into HTML:

```bash
docker run --rm -v $PWD:/home/marp/app/ -e LANG=$LANG marpteam/marp-cli --bespoke.transition --bespoke.progress --preview slides.md
```

or use server mode (serve current directory in http://localhost:8080/)

```bash
docker run --rm --init -v $PWD:/home/marp/app -e LANG=$LANG -p 8080:8080 -p 37717:37717 marpteam/marp-cli --bespoke.transition --bespoke.progress -s .
```
