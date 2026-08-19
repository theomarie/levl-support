# Accessibility at Levl / Accessibilité de Levl

Levl is designed so its common tasks can be completed with VoiceOver, Voice Control, the
keyboard, and macOS display accommodations.

## Accessibility features implemented in Levl 1.2.1

- **VoiceOver:** controls expose concise names, values, states, and a logical reading order.
- **Voice Control:** visible wording and contextual input labels identify actions unambiguously.
- **Dark Interface:** common tasks remain available in the native dark appearance.
- **Differentiate Without Color Alone:** text, symbols, shape, and state accompany color cues.
- **Sufficient Contrast:** semantic macOS colors adapt to light, dark, and increased-contrast modes.
- **Reduced Motion:** nonessential motion and continuous meter updates are reduced when the macOS
  setting is enabled.
- **Keyboard navigation:** menus, sliders, buttons, toggles, and scene actions support Full Keyboard
  Access where macOS exposes it.

Levl's accessibility implementation addresses first launch, audio permission, the menu-bar mixer,
master and per-app audio controls, outputs, scenes, automation, error recovery, and settings.

Each release must be manually validated on the shipping binary with the corresponding macOS
assistive technology before its App Store accessibility declarations are treated as confirmed.
Automated tests and Accessibility Inspector are supporting evidence, not a substitute for that
validation.

The App Store Larger Text label is not available for macOS. Levl contains no spoken audio, video,
cutscenes, or other time-based editorial media, so Captions and Audio Descriptions do not apply.

Levl processes other apps' audio in real time and in memory to apply volume, mute, routing, and
level metering. It does not record, persist, or transmit that audio. Live level meters are
supplemental; their corresponding sliders remain standard, labeled controls.

To report an accessibility issue, email
[theomarie@protonmail.com](mailto:theomarie@protonmail.com) and include your macOS version, the
assistive technology used, and the task affected.

---

Levl est conçu pour que ses tâches courantes soient réalisables avec VoiceOver, le Contrôle vocal,
le clavier et les adaptations d'affichage de macOS.

## Fonctions d'accessibilité mises en œuvre dans Levl 1.2.1

- **VoiceOver :** les commandes exposent des noms, valeurs et états concis dans un ordre logique.
- **Contrôle vocal :** les textes visibles et libellés contextuels identifient chaque action sans
  ambiguïté.
- **Interface sombre :** les tâches courantes restent disponibles dans l'apparence sombre native.
- **Différencier sans la couleur seule :** texte, symboles, forme et état accompagnent les couleurs.
- **Contraste suffisant :** les couleurs sémantiques de macOS s'adaptent aux apparences claire,
  sombre et au contraste accru.
- **Réduire les animations :** les mouvements non essentiels et la fréquence des vumètres sont
  réduits lorsque le réglage macOS est activé.
- **Navigation au clavier :** menus, curseurs, boutons, interrupteurs et actions sur les scènes
  prennent en charge l'Accès complet au clavier lorsque macOS l'expose.

Le travail d'accessibilité de Levl porte sur le premier lancement, l'autorisation audio, le mixeur
de la barre des menus, les commandes audio principales et par app, les sorties, les scènes,
l'automatisation, la récupération après erreur et les réglages.

Chaque version doit être validée manuellement sur le binaire distribué avec la technologie
d'assistance macOS correspondante avant de considérer ses déclarations d'accessibilité App Store
comme confirmées. Les tests automatisés et Accessibility Inspector complètent cette validation
sans la remplacer.

Le label App Store **Texte plus grand** n'est pas disponible pour macOS. Levl ne contient ni
parole, ni vidéo, ni cinématique, ni autre contenu éditorial temporel ; les labels **Sous-titres**
et **Descriptions audio** ne s'appliquent donc pas.

Levl traite en mémoire et en temps réel l'audio des autres apps pour appliquer le volume, le
silence, le routage et les niveaux. Il ne l'enregistre, ne le conserve et ne le transmet pas. Les
vumètres sont complémentaires ; les curseurs associés restent des commandes standard libellées.

Pour signaler un problème d'accessibilité, écrivez à
[theomarie@protonmail.com](mailto:theomarie@protonmail.com) en précisant votre version de macOS,
la technologie d'assistance utilisée et la tâche concernée.
