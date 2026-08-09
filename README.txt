ÉCHECS V2.1 — DESIGN BOIS — FIX

Cette version repart exactement de la V1-REBUILD qui se lançait correctement.
Le moteur et les IDs HTML fonctionnels sont conservés.

Correction du bug V2 :
- le précédent index.html ne contenait plus les IDs aiBtn / localBtn / onlineBtn
  attendus par script.js, donc JavaScript plantait dès l'initialisation.
- V2.1 conserve tous les IDs fonctionnels.
- nouveau design brun/crème inspiré de la référence fournie.
- pièces forcées en rendu texte homogène pour éviter les pions noirs type emoji.

Firebase :
- Authentication anonyme doit être activée.
- conserver/ajouter les règles chessRooms de firebase-rules.json.
