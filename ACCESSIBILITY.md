# Accessibility at Levl / Accessibilité de Levl

Levl is designed so its common tasks can be completed with VoiceOver, Voice Control, the
keyboard, and macOS display accommodations.

## Accessibility features in Levl 1.3

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
The core mixer is available free; Pro adds optional monthly, annual, and lifetime features. The Pro
offer, purchase, restore, and subscription-management flows are part of the release candidate and
require manual validation on the shipping binary before they are treated as confirmed accessibility
coverage.
Levl has no advertising, account system, or tracking. Eligible Early Supporters keep Pro for life,
based on a verified Apple transaction.

Each release must be manually validated on the shipping binary with the corresponding macOS
assistive technology before its App Store accessibility declarations are treated as confirmed.
Automated tests and Accessibility Inspector are supporting evidence, not a substitute for that
validation.

The App Store Larger Text label is not available for macOS. Levl contains no bundled spoken audio,
video, cutscenes, or other time-based editorial media, so Captions and Audio Descriptions don't
apply to the app's own content.

Levl processes other apps' audio in real time and in memory to apply volume, mute, routing, and
level metering. It does not record, persist, or transmit that audio. Live level meters are
supplemental; their corresponding sliders remain standard, labeled controls.

Levl 2's distinct Pro recorder can persist only the screen and audio sources a user explicitly
selects after starting a recording. Its source selection, countdown, pause, stop, draft recovery,
and export controls have names, states, focus handling, and reduced-motion alternatives in the
release candidate. This complete recorder task remains pending manual validation with VoiceOver,
Voice Control, and Full Keyboard Access on the shipping binary, so it isn't yet included in an
App Store accessibility declaration.

To report an accessibility issue, email
[theomarie@protonmail.com](mailto:theomarie@protonmail.com) and include your macOS version, the
assistive technology used, and the task affected.

---

Levl est conçu pour que ses tâches courantes soient réalisables avec VoiceOver, le Contrôle vocal,
le clavier et les adaptations d'affichage de macOS.

## Fonctions d'accessibilité dans Levl 1.3

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
Le mixeur essentiel est disponible gratuitement ; Pro ajoute des fonctions mensuelles, annuelles
ou à vie. L'offre Pro, l'achat, la restauration et la gestion de l'abonnement font partie de la
release candidate et doivent être validés manuellement sur le binaire distribué avant d'être
considérés comme une couverture d'accessibilité confirmée.
Levl ne comporte ni publicité, ni compte, ni suivi. Les Early Supporters éligibles conservent Pro à
vie, sur la base d'une transaction Apple vérifiée.

Chaque version doit être validée manuellement sur le binaire distribué avec la technologie
d'assistance macOS correspondante avant de considérer ses déclarations d'accessibilité App Store
comme confirmées. Les tests automatisés et Accessibility Inspector complètent cette validation
sans la remplacer.

Le label App Store **Texte plus grand** n'est pas disponible pour macOS. Levl ne contient ni parole,
ni vidéo, ni cinématique, ni autre contenu éditorial temporel intégré ; les labels **Sous-titres**
et **Descriptions audio** ne s'appliquent donc pas au contenu propre de l'app.

Levl traite en mémoire et en temps réel l'audio des autres apps pour appliquer le volume, le
silence, le routage et les niveaux. Il ne l'enregistre, ne le conserve et ne le transmet pas. Les
vumètres sont complémentaires ; les curseurs associés restent des commandes standard libellées.

L'enregistreur Pro distinct de Levl 2 ne peut conserver que l'écran et les sources audio choisis
explicitement après le démarrage d'une capture. Dans la release candidate, la sélection de source,
le décompte, la pause, l'arrêt, la récupération du brouillon et l'export disposent de noms, états,
gestion du focus et alternatives en cas de réduction des animations. Ce parcours complet reste à
valider manuellement avec VoiceOver, le Contrôle vocal et l'Accès complet au clavier sur le binaire
distribué ; il n'est donc pas encore inclus dans une déclaration d'accessibilité App Store.

Pour signaler un problème d'accessibilité, écrivez à
[theomarie@protonmail.com](mailto:theomarie@protonmail.com) en précisant votre version de macOS,
la technologie d'assistance utilisée et la tâche concernée.
