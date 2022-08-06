# EclipseCON 2022 Keyboard Talk

These slides are using [Marp](https://marp.app/) Markdown Presentation Ecosystem. Usage documentation can be found [here](https://marpit.marp.app/).

For building the slides in this repository using the [official Docker image](https://hub.docker.com/r/marpteam/marp-cli/) use the following:

```bash
# Convert slide deck into HTML
docker run --rm -v $PWD:/home/marp/app/ -e LANG=$LANG marpteam/marp-cli --bespoke.transition --bespoke.progress --preview slides.md
```

```bash
# Server mode (Serve current directory in http://localhost:8080/)
docker run --rm --init -v $PWD:/home/marp/app -e LANG=$LANG -p 8080:8080 -p 37717:37717 marpteam/marp-cli --bespoke.transition --bespoke.progress -s .
```
