# Lausanne Musées — écosystème technique

Sources des sites de l'Association des musées de Lausanne et Pully (AMLP) :
[lausannemusees.ch](https://lausannemusees.ch) (agenda annuel) et
[lanuitdesmusees.ch](https://lanuitdesmusees.ch) (La Nuit des Musées).

> Snapshots du code au **30.09.2026**, correspondant à l'état de production.

**Par où commencer → [docs](https://github.com/lausannemusees/docs)**
(architecture, flux de données, production), puis le README de chaque repo.

| Repo | Rôle |
|---|---|
| [docs](https://github.com/lausannemusees/docs) | Architecture, flux, production |
| [front-lausannemusees](https://github.com/lausannemusees/front-lausannemusees) | Site public agenda (Nuxt) |
| [front-lanuitdesmusees](https://github.com/lausannemusees/front-lanuitdesmusees) | Site public Nuit des Musées (Nuxt) |
| [api-v3](https://github.com/lausannemusees/api-v3) | API REST v3 — sert les deux fronts (CakePHP 5) |
| [api-v2](https://github.com/lausannemusees/api-v2) | API v2 legacy — flux Lausanne Tourisme (CakePHP 4) |
| [api-v1-archive](https://github.com/lausannemusees/api-v1-archive) | Première API (CakePHP 3), conservée pour référence |
| [cms](https://github.com/lausannemusees/cms) | Back-office musées + crawlers d'import quotidiens (CakePHP 3) |
| [cms-strapi](https://github.com/lausannemusees/cms-strapi) | Strapi — formulaires uniquement |
| [worker-thumbnails](https://github.com/lausannemusees/worker-thumbnails) | Cloudflare Worker — resizer d'images |

Contact technique : Damien Grossfeld (WGR) — `grossfeld@wgr.ch`
