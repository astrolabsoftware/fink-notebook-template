# Fink broker tutorials

This repository contains materials (notebooks & presentation) to explore the [Fink broker](https://fink-broker.org) alert data. As of April 2021, Fink has collected more than 80 million alerts from the ZTF public stream, and processed more than 30 millions (after quality cuts). Among these, you will find extragalatic sources (supernovae, AGN, ...), galactic sources (many classes of transients incl. variables stars from our galaxy or gravitational microlensing events, ...) and moving objects from our Solar System (asteroids, comets, and made-man objects like space-debris!).

## Materials

The repository contains a number of notebooks focusing on the use of the Science Portal API. We shortly present different science cases:

- Extragalactic science: AGN & supernovae ([open in colab]())
- Galactic science: variable stars & microlensing ([open in colab]())
- Solar system science: asteroids, comets & space debris ([open in colab]())
- Multi-messenger astronomy: searching for kilonovae ([open in colab]())
- Broker interfaces: presentation on the livestream service, the Science Portal and its API, and the Fink TOM module ([read the presentation]())


You can try the notebooks using Google Colab (follow the links above). You can also clone the repo, and try it locally (very little external libraries are required).

## How to contribute

How to contribute:

- Clone (or fork) this repo, and open a new branch.
- Create a new folder with a meaningful name (e.g. `supernovae`, `grb`, ...)
- Copy and read the [example/example.ipynb](example/example.ipynb) to get an  idea of the structure of a tutorial (or take inspiration from the existing ones).
- Once your notebook finished, open a Pull Request such that we review the tutorial and merge it.
