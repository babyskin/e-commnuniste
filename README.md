# E-COMMUNISTE

## Présentation

Ce projet vise à démocratiser l'accès à la culture en présentant des alternatives aux plateformes commerciales traditionnelles et propose des solutions d'auto-hébergement pour la musique, le cinéma ainsi que l'accès aux livres.

Présenté lors d'un RUMP à la GEEK'S NIGHT 2025 :)


## Créer sa Plateforme de Streaming Musical

- **[Navidrome](https://github.com/navidrome/navidrome)** - Serveur de streaming pour héberger tes musiques
- **[Streamrip](https://github.com/nathom/streamrip)** - Outil pour fetch tes musiques fav
- **[Tempo](https://github.com/CappielloAntonio/tempo/releases)** - Client mobile Android pour Navidrome


## Créer sa Plateforme de Streaming Cinéma

### Stack complète

- **[Jellyfin](https://github.com/jellyfin/jellyfin)** - Serveur de streaming multimédia (alternative à Plex)
- **[Jellyseerr](https://github.com/Fallenbagel/jellyseerr)** - Interface de requêtes de films/séries
- **[Radarr](https://github.com/Radarr/Radarr)** - Gestionnaire automatique de films
- **[Prowlarr](https://github.com/Prowlarr/Prowlarr)** - Gestionnaire d'indexeurs pour Radarr/Sonarr
- **[qBittorrent](https://github.com/qbittorrent/qBittorrent)** - Client torrent
- **[Gluetun](https://github.com/qdm12/gluetun)** - Client VPN pour pas qu'ils viennent sonner chez toi à 6h
- **[FlareSolverr](https://github.com/FlareSolverr/FlareSolverr)** - Proxy pour contourner Cloudflare
- **[JOAL](https://github.com/anthonyraymond/joal)** - Outil pour optimiser le ratio sur les trackers

### Architecture

```
Jellyseerr (Requêtes) → Radarr (Gestion) → Prowlarr (Indexeurs) 
                                              ↓
                                    qBittorrent + Gluetun (VPN)
                                              ↓
                                    Jellyfin (Lecture)
```

## Accès aux Livres

- **[Anna's Archive](https://annas-archive.org/)** - Bibliothèque numérique gratuite
- **[Z-Library](https://singlelogin.re/)** - Accès à des millions de livres


## Soutenir les indépendant

- **[HelloAsso - Catégorie Cinéma](https://www.helloasso.com/e/cat/cinema)** - Soutenez des associations cinématographiques
- **[Librairies Indépendantes](https://www.librairiesindependantes.com)** - Trouvez des librairies de proximité

## Précision

**Le manque d’objectivité apparent sur les slides s’explique par une dénonciation contextualisée, fondée sur des faits observables et actuels**, et non par une volonté idéologique de valoriser un système qui, historiquement ou aujourd’hui, peut également négliger une partie de la population.

Le terme **« e-communiste »** est utilisé ici comme **un néologisme, désignant le partage, la mutualisation et l’accessibilité des ressources sur Internet, indépendamment de toute doctrine politique traditionnelle.**
