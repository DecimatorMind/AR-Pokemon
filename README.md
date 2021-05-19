[![](https://img.shields.io/github/followers/DecimatorMind?label=Follow&style=social)](https://www.github.com/DecimatorMind)

<img src = "https://img.shields.io/badge/Author-Pranjal_Bhardwaj-green"> <img src = "https://img.shields.io/badge/IDE-Xcode-blue"> <img src = "https://img.shields.io/badge/Language-Swift-orange">

# AR-Pokemon

An AR Pokemon Card displayer that displays Pokemons by detecting them and rendering them in 3D.

# How To Use

You first need to get Pokemon Card of your choice.
Initially there are two pokemons - oddish and eevee.
For your custom pokemon other than these, you need to get an scnobject of the pokemon.
Add the picture of the pokemon card to the xcassets.assets.
Measure card's dimensions and add them to the card's attribute inspector.
Add custom scn objects in the art.scnassets folders and change the names in the ViewController.swift folder.
Now when the card is identified , the pokemon should be displayed in 3D on the card.
