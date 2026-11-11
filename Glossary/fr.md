# Translation Glossary — French (fr)

Terminologie française pour l’interface et les fonctions de BetterDisplay.

## Conventions

- Conserver BetterDisplay, Apple, Metal, HiDPI, LoDPI, HDR, SDR, XDR, EDID, DisplayID, DDC, CLI et les identifiants techniques.
- Unités : bits, octets, Hz, nits ; conserver les paramètres de substitution et les liens. Profondeur de couleur affichée comme valeur technique : « 8-bit », « 10-bit » (sans « s », comme dans les spécifications et menus d’appareils).
- Les noms identiques en français et en anglais, unités, noms de produits et sigles techniques sont volontairement conservés.
- Orthographe : réappliquer, redétecter ; conserver le nom de version macOS Sequoia sans accent ajouté.
- « App » et « application » sont tous deux admis (Apple emploie les deux) : « app » de préférence dans les libellés courts (menus, boutons, barre des menus), « application » dans les phrases ; ne pas mélanger les deux dans une même chaîne.
- Pourcentages : séparer le nombre du symbole par une espace insécable (100 %) ; préserver les rapports techniques tels que 1:1 et 4:2:0.

## Terminology

| English | French | Notes |
| --- | --- | --- |
| Apple Display Preset | préréglage d’écran Apple | Sans le restreindre aux seuls écrans XDR. |
| Auto Calibrate | Auto Calibration | Conservé en anglais (nom de la méthode). |
| Bass Boost | Boost des graves | Terme usuel en audio grand public. |
| brightness upscaling | upscaling (de la luminosité) | Anglicisme d’usage courant chez les techniciens et dans la presse spécialisée. « Démultiplication » est peu clair (en mécanique, il désigne surtout une réduction). Ne pas confondre avec l’upscaling de résolution : préciser « de la luminosité » si le contexte est ambigu. |
| channel trim | gain du canal | « Gain du canal gauche / droit ». |
| checksum | contrôle (checksum) | Garder « checksum » entre parenthèses, terme technique courant en français. |
| color depth | profondeur de couleur | |
| configuration protection | protection de la configuration | |
| crash report | rapport de crash | Plus courant que « rapport de plantage ». |
| crop area | zone de recadrage | « Largeur de recadrage » / « Hauteur de recadrage » quand le contexte rend « zone » superflu. |
| display | écran | Moniteur pour distinguer un appareil physique lorsque le contexte l’exige. |
| Display Cutout | encoche | Terme d’Apple pour l’encoche de l’écran (« notch »). |
| display preset | préréglage d’écran | |
| dithering | dithering | « Tramage » est rarement employé par les techniciens et les médias spécialisés. À discuter. |
| duplicate | Dupliquer | Action ; Copie dans le nom proposé d’un groupe dupliqué. |
| Error Reporting | Rapport d’erreurs | |
| fixed-point | valeur brute | Dans les informations de mode d’affichage (« Fréquence de rafraîchissement brute »). « En virgule fixe » reste exact mais trop littéral pour l’utilisateur. |
| flipped | Retourner (l’écran) ; Inverser largeur et hauteur | « Retourner » pour l’action côté utilisateur, les opérations sur un écran relevant surtout de la rotation ; préciser « (inverser largeur et hauteur) » quand seules les dimensions configurées sont permutées. |
| framebuffer | framebuffer | |
| Gate Attack / Hold / Release | Attaque / Maintien / Relâchement (Gate) | Termes de traitement audio ; « Gate » conservé, rarement traduit (« porte » est à éviter). |
| GPU | processeur graphique (GPU) | |
| Home button | bouton Home | Nom conservé, comme chez Apple. |
| HW (hardware) | HW | Abréviation conservée dans les libellés courts (« HW max. », « HW min. »). |
| Loudness | Loudness | Terme technique utilisé tel quel en français ; « correction physiologique » est obsolète. « Compensation du Loudness ». |
| LUT | LUT | Féminin (une table de correspondance) : LUT 3D, LUT HDR ; importer/exporter une LUT. |
| mapping | mapping | Terme technique courant (« mapping des valeurs DDC »). |
| mirroring | recopie (vidéo) ; verbe : recopier ; adj. : recopié | Terminologie d’Apple depuis des années (« Recopie vidéo », « Recopie de l’écran » dans macOS/iOS et la documentation). « Mise en miroir » est la formulation de Windows. Destination : « Recopier dans l’écran X ». |
| mute | mise en sourdine | Voir la discussion ci-dessous pour mute/unmute. |
| notch (audio filter) | filtre (coupe-bande) | « Fréquence du filtre » ; « coupe-bande » seulement si le contexte l’exige. Ne pas confondre avec l’encoche de l’écran. |
| pairing prompt | demande d’appairage | Pas « prompt ». |
| PiP (Picture in Picture) | image dans l’image (PiP) | Terme d’Apple ; « PiP » ajouté entre parenthèses, Apple l’employant aussi dans sa documentation. |
| polling | lecture périodique | |
| preset (audio/égaliseur) | préréglage | Pas « station mémorisée ». |
| refresh rate | fréquence de rafraîchissement | Taux de rafraîchissement également conservé dans les textes existants corrects. |
| scaling | mise à l’échelle | |
| screen | écran | |
| service menu | menu de service | |
| settings | réglages | |
| Sidecar | Sidecar | Ne pas traduire en « side-car ». |
| slider | slider | Terme courant en interface ; « curseur » reste admis. |
| soft connect | connexion par logiciel | Éviter « en douceur ». |
| soft disconnect | déconnexion par logiciel | Éviter « en douceur ». |
| Software Update | Mise à jour | |
| Start/Stop | Start/Stop | Conservé dans les libellés courts. |
| streaming | diffusion | |
| switch (on/off) | switch on/off | |
| System Settings | Réglages Système | |
| temporal dithering | dithering temporel | Voir « dithering ». |
| timeout | délai d’expiration | |
| Tools menu | menu Utilitaire | Au singulier, comme le nom du menu dans l’app. |
| unlicensed | sans licence | |
| unlock | déverrouiller | |
| unmute | désactivation de sourdine | Voir la discussion ci-dessous. |
| unsafe mode | mode non sécurisé | Sans trait d’union (« non » devant un adjectif). |
| vendor | fabricant | Dans les identifiants d’écran. |
| vignette | vignettage | Filtre. |
| virtual screen | écran virtuel | |
| Wake-on-LAN | Wake-on-LAN | Nom conservé. |

## À discuter

- **UI scale matching** : plusieurs variantes selon le contexte (« Correspondance de la taille de l’interface », « Uniformiser les échelles d’interface du groupe », « mise à l’échelle automatique de l’interface »). « Correspondance » sonne comme un calque de l’anglais ; faut-il fixer un terme unique ou admettre des variantes selon l’emplacement ?
- **mute / unmute** : « mise en sourdine », « désactivation de sourdine », « on/off du son ». « Sourdine » est lourd ; beaucoup de professionnels disent « muter / démuter », absent des dictionnaires. Même question : terme unique ou variantes ?
- **dithering** : « tramage temporel » (entrée précédente) est peu employé par les techniciens et les médias ; proposition de garder « dithering ».
