Bonjour à tous,
J’ai imaginé un concept d’ordinateur moderne 100 % 8‑bit, basé sur le C64, mais respectueux du C64 classique.
Je ne suis pas programmeur, juste passionné.
Voici ma vision du C64‑NEXT :



📘 C64‑NEXT — Concept global (version 8‑bit)
Un ordinateur moderne, open source, 100 % 8‑bit, fidèle au C64 classique

🧭 1. Vision générale
Le C64‑NEXT est un concept d’ordinateur moderne basé sur le Commodore 64, conçu pour :
• 	préserver intégralement le C64 classique
• 	offrir un mode NEXT entièrement 8‑bit
• 	utiliser un ARM uniquement comme coprocesseur externe, jamais comme CPU
• 	rester open source
• 	respecter l’esthétique et l’esprit Commodore
Le C64‑NEXT n’est pas un PC, pas un émulateur, pas un Raspberry déguisé.
C’est un véritable ordinateur 8‑bit, pensé pour 2026.

🟦 2. Le C64 classique (zone sacrée, intouchable)
Le mode C64 classique est figé, authentique, préservé.
Caractéristiques :
• 	CPU 6510 (ou cœur FPGA 8‑bit)
• 	ROM BASIC V2 originale
• 	ROM KERNAL originale
• 	VIC‑II strict
• 	CIA strict
• 	64 Ko de RAM
• 	timings identiques
• 	ports DB9
• 	port cartouche
• 	Datassette
• 	sortie vidéo rétro
Interdictions :
En mode C64, rien de moderne n’existe :
• 	pas d’ARM
• 	pas de SSD
• 	pas de Wi‑Fi
• 	pas de Bluetooth
• 	pas de RAM étendue
• 	pas de VIC‑NEXT
Le C64 classique reste le C64, point final.

🟥 3. Le processeur ARM (coprocesseur, jamais CPU)
Le C64‑NEXT inclut un ARM, mais son rôle est strictement limité.
En mode C64 :
• 	ARM désactivé
• 	invisible
• 	aucune accélération
• 	aucune interaction
En mode NEXT :
L’ARM sert uniquement à :
• 	gérer le Wi‑Fi / Bluetooth
• 	gérer le SSD
• 	charger des fichiers
• 	fournir des services modernes
• 	exécuter des tâches lourdes hors du CPU 8‑bit
Le 6510 reste le seul CPU.
Le NEXT reste une machine 8‑bit.

🟩 4. Le mode C64‑NEXT (8‑bit étendu, open source)
Le mode NEXT est un super‑C64, mais toujours 8‑bit.
Extensions 8‑bit :
• 	VIC‑NEXT : graphismes étendus, haute résolution, sprites modernes
• 	RAM étendue : plusieurs Mo accessibles via banques 8‑bit
• 	SID‑NEXT : plus de voix, filtres améliorés
• 	BASIC‑NEXT : commandes graphiques, réseau, fichiers
• 	GEOS‑NEXT : bureau moderne 8‑bit
• 	drivers 8‑bit
• 	API 8‑bit pour le SSD, Wi‑Fi, BT
Le CPU reste :
• 	un 6510
• 	ou un cœur compatible 100 % 8‑bit
Le NEXT n’est pas un ARM déguisé.
C’est un C64 augmenté, mais toujours 8‑bit.

🟧 5. BIOS NEXT (8‑bit + ARM en support)
Le BIOS NEXT :
• 	initialise le matériel
• 	propose un menu de démarrage
• 	masque les extensions en mode C64
• 	active les extensions en mode NEXT
• 	communique avec l’ARM via un protocole 8‑bit
• 	reste open source
Le BIOS est écrit pour le CPU 8‑bit.
L’ARM n’est qu’un assistant, jamais un maître.

🟨 6. Séparation stricte entre C64 et NEXT
Mode C64 :
• 	extensions NEXT désactivées
• 	ARM inactif
• 	registre de mode = 0
Mode NEXT :
• 	extensions activées
• 	ARM actif en arrière‑plan
• 	registre de mode = 1
Le passage au NEXT est volontaire.

💾 7. Stockage
Carte SD (FAT32)
• 	utilisée en mode C64
• 	lecteur 1541 virtuel
• 	chargement PRG, D64, CRT
SSD interne
• 	utilisé en mode NEXT
• 	accessible via API 8‑bit
• 	géré par l’ARM en arrière‑plan

🖱️ 8. Périphériques
Classiques :
• 	DB9
• 	souris 1351
• 	cartouches
• 	Datassette
• 	vidéo rétro
Modernes (via ARM) :
• 	HDMI
• 	USB
• 	Wi‑Fi
• 	Bluetooth
• 	souris modernes
• 	SSD M.2
Le CPU 8‑bit reste maître, l’ARM sert d’interface.

🎨 9. Design extérieur
Coque :
• 	style breadbin modernisé
• 	beige, noir, transparent
• 	logo C64‑NEXT rétro‑futuriste
Clavier :
• 	mécanique
• 	touches C64
• 	PETSCII imprimé
• 	rétro‑éclairage optionnel
• 	touches modernes discrètes

🌍 10. Open Source
Tout ce qui concerne le NEXT est open source :
• 	BIOS NEXT
• 	KERNAL‑NEXT
• 	BASIC‑NEXT
• 	GEOS‑NEXT
• 	drivers
• 	documentation
• 	schémas matériels (si possible)
Le C64 classique reste protégé.

📜 11. Règles du projet
1. 	Le C64 classique est intouchable.
2. 	Le NEXT est 100 % 8‑bit.
3. 	L’ARM n’est jamais un CPU principal.
4. 	Les deux mondes ne se mélangent pas.
5. 	Le NEXT est open source.
6. 	Le C64 reste authentique.

⭐ 12. Conclusion
Le C64‑NEXT est un concept d’ordinateur moderne 100 % 8‑bit, respectueux du C64 classique, mais ouvert à l’innovation.
Il combine :
• 	fidélité
• 	modernité
• 	simplicité
• 	open source
• 	passion
C’est une vision pour imaginer ce que pourrait être un C64 en 2026…
sans jamais trahir son âme.
