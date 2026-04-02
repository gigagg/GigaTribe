3.09.014 BETA (2026-04-02)
* Amélioration de la stabilité

3.09.013 (2026-04-01)
* Correction du tris des dossiers partagé par taille

3.09.012 (2026-03-31)
*   Active et améliore l'upload de fichiers dans un dossier partagé en écriture
*   Ajout du bouton "Lire" sur les vidéos en cours de téléchargement

3.09.010 (24-03-2026)
* Correction de plantages : Résolution d'un problème majeur lors de la modification de fichiers partagés.
* Amélioration des traductions : Affinement de la gestion des liens web et des paramètres pour les différentes langues.
* Améliorations Windows : Correction de plusieurs plantages spécifiques à Windows et optimisation de l'identification des chemins de fichiers.
* Stabilité générale : Corrections internes pour prévenir divers arrêts inattendus.

3.09.009 (20-03-2026)
* Nouvelle fonctionnalité : Ajout d'un paramètre pour choisir la fréquence de rescannage automatique de vos dossiers.
* Paramètres intelligents : Les modifications de l'intervalle de scan s'appliquent désormais immédiatement sans redémarrage.
* Améliorations de l'interface : Mise à jour des messages lors de la connexion aux utilisateurs principaux et uniformisation de l'outil de sélection de dossiers Windows.
* Gestion des connexions : Amélioration de la fermeture des connexions lors de l'utilisation des outils en ligne de commande.

3.09.008 BETA (17-03-2026)
* Maintenance : Améliorations mineures de la stabilité et nettoyage du code.

3.09.007 BETA (09-03-2026)
* Optimisation du scan :
    * Le scan est désormais plus rapide et consomme moins de ressources système.
    * Correction des problèmes de « gel » de l'application en déplaçant les mises à jour de fichiers hors du thread principal de traitement.
    * L'application empêche désormais l'exécution simultanée de plusieurs scans pour économiser de la mémoire.
* Polissage développeur : Amélioration de la prise en charge des builds Windows et nettoyage des dépendances de fichiers internes.
* Fiabilité : Ajout de tests plus rigoureux sur le comportement des dossiers afin de prévenir de futurs bugs.

3.09.006 BETA (2026-02-16)
- Dialogue d'écrasement optimisé — confirmation plus rapide et fluide lors du remplacement de fichiers.
- Affichage des tailles de dossiers — la taille des dossiers est maintenant affichée là où c'est pertinent.
- Mises à jour plus réactives de la liste de transferts — parsing des fichiers de trafic en arrière-plan plus performant.

