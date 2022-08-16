# EclipseCON 2022 Keyboard Talk

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
