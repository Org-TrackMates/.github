# Contribuer

## Les règles de tous les dépôts

- **L'anglais et [gitmoji](https://gitmoji.dev) pour les messages de
  commit** : un emoji qui nomme l'intention, puis un résumé à l'impératif
  (`✨ Add …`, `🐛 Fix …`, `📝 Document …`), et un corps qui dit pourquoi.
- **Le français** pour les pull requests et les échanges ; **l'anglais** pour
  le code, ses commentaires et les fichiers `CLAUDE.md`.
- **Une PR, un sujet.** Elle s'ouvre en brouillon, est assignée au
  responsable du dépôt pour sa review, et n'est fusionnée qu'avec son accord.
  Son modèle demande ce qui change, pourquoi, comment c'est vérifié, et ce
  qu'il reste à faire après la fusion.
- **Un message de commit dit pourquoi**, pas seulement quoi : le contexte, la
  décision, ce qui a été mesuré.
- **Jamais un secret dans le dépôt** — une clé, un jeton, une adresse de base
  de données : ni dans le code, ni dans un commit, ni dans un journal de CI.
- **`CLAUDE.md` dit ce qui tient aujourd'hui.** Un changement qui modifie une
  règle la corrige sur place ; l'histoire va dans le commit ou la PR.
- **Les tests gardent des décisions**, surtout celles dont l'échec serait
  silencieux. Un test qui ne garde rien est supprimé.
- **Une dépendance est une décision**, écrite dans la PR qui l'ajoute. Aucune
  version publiée depuis moins de 14 jours n'est installée.
- **Une version se publie par un tag** `v<version>`, poussé par le
  responsable du dépôt.

## Démarrer un nouveau dépôt

Partir du modèle de son langage (`paddock-template-typescript`,
`paddock-template-rust`, `paddock-template-nextjs`), avec le bouton **Use this
template**, puis suivre la section « Partir de ce modèle » de son README.
