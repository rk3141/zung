![Slide 16_9 - 11](https://user-images.githubusercontent.com/63385587/135715306-c4e82b5c-bdbb-40e0-8646-b0928e47de08.png)

# Zung

## _क्या आपकी संकेत-लिपि मे ज़ंग है?_

Would you like to try something different, in an exotic and funny-sounding language?
Would you want to bring some Hindi touch to your programs?

**zung** (Hindi for _Rust_) is here to save your day, as it allows you to
write Rust programs in Hindi, using Hindi keywords, Hindi function names,
Hindi everything.

You don't like the vibes of built-in translation? Don't worry! Open a issue about it, make a PR, and have another translation in your "zung" vocab.
Or Hindi Rust is fully compatible with Vanilla Rust, so you can have a nice hindi-english smoothie of a program.

### Purpose

Maybe making a operating system (I am looking at you, future contributors) with hindi code or flexing off ur code in hindi, idk.

<!--
Here's an example of what can be achieved with Zung:

### trait and impl (aka convention et réalisation)

```rust
rouille::rouille! {
    utilisons std::collections::Dictionnaire comme Dico;

    convention CléValeur {
        fonction écrire(&soi, clé: Chaine, valeur: Chaine);
        fonction lire(&soi, clé: Chaine) -> PeutÊtre<&Chaine>;
    }

    statique mutable DICTIONNAIRE: PeutÊtre<Dico<Chaine, Chaine>> = Rien;

    structure Concrète;

    réalisation CléValeur pour Concrète {
        fonction écrire(&soi, clé: Chaine, valeur: Chaine) {
            soit dico = dangereux {
                DICTIONNAIRE.prendre_ou_insérer_avec(Défaut::défaut)
            };
            dico.insérer(clé, valeur);
        }
        fonction lire(&soi, clé: Chaine) -> Résultat<PeutÊtre<&Chaine>, Chaine> {
            si soit Quelque(dico) = dangereux { DICTIONNAIRE.en_réf() } {
                Bien(dico.lire(&clé))
            } sinon {
                Arf("fetchez le dico".vers())
            }
        }
    }
}
`-->

### Support for regional dialects

Not there yet, feel free to open a issue. :'(

### Other examples

See the [example](./examples/src/main.rs) to get a rough sense of the whole
syntax. बस इतना ही.

## Contributions

First of all, _धन्यवाद, शुक्रिया_ for considering participating to this joke, ~~The future users of operating system written in hindi rust~~ will thank you later! Feel free to throw in words from your own dialects in as well, and open a pull-request against the `mukhya` (Hindi for
`main`) branch.

Please don't introduce swear words, we arent supposed to be rude programmers.

## but why would you do zat

- horsin around
- playing with raw proc macros
- Fulfilling my wish of programming in hindi one day.

## Other languages

- Dutch: [roest](https://github.com/jeroenhd/roest)
- German: [rost](https://github.com/michidk/rost)
- Polish: [rdza](https://github.com/phaux/rdza)
- Italian: [ruggine](https://github.com/DamianX/ruggine)
- French: [rouille](https://github.com/bnjbvr/rouille)

## License

[WTFPL](http://www.wtfpl.net/).
