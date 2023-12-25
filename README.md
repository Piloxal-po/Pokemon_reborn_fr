# Pokemon_reborn_fr
Traduction de pokemon reborn fr

# EN

Here is the difference between the original version and the FR version: https://github.com/Piloxal-po/Pokemon_reborn_fr/compare/reborn_fr/base...main

## Current status

The translation hasn't been tested yet, but I'm planning to play a game with it myself, so if you want to play with it, save regularly.

### How has it been translated?

#### Deepl API

Most of the text in Pokémon Reborn has been translated using the [Deepl API](https://github.com/DeepLcom/deepl-python), which is an AI-powered translation tool.

As the translation has been automated, the French may be shaky. So far, it's only taken me 4 days to get this version out, with around 20 hours spent on it, so it's a very short time compared with what a real translation can take.

#### POKE API

I used the [Poke API](https://pokeapi.co/docs/v2) for items, pokemons, attacks and abilities.

#### Error-finding algorithm

I've tried to implement error-finding algorithms in the text to correct as many errors as possible.

When I say errors, I don't mean French errors, but format errors.

For example, to display the player's name in a text, Pokemon Reborn uses this

So I ran some algorithms to see if \PN existed in the original text and if it was still present in the translated text.

I'm sure there are still some format errors in addition to the French ones. But I did remove more than 1,000 or even 2,000 errors by hand.

## Future ideas

### Externalization
For the moment, I'm modifying the Pokémon Reborn code directly, but my long-term goal is to make it an external mod that can be added as you wish. I don't know if that's possible, but that's the ambition.

# FR

Voici la différence entre la version originelle et la version FR : https://github.com/Piloxal-po/Pokemon_reborn_fr/compare/reborn_fr/base...main

## Etat actuel

La traduction n'a pas encore été testée, je compte faire une partie de mon côté avec cette traduction, donc si vous voulez jouer avec, sauvegardez régulièrement.

### Comment ça a été traduit ? 

#### API Deepl

La majorité du texte de Pokémon Reborn a été traduit par [l'API de Deepl](https://github.com/DeepLcom/deepl-python), qui est un outil de traduction utilisant l'IA.

Comme la traduction a été automatisée, le français peut être bancal. J'ai pour le moment mis seulement 4 jours pour sortir cette version avec environ 20 h passées dessus, donc très peu de temps comparé à ce que peut prendre une véritable traduction.

#### POKE API

Pour les items, pokemon, attaque, abilité j'ai utilisé [Poke API](https://pokeapi.co/docs/v2)

#### Algorithme de recherche d'erreur

J'ai essayé de mettre en place des algorithmes de recherche d'erreur dans le texte pour corriger au maximum les erreurs dans le texte.

Quand je parle d'erreur, je ne parle pas d'erreur de français, mais bien d'erreur de format.

Par exemple, pour afficher le nom du joueur dans un texte, Pokemon Reborn utilise ceci `\PN`

J'ai donc fait des algorithmes qui regardent s'il existait `\PN` dans le texte original et s'il était toujours présent dans le texte traduit.

Il y a sûrement encore des erreurs de format en plus des erreurs de français. Mais, j'ai bien retiré plus de 1000 voire 2000 erreurs à la main.

## Idées futures

### Externalisation

Pour le moment, je modifie directement le code de Pokémon Reborn, mon but à terme est de faire en sorte que ça soit un Mod externe qui puisse s'ajouter comme on le veut, j'ignore si c'est possible, mais c'est l'ambition voulue.