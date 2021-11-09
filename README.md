# Mandelbrot

## Forberedelser:
- Last ned Anaconda: https://www.anaconda.com/products/individual#Downloads (Graphical installer)
- Installer og åpne Anaconda Navigator
- Trykk på 'Environments'
- Trykk på 'Create'
- I dialogen som dukker opp: fyll ut et navn og trykk 'Create'
- Trykk på 'Channels'
- Trykk på 'Add...'
- Lim inn https://conda.anaconda.org/conda-forge/ og trykk på enter
- Trykk på 'Update channels'
- Trykk på 'Update index...'
- Pass på at nedtrekkslista til venstre for 'Channels' står på 'All' eller 'Not installed'. I 'Search Packages'-feltet kan du nå søke etter **tensorflow**
- Velg 'tensorflow' og trykk 'Apply'
- Søk også opp pakken **pillow** og 'Apply'
- Du kan også installere pakken **moviepy** hvis du vil lage gifs


## Intro

- Complex numbers: https://www.youtube.com/watch?v=SP-YJe7Vldo
- The Mandelbrot set: https://www.youtube.com/watch?v=FFftmWSzgmk


## Let's go!

- Klon dette repoet: https://github.com/kimsb/tensorflow-fractal-playground
- I Anaconda, trykk på play-knappen for miljøet du har laget, og velg 'Open terminal'
- Naviger til prosjektet du har klonet, og følg READMEen i det prosjektet.

- Hvis du får feilen <code>Parameter to MergeFrom() must be instance of same class: expected tensorflow.TensorShapeProto got tensorflow.TensorShapeProto.</code> , kjør kommandoen <code>pip install -U protobuf</code>

- Når du har kommet gjennom READMEen i prosjektet kan du leke deg med farger, finne andre utsnitt eller se om du klarer å optimalisere litt, så du kan lage bilder med høyere oppløsning!
- Det skal også finnes en pakke som heter **tensorflow-gpu** som skal være raskere til å generere bilder.


### Noen fine lenker:
- Kul side som illustrerer "Iteration orbits" for forskjellige verdier av C.
- Side som forklarer noen forskjellige algoritmer: https://www.math.univ-toulouse.fr/~cheritat/wiki-draw/index.php/Mandelbrot_set
