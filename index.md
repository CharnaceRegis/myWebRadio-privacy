# Politique de confidentialité — Neon Radio

**Dernière mise à jour : 15 octobre 2026**

Cette politique décrit comment l'application **Neon Radio** (« nous », « l'application ») traite les données lorsque vous l'utilisez.

## En résumé

**Nous ne collectons aucune donnée personnelle.** Pas de compte, pas de publicité, pas d'outil de mesure d'audience, pas de rapport de plantage. Nous n'avons aucun serveur : vos favoris et vos enregistrements restent sur votre téléphone.

## Données traitées

### Annuaire des stations (Radio Browser)

La liste des stations vient de l'annuaire public et gratuit [Radio Browser](https://www.radio-browser.info/). L'application interroge directement ses serveurs (`*.api.radio-browser.info`) pour la recherche par nom et par pays.

Quand vous lancez une station, l'application le signale à Radio Browser (compteur public de popularité de la station). Ces requêtes ne contiennent aucun identifiant : seulement la station ou la recherche concernée. Comme toute connexion Internet, elles exposent votre adresse IP à ce service.

### Flux audio

Le son est lu directement depuis le serveur de la station choisie, sans intermédiaire. Ce serveur, géré par la station et non par nous, voit votre adresse IP comme pour toute écoute en ligne. Certaines stations ne diffusent qu'en `http://` non chiffré : l'application l'autorise pour pouvoir les lire.

### Favoris et reprise (stockage local)

Vos stations favorites, la dernière station ou le dernier enregistrement écouté (et sa position) sont stockés **uniquement sur votre téléphone**, dans le stockage de l'application. Rien n'est transmis.

### Enregistrements

Les enregistrements du flux sont écrits dans un dossier que **vous choisissez** via le sélecteur de fichiers d'Android. L'application n'accède qu'à ce dossier, à rien d'autre de votre stockage. Les fichiers restent sur votre téléphone ; vous pouvez les supprimer depuis l'application ou l'app Fichiers.

### Mises à jour de l'application

Les mises à jour mineures sont téléchargées depuis le service **EAS Update** d'[Expo](https://expo.dev/privacy). La requête contient la version de l'application, la plateforme et un identifiant d'installation aléatoire, utilisé seulement pour la distribution des mises à jour. Aucune donnée personnelle.

## Permissions Android

- **`INTERNET`** : annuaire des stations, flux audio, mises à jour.
- **`POST_NOTIFICATIONS`** : notification de lecture avec les contrôles play/pause.
- **Lecture en arrière-plan** (service de lecture multimédia) : continuer l'écoute écran éteint ou dans une autre application.

L'application **ne demande pas** l'accès au micro, à la localisation, aux contacts ni à vos photos et fichiers.

## Enfants

L'application ne cible pas spécifiquement les enfants et ne collecte aucune donnée, y compris les concernant. Le contenu des stations relève de leurs diffuseurs.

## Vos droits (RGPD)

- **Désinstaller l'application** efface toutes ses données locales (favoris, reprise). Les enregistrements, dans le dossier que vous avez choisi, restent jusqu'à ce que vous les supprimiez.
- Comme nous **ne stockons rien sur nos serveurs**, il n'y a rien à demander à effacer de notre côté.

## Contact

Pour toute question sur cette politique : **euselproduction@gmail.com**

## Modifications

Toute modification sera publiée sur cette page avec une nouvelle date de mise à jour.

---

# Privacy Policy — Neon Radio

**Last updated: October 15, 2026**

This policy describes how the **Neon Radio** app ("we", "the app") handles data when you use it.

## TL;DR

**We collect no personal data.** No account, no ads, no analytics, no crash reporting. We have no server: your favorites and recordings stay on your phone.

## Data processed

### Station directory (Radio Browser)

The station list comes from the free public directory [Radio Browser](https://www.radio-browser.info/). The app queries its servers (`*.api.radio-browser.info`) directly to search by name and country.

When you start a station, the app reports it to Radio Browser (a public popularity counter for the station). These requests carry no identifier, only the station or search involved. Like any Internet connection, they expose your IP address to that service.

### Audio streams

Audio is played directly from the selected station's server, with no intermediary. That server, run by the station and not by us, sees your IP address as with any online listening. Some stations only broadcast over unencrypted `http://`: the app allows it so they can be played.

### Favorites and resume (local storage)

Your favorite stations and the last station or recording played (with its position) are stored **only on your phone**, in the app's storage. Nothing is transmitted.

### Recordings

Stream recordings are written to a folder **you choose** with Android's file picker. The app only accesses that folder, nothing else on your storage. Files stay on your phone; you can delete them from the app or the Files app.

### App updates

Minor updates are downloaded from [Expo](https://expo.dev/privacy)'s **EAS Update** service. The request contains the app version, the platform and a random installation identifier, used only to distribute updates. No personal data.

## Android permissions

- **`INTERNET`**: station directory, audio streams, updates.
- **`POST_NOTIFICATIONS`**: playback notification with play/pause controls.
- **Background playback** (media playback service): keep listening with the screen off or in another app.

The app **does not request** access to the microphone, location, contacts, or your photos and files.

## Children

The app is not specifically aimed at children and collects no data, including about them. Station content is the responsibility of its broadcasters.

## Your rights (GDPR)

- **Uninstalling the app** erases all its local data (favorites, resume). Recordings, in the folder you chose, remain until you delete them.
- Since we **store nothing on our servers**, there is nothing to request to be deleted on our side.

## Contact

For any questions about this policy: **euselproduction@gmail.com**

## Changes

Any change will be published on this page with an updated date.
