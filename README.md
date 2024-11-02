# ES-3 Planification

L'expérience se déroule dans une pièce sombre, entourée de rideaux noirs, avec trois micros suspendus au plafond. En s'approchant d'un micro, un spotlight s'allume, mettant l'utilisateur en lumière. En prenant la parole, sa voix est déformée, créant une expérience immersive qui explore l'anxiété de performance et les tensions liées à l'expression personnelle.

## Synoptique
```mermaid
flowchart TD
    subgraph Plafond
    A[Alimentation] --> B[Microphone]
    A --> G
    A --> D[Détecteur de présence]
    A --> F[Hauts-parleurs]
    end

    subgraph Derrière rideaux
    C --> F
    G[Spotlight] --> H[Ordinateur]
    B --> C[Carte de son]
    C --> H
    D --> H
    end
```

## Plantation

## Simulation
<img src="./images/simulation_1.jpg" width="400"/> <img src="./images/simulation_2.jpg" width="400"/> <img src="./images/simulation_3.jpg" width="400"/> <img src="./images/simulation_4.jpg" width="400"/> <img src="./images/simulation_5.jpg" width="400"/>

## Scénarimage
<img src="./images/scenarimage_legende.png" width="150"/>

<img src="./images/scenarimage_1.jpg" width="500"/> <img src="./images/scenarimage_2.jpg" width="500"/> <img src="./images/scenarimage_3.jpg" width="500"/> <img src="./images/scenarimage_4.jpg" width="500"/> <img src="./images/scenarimage_5.jpg" width="500"/>

## Devis Technique

### Matériels

#### Founi par l'école
- 3 Microphones cardioïdes Shure SM57
- 3 Détecteurs de présence
- 4 Haut-parleurs
- 3 Spotlights ellipsoïdals
- Carte de son
- Ordinateur

### Logiciels

#### Founi par l'artiste
- Reaper

#### Founi par l'école
- QLC +
- Max

### Mise en réseau et de communication
Les dispositifs communiqueront entre eux via DMX et Loop MIDI.
