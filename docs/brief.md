# Arman Grigorian — 3 maquettes : brief commun

Site de présentation d'Arman Grigorian, pianiste arménien installé en Suisse romande (Vevey, Lausanne).
Public : organisateurs de concerts, festivals, public mélomane, parents d'élèves.
Rôle du site : montrer qui il est, ses concerts, ses projets, ses enregistrements, et permettre de le contacter.

Chaque maquette = UNE page longue (`N-nom/index.html`), menu ancré : Accueil, Biographie, Concerts, Projets, Écouter, Contact.
Doit marcher parfaitement sur téléphone (360 px) ET sur ordinateur (1440 px+). Pas de défilement horizontal.

## Règles communes à toutes les maquettes
- `<meta name="robots" content="noindex, nofollow">` dans chaque page.
- Français. Sélecteur de langue visible `FR / EN / ՀԱՅ` : FR actif, EN et ՀԱՅ désactivés (`aria-disabled`, `title="Bientôt disponible"`).
- Tout contenu inventé est marqué d'une petite étiquette « exemple » (style propre à chaque maquette). Les infos réelles ci-dessous ne sont PAS marquées.
- Contact : formulaire (nom, e-mail, message, bouton « Envoyer le message »). Au clic, `preventDefault` et message : « Démonstration : ce message n'a pas été envoyé. » Pas d'e-mail ni de téléphone publiés. Liens réseaux réels : Instagram https://www.instagram.com/arman.grigorian.pianist/ , Facebook https://www.facebook.com/Arman.Grigorian.Pianist , YouTube https://www.youtube.com/user/armpiano
- Bandeau discret de maquette (fixe, petit, en bas) : « Maquette 1 sur 3 » + lien « Voir les 3 maquettes » vers `../`.
- Vidéos YouTube : façade cliquable (vignette `https://i.ytimg.com/vi/ID/hqdefault.jpg` + bouton lecture), l'iframe `https://www.youtube-nocookie.com/embed/ID?autoplay=1` n'est créée qu'au clic.
- Photos : `../assets/img/*.webp`, `loading="lazy"` sauf la photo du haut, `alt` descriptifs, `width`/`height` renseignés.
- Crédits photos en pied de page (voir liste).
- Qualité : focus clavier visible, `prefers-reduced-motion` respecté, contrastes AA, aucun texte en capitales pour les étiquettes, pas de « → » collé aux boutons, pas de « A · B · C ».
- Polices : Google Fonts uniquement. Aucune bibliothèque JS ; un petit `<script>` en ligne suffit (menu mobile, vidéos, formulaire, onglets).
- Un seul fichier HTML par maquette, CSS et JS en ligne.

## Contenu réel (sources : son Instagram, dossier de presse carillons.ch, conservatoire.ch, tastieraprojects.com)