3.09.005 (2026-02-13)
- Affiche la version dans le profil — la version courante est maintenant visible dans le profil utilisateur.
- Correction — sélecteur de langue au premier lancement (plus de langue incorrecte/par défaut).
- Correction — Options / Général & Avancé — cases à cocher et options restaurées à leur état correct.
- Interface de transfert renforcée — paramètre de connexion durci dans les éléments de trafic/transfert (moins d'états invalides/crashs).

3.09.004 (2026-02-12)
* Affichage de la version : Ajout d'une colonne de version dans la liste des utilisateurs pour que vous puissiez facilement voir quelle version les autres utilisent.
* Introduction d'une action pour re-analyser les dossier partagé.
* Ajout d'une colonne affichant le statut de vos dossiers partagés pour une meilleure visibilité.
* Les versions s'affichent maintenant en couleurs pour rapidement voir les versions parfaitement compatibiles.
* Amélioration de la sécurité dans l'écriture et la lecture de fichiers pour éviter les erreurs.
* Activation de la nouvelle fenêtre de selection de fichier spécifiquement pour les utilisateurs Mac.
* Plantages : Correction d'un problème de plantage et amélioration de la stabilité globale de l'application.
* Correction d'un problème avec la lecture des fichiers pour éviter les problèmes de mémoire.

3.09.002 (2026-02-06)
* L’ouverture du réseau gagne en clarté : compteur de progression, réinitialisation fiable du premier lancement et meilleure gestion du message “il faut la dernière version”.
* Les performances globales sont durcies (gestion des threads et transferts) pour des sessions plus stables même sous forte charge.
* Les surveillances de dossiers ont été revues pour consommer moins de ressources disque.
* Les transferts de fichiers sont plus robustes : envoi via tunnel dès que prêt, correction des uploads et affichage du nombre de dossiers en lecture.
* Une alerte s’affiche maintenant dans la barre d’état quand le disque est jugé trop lent, facilitant le diagnostic des ralentissements.

3.08.042 BETA (2026-01-16)

* Amélioration des performances de la recherche CRC.
* Optimisation du chargement des fichiers d'état pour les disques lents.
* Améliorations générales des performances.

3.08.041 BETA (2026-01-14)

* Optimisations multiples du téléchargement de fichiers.
* Nettoyage général du code.
* Améliorations générales des performances.

3.08.040 BETA (2025-12-22)

* Mise à jour du système de journaux (logging).
* Diverses améliorations de la connexion et des tunnels réseau.

3.08.038 (2025-12-18)

* Correction des problèmes de l'installeur Windows.
* Ajout de la gestion des événements d'ouverture d'URL sur macOS (protocole gigatribe://).
* Diverses corrections de bugs mineurs.
* [Version Mac](https://www.gigatribe.com/software/macx/GigaTribe-3.08.038.dmg)

3.08.035 (2025-11-26)

- Nous nous sommes concentrés sur le fait de rendre GigaTribe **plus intelligent, plus sûr et plus rapide** dans cette mise à jour.
- **Accès facilité grâce aux liens (Deep Linking) :** Vous pouvez désormais ouvrir GigaTribe directement sur le contenu pertinent en cliquant simplement sur les liens spéciaux `gigatribe:` que vous trouvez dans votre navigateur, vos e-mails ou vos messages de chat.
- **Sécurité et fiabilité améliorées :** Nous avons renforcé la manière dont GigaTribe gère les liens et les parties externes de l'application, en particulier sous Windows, la rendant globalement plus **sécurisée et stable**.
- **Performances plus fluides :** Nous avons mis à jour le code essentiel de l'application pour garantir qu'elle fonctionne bien et reste **rapide** sur les systèmes d'exploitation informatiques les plus récents.

3.08.034 (2025-11-18)

- Signature de l'application pour le système Windows.

3.08.031 (2025-11-05)

- Cette mise à jour rend l'application plus stable et fiable.
- **Fonctionnement plus fluide :** Correction de problèmes pouvant entraîner le ralentissement ou le plantage de l'application.
- **Mode sombre amélioré :** Rendu les messages de chat plus faciles à lire lors de l'utilisation du mode sombre.
- **Memoire :** Correction d'une fuite mémoire en connexion direct.
- **Corrections générales :** Amélioration des connexions, de la recherche et des transferts de fichiers.

3.08.030 (2025-10-30)

- Une mise à jour mineure pour améliorer le processus de mise à jour lui-même.
- **Mises à jour plus intelligentes :** Rendu la fonctionnalité de mise à jour automatique plus fiable pour les utilisateurs de Windows.

3.08.029  (2025-10-29)

- Cette mise à jour rend l'application plus conviviale.
- **Noms d'appareils plus clairs :** Vos appareils affichent désormais des noms conviviaux (comme « Smartphone de John ») au lieu de codes techniques.
- **Lecture plus facile :** Amélioration des couleurs du texte dans le chat pour les modes clair et sombre.
- **Sons corrigés :** Correction d'un bug qui empêchait la lecture correcte des sons de notification.
- **Autres corrections :** Amélioration du processus de mise à jour pour les utilisateurs Mac et correction d'autres bugs mineurs.

3.08.028  (2025-10-28)

- Il s'agissait d'une mise à jour de maintenance pour améliorer la façon dont vous recevez les nouvelles versions.
- **Mises à jour améliorées :** Amélioration du système de mise à jour automatique pour tous les utilisateurs.
- **Installation plus fluide (Windows) :** L'installateur Windows fonctionne désormais mieux sur un plus grand nombre d'ordinateurs.

3.08.027  (2025-10-27)

- Une mise à jour importante axée sur la stabilité et la sécurité.
- **Connexions plus stables :** Renforcement des connexions réseau et correction de problèmes pouvant entraîner des plantages lors des transferts de fichiers.
- **Sécurité renforcée :** Ajout de vérifications supplémentaires pour sécuriser vos connexions.
- **Performances accrues :** L'application fonctionne désormais plus efficacement en arrière-plan.

3.08.024  (2025-10-27)

- Une mise à jour de maintenance pour améliorer l'expérience sous Windows.
- **Meilleure installation Windows :** L'installateur fonctionne désormais mieux sur un plus grand nombre d'ordinateurs Windows.
- **Moins de fausses alertes :** Suppression des messages d'erreur confus qui apparaissaient alors que tout fonctionnait.

3.08.023  (2025-10-22)

- Cette mise à jour rend les notifications par e-mail plus faciles à comprendre.
- **Alertes e-mail plus claires :** L'application vous indique désormais clairement si vos notifications par e-mail sont désactivées car votre adresse e-mail n'est pas vérifiée.
- **Paramètres simplifiés :** La page des paramètres est maintenant plus facile à comprendre.

3.08.022  (2025-10-21)

- Un correctif rapide pour un bug visuel.
- **Noms d'appareils corrigés :** Correction d'un bug qui empêchait vos noms d'appareils personnalisés de s'afficher correctement.

3.08.021  (2025-10-21)

- Cette mise à jour visait à améliorer votre expérience de chat sur tous les appareils.
- **Synchro du chat multi-appareils :** Vos messages de chat se synchronisent désormais parfaitement sur tous vos appareils (téléphone, ordinateur, etc.).
- **Meilleur historique de chat :** Amélioration de la sauvegarde et de l'affichage de votre historique de chat.

3.08.007-BETA (2024-05-31)

- Introduction du mode multi-connexions 
- Optimisation de l'algorithm de transfer 
- Amélioration de la connectivité avec le VPN

3.08.001-BETA (2024-05-31)

- Migration vers la version 6 de QT
- Correction de fautes d'orthographe

3.06.015 (2024-03-06)

- Amélioration des traductions

3.06.014 (2024-02-27)

- Amélioration de la traduction des recommendations

3.06.013 (2024-02-19)

- Correction d'une traduction manquante en français

3.06.012 (2024-02-13)

- Ajout d'une options de notification dans les options de profil 
- Amélioration de la traduction espagnole

3.06.011 (2024-02-08)

- Améloration de la conformité RGPD
- Correction d'un bug sur la version linux

3.06.010 (2021-08-30)

- Ajout des correctifs issus de la BETA dans la version Release

3.07.009-BETA (2021-08-30)

- Correction d'un bug d'affichage des icones sur écran rétina sous Mac
- Suppression du bouton de mise à jour sur Mac (il n'y a pas de mise à jour automatique sous Mac/beta)
- Correction de bugs sur l'historique du chat.


3.07.005-BETA (2021-06-08)

- Amélioration de la gestion d'erreur lors de la lecture de l'historique de chat


3.07.005-BETA (2021-06-08)

- Amélioration de la gestion d'erreur lors de la lecture de l'historique de chat

3.07.004-BETA (2021-06-07)

- Correction d'un autre bug sur l'historique de chat
- Améliration du profile utilisateur quand l'adresse email n'est pas validée
- "Supprimer les transferts inutiles" devient "Supprimer les transferts terminés"

3.07.003-BETA (2021-05-20)

- Correction de bug sur l'historique de chat
- Ajout d'un formulaire de signalement de bug directement dans le chat

3.06.007 (2020-06-22)

- Correction du chat sous windows (problème d'encodage de caratères)

3.06.006 (2020-06-19)

- Backport depuis la béta du correctif sur l'historique de chat

3.07.001-BETA (2020-06-12)

- Amélioration du stockage des historiques de chat

3.06.005 (2020-06-03)

- Correction de la lecture de vidéos en cours de téléchargement
- Amélioration de l'installeur sous Windows

3.06.004 (2020-05-18)

- Ajout du menu RAZ sur la page de connexion

3.06.003 (2020-04-24)

- Corrections du rafraîchissement des dossiers partagés distants
- Corrections de l'affichage lors de l'utilisation de grandes polices
- Amélioration de l'installeur pour Mac

3.06.002 (2020-04-08)

- Corrections de design lors de la configuration des dossiers partagés
- Amélioration de l'affichage des emails non validé et ajout d'un bouton pour envoyer un email de validation
- Changement de la page de nouveautés en une page d'accueil
- Ajout d'une options de recherche par tag dans la fenêtre de recherche
- Amélioration du texte de l'option 'liste rouge'
- Amélioration de la sélection de dossier lors d'un partage (sélection par défaut des sous dossiers)

3.06.001 (2020-03-31)

- Mise à jour mineur sur la traduction de certains éléments.

3.05.043 (2020-03-20)

- Correction d'un problème de performance sur certaine fenêtre de dialogue.

3.05.041-beta (2020-03-18)

- Création du channel BETA

3.05.039 (2020-03-17)

- Correction du menu contextuel sur le lien (dans le chat)
- Amélioration de du style de la page de news
- Ajout du menu burger dans la fenêtre de connexion

3.05.038 (2020-03-12)

- Améliorations du mode sombre
- Correction de la position du menu "burger"
- Correction du bug lors de l'insertion de lien
- Correction de crash possible lorsque plusieurs instance de gigatribe on été lancées

3.05.037 (2020-03-05)

- Améliorations de la certification de l'installeur MacOs
- Améliorations de l'installeur Windows
- Améliorations de l'installeur Linux
- Améliorations de styles (chat, menus ...)

3.05.036 (2020-03-03)

- Améliorations du mode sombre
- Améliorations de entête de tableau (style et sauvegarde de l'état)
- Nettoyage et optimisation du code
- Petites améliorations de style
- Amélioration de la gestion des tailles de police dans le chat
- Correction du bugs en mode sombre de la boite de dialogue des mises à jours
- Amélioration des capacités de reconnexion après qu'un utilisateur se déconnecte.

3.05.035 (2020-02-26)

- Nouvelle fonctionnalité : la version Linux
- Corrections de bugs potentiels
- Nettoyage du code

3.05.034 (2020-02-24)

- Améliorations du mode sombre (couleurs)
- Correction d'un bug possible aléatoire

3.05.033 (2020-02-21)

- Correction de plusieurs crash
- Nouvelle fonctionnalité : les liens gigatribe://hashtag/#xxx
- Nouvelle fonctionnalité : le Mode sombre et amélioration de la présentation
- Ajout du menu "burger"
- Correction de la sérialisation (Message de chat / download en cours)
- renommage des tags en hashtags

3.05.032 (2019-12-02)

- Correction d'un bug lors du chargement des polices
- Correction de la compilation sous Windows

3.05.031 (2019-11-29)

- Certification de l'installeur pour MacOs (meilleur signature et "Notarization" du bundle)
- Amélioration du bundle pour MacOs (options dans info.plist)
- Correction de la dé-sélection automatique du dossier partagé
- Amélioration des icônes système (augmentation de la résolution)
- Sauvegarde des option de chat
- Amélioration de l'installeur pour Windows

3.05.030 (2019-11-21)

- Correction de plusieurs crash lors de log d'erreur
- Amélioration du bundle pour MacOs

3.05.029 (2019-11-19)

- Amélioration de la performance lors du chargement des icônes
- Correction d'un problème de connexion au VPN

3.05.028 (2019-11-14)

- Correction de plusieurs corruptions mémoire potentielles
- Pas de suppression des transferts en pause
- Amélioration de la compilation et des performances
- Amélioration des Vue Qt.

3.05.027 (2019-11-12)

- Correction de plusieurs crashs

de 3.04.013 à 3.05.027

- Passage à Qt5, amélioration du système de connections, améliorations de performances