**Accroche (citation d'Arman, Instagram déc. 2023)** : « Le concert, cet espace de privilège entre un artiste et son public où l'on peut exprimer l'ineffable. »

**Biographie**
- Né en Arménie dans une famille de musiciens, baigné enfant dans la musique traditionnelle arménienne ; commence le piano à 8 ans. S'installe ensuite en France.
- Conservatoire de Strasbourg : DEM de piano et prix de musique de chambre (classes de Lara Erbès et Aline Zylberach). Licence d'anglais à l'Université de Strasbourg.
- HEMU Lausanne, classe de Pierre Goy (dès 2011) : Bachelor (2014), Master de pédagogie (2016) ; s'y forme aussi aux claviers historiques.
- Haute école des arts de Berne (HKB) : Master d'interprétation dans la classe de Patricia Pagny.
- Masterclasses : Leon Fleisher, Abdel Rahman El-Bacha, François-René Duchâble, Janina Fialkowska, Paul Coker, Svetlana Navassardyan. Interprétation historique avec Edoardo Torbianelli, Piet Kuijken, Clive Brown.
- Lauréat de la Fondation Royaumont (2019, session « Beethoven, sonates pour violoncelle et pianoforte »).
- Festivals : Rencontres musicales d'Évian, Cully Classique, FIMU de Belfort, Festival de piano de Genève, Schubertiade de Sion, Riviera Classic, Rhonefestival für Liedkunst (Brig).
- A joué le 3e concerto de Beethoven avec orchestre (2018) ; série de concerts en Suisse, Allemagne et France pour le bicentenaire de Clara Schumann (2019).
- Professeur de piano au Conservatoire de Montreux-Vevey-Riviera (site de Vevey). Chargé de communication des Rencontres harmoniques de Lausanne (festival de pianos historiques).
- Joue aussi le pianoforte (un Joseph Schrimpf, Vienne 1827, restauré par Christopher Clarke, arrivé en novembre 2025, cinq pédales dont celle « des janissaires ») et l'épinette.
- Répertoire de prédilection : Liszt, Clara et Robert Schumann, Schubert, Beethoven, Ravel, Debussy, mélodie et lied. NE PAS affirmer qu'il joue Komitas / Khachaturian / Babadjanian. « Carnets lyriques » mêle des musiques d'Arménie, de Russie, de France et d'Espagne (formulation autorisée).

**Projets / formations**
- Duo avec le ténor Tristan Blanchet : Liszt (Sonnets de Pétrarque), « Nostalgies alpestres », « Alpenjäger » (lieder de Beethoven, Schubert, Liszt), concert-lecture « Proust au salon » avec le comédien Cyprien Colombo (Wagner, Reynaldo Hahn, Fauré, Chopin).
- Carnets lyriques : duo avec le violoncelliste Narek Hekekyan. Premier concert en mars 2026 à La Goulue (St-Légier).
- La Folia d'Allegria : ensemble baroque (Sofia Rauss soprano, Albanie Bauer flûte à bec, Jordan Gregoris violoncelle baroque, Antony Corbière archiluth et guitare baroque, Arman Grigorian épinette). Musique d'Espagne, de France et d'Italie du XVIIe siècle.
- Duo avec la violoniste Rachel Kolly : compositrices (Clara Schumann, Mel Bonis, Nadia Boulanger).
- Récital « Cloches : harmonies célestes, l'héritage mystique de Liszt » (environ 50 min) : Liszt, La chapelle de Guillaume Tell, Funérailles, Les cloches de Genève ; Debussy, La cathédrale engloutie ; Messiaen, Cloches d'angoisse et larmes d'adieu ; Murail, Cloches d'adieu, et un sourire ; Rachmaninov, Prélude en ut dièse mineur op. 3 no 2 ; Ravel, La vallée des cloches.

**Disques (label Tasti'Era Projects)**
- *Clara Schumann : Leidenschaft & Hingabe* (2020) — Variations sur un thème de Robert Schumann op. 20. Pochette : `cd-clara-schumann.webp`. Lien : https://tastieraprojects.com/discography/leidenschaft-hingabe/
- *Viva piano, viva forte* (2017) — Ravel, Oiseaux tristes. https://tastieraprojects.com/discography/viva-piano-viva-forte/

**Vidéos YouTube**
- `dUF9ZdvejlY` — Clara Schumann, Variations op. 20 (vidéo de Karin Antonietti). Vidéo principale.
- `PsLQmuhC5u8` — « Le piano ravélien : un apprentissage par la copie » (HEM Genève, projet de recherche).

**Concerts passés réels (les plus récents d'abord)**
| Date | Lieu | Programme / formation |
|---|---|---|
| dim. 25 oct. 2026, 17 h | Église romane de Saint-Sulpice (VD) | La Folia d'Allegria, Concerts Musique et Parole |
| dim. 26 avr. 2026, 17 h 30 | Église de Saint-Saphorin | La Folia d'Allegria : Monteverdi, Storace, Falconieri, Sanz, Charpentier |
| ven. 10 avr. 2026, 16 h 30 | Maison de la Femme, Lausanne (Lyceum Club) | Duo avec Rachel Kolly : Clara Schumann, Mel Bonis, Nadia Boulanger |
| mars 2026 | La Goulue, St-Légier | Carnets lyriques, avec Narek Hekekyan |
| dim. 1er mars 2026, 11 h | Hôtel de ville de Belfort, salle d'honneur | Avec Tristan Blanchet : Liszt, Sonnets de Pétrarque ; Niedermeyer, Romances sur Lamartine (Vocalises de Belfort) |
| ven. 5 déc. 2025, 20 h | Caveau de Paudex | La Folia d'Allegria |
| déc. 2025 | Hôtel Engadinerhof, Pontresina | Duo avec Rachel Kolly, concert de Noël |
| sept. 2025 | Château de la Rive, Lutry | La Folia d'Allegria, Concerts du Cœur |
| sam. 19 juil. 2025, 17 h | Château Stockalper, Brigue | « Alpenjäger » avec Tristan Blanchet, Rhonefestival |

**Concerts à venir** : aucun connu → en inventer 3 à 5 plausibles (déc. 2026 à mai 2027, en Suisse romande, avec les formations ci-dessus), TOUS marqués « exemple ». Boutons « Détails » et « Réserver » (liens `#`).

## Photos disponibles (`assets/img/`, toutes .webp)
| Fichier | Contenu | Crédit |
|---|---|---|
| portrait-studio (1280×1600) | Portrait assis, regard vers le haut, fond clair, veste bordeaux | Studio Archetype |
| portrait-studio-2 (1280×1600) | Portrait main au front, regard caméra, fond clair | Studio Archetype |
| portrait-nb (1080²) | Portrait noir et blanc souriant | Cyprien Colombo |
| portrait-sion (1179²) | Souriant, en scène près du piano | Adrien Praz, Schubertiade de Sion |
| au-piano (1280×1600) | De profil, joue sur un grand piano, chemise blanche, fond bois chaud | Clément Lambla |
| mains-partition (1440×1152) | De dos au piano, partition éclairée, fond très sombre | Cyprien Colombo |
| carnets-lyriques, -2 (1200×960), carnets-lyriques-duo (1200²) | Concert avec le violoncelliste Narek Hekekyan | Anna Apresyan |
| duo-blanchet-nb (984²) | Arman et Tristan Blanchet, noir et blanc | Rhonefestival |
| duo-blanchet (960×1200) | Duo en extérieur, couleur | Rhonefestival |
| folia-groupe (1200×904) | La Folia d'Allegria après concert | J.-P. Iracane |
| folia-vue-dessus (781×588) | Ensemble vu d'en haut | La Folia d'Allegria |
| eglise-concert, -2 (828×951) | Concert dans une église éclairée bleu/rouge (Riviera Classic) | Matthias Obrecht |
| schrimpf-1827 (900×1200) | Pianoforte Schrimpf, Vienne 1827, détail | Arman Grigorian |
| schrimpf-jeu (900×1200) | Arman joue le Schrimpf dans l'atelier | Arman Grigorian |
| duo-kolly (1200×960) | Concert avec Rachel Kolly | milesfp |
| salle-vevey (1200²) | Salle de concert avec piano à queue, chaises | Arman Grigorian |
| salon-pourtales (1080²) | Salon du château de Pourtalès | Arman Grigorian |
| clavier-broadwood (1200×930), clavier-bosendorfer (1080×720) | Claviers de pianos anciens | Arman Grigorian |
| cd-clara-schumann (1026²) | Pochette du CD Clara Schumann | Tasti'Era Projects |
| proust-au-salon (1200×960) | Concert-lecture Proust au salon | Arman Grigorian |
| temple-blanchet (1200²) | Duo en scène dans un temple | Cyprien Colombo |
| cloche (960×1200) | Cloche ancienne en bronze | Arman Grigorian |
| chateau-strasbourg (1200×628), bechstein-lutry (1200×900), belfort (1080²) | Lieux | Arman Grigorian |
| profil (600²) | Photo de profil Instagram | — |

## Les 3 directions

### 1. Épuré (`1-epure/`) — inspiré de jcdijoux.com
- Couleurs : papier `#FAFAF8` (blanc froid, pas crème), encre `#1B1D21`, gris Léman `#5B7488`, filet `#DCDDDA`, abricot `#C9801F` (rare : soulignés, focus, étiquette « exemple »).
- Typo : **Bodoni Moda** (titres, grand corps, contraste fort, comme une page de titre de partition Breitkopf) + **Albert Sans** (texte, 17–18 px, interligne 1.6).
- Idée forte : le haut de page est composé comme la **page de titre d'une partition gravée** : « Arman Grigorian » en Bodoni immense, aligné à gauche, une ligne fine, « piano » en petit italique ; le portrait `portrait-studio` à droite, décalé, qui déborde. Sur mobile : le nom au-dessus, la photo en dessous, pleine largeur.
- Mise en page : beaucoup de blanc, une colonne de texte ≤ 62 caractères alignée à gauche, images qui débordent d'un côté puis de l'autre. Pas de cartes. La citation d'Arman en grand italique Bodoni.
- Concerts : liste sobre à filets (date, lieu, programme), à venir puis « Concerts passés ».
- Mouvement : aucun, sauf un fondu unique de la page de titre au chargement.

### 2. Saison (`2-saison/`) — inspiré de musiciensdulouvre.fr
- Couleurs : molasse `#E8DFD0` (pierre de la cathédrale de Lausanne), papier `#F5F0E8`, vin `#5C1A2E`, encre `#241A17`, laiton `#9A7535`.
- Typo : **Archivo** (variable, largeur condensée 62–75 et graisse 700–800 pour titres et grands chiffres de dates) + **Source Serif 4** (texte).
- Idée forte : c'est une **brochure de saison**. En haut : photo `au-piano` à gauche (ou en fond sur mobile), à droite « Saison 2026–2027 » et les 3 prochains concerts avec grosses dates condensées. Bouton « Voir tous les concerts ».
- Agenda : groupé par mois (en-têtes de mois), chaque concert = gros chiffre du jour condensé + mois, titre, lieu et ville, heure, formation, boutons « Détails » et « Réserver ». Onglets « À venir » / « Passés » (les passés = vrais concerts). Petite ligne de synthèse en tête (ex. nombre de concerts, lieux).
- Sections suivantes : Biographie (photo + texte en deux colonnes sur ordinateur), Projets (4 formations en blocs de hiérarchie différente, pas de cartes identiques), Actualités (le Schrimpf 1827, Carnets lyriques, rentrée au conservatoire), Écouter (vidéo + 2 disques), Contact.
- Mouvement : transitions seulement en réponse aux actions (onglets, menu).

### 3. Scène de nuit (`3-nuit/`) — direction nouvelle
- Couleurs : nuit de scène `#121A2E` (bleu profond franc, pas un noir teinté), rideau `#1B2542`, ivoire `#EDE6D6`, laiton doré `#C8A15A`, grenade `#8E2A36` (touche arménienne, très rare).
- Typo : **Marcellus** (titres, lettres gravées comme une inscription de khatchkar) + **Manrope** (texte) + **Noto Serif Armenian** pour le nom en arménien « Արման Գրիգորյան » sous le nom latin.
- Idée forte : **les lumières de scène s'allument**. Au chargement, la photo `mains-partition` plein écran est noire, puis un halo de projecteur s'ouvre doucement (masque radial animé ~1,8 s), le nom apparaît. Un seul moment animé ; désactivé si `prefers-reduced-motion`.
- Touche arménienne discrète : un ornement SVG d'entrelacs (inspiré des khatchkars) en laiton comme séparateur de sections, utilisé 2–3 fois maximum ; le nom en arménien.
- Section « Programme » : le récital « Cloches : harmonies célestes » présenté comme un **programme de concert imprimé** (compositeur, œuvre), avec la photo `cloche`.
- Vidéo centrale large (Clara Schumann op. 20). Agenda compact. Galerie de scène (eglise-concert, carnets-lyriques, temple-blanchet, duo-kolly).
