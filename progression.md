# Suivi de progression — Remise à niveau technique

## Profil
- **Formation** : BTS Informatique, spécialité bases de données
- **Objectif** : Emploi ou freelance
- **Stack prioritaire** : SQL → Python → JavaScript/TypeScript

---

## État des compétences

| Compétence | Statut | Détail |
|---|---|---|
| SQL | 🟡 En progression | CRUD, JOIN, agrégation |
| Python | 🔴 À (re)démarrer | — |
| Git | 🟢 Solide | Structure interne, branches, merge, push |
| GitHub | 🟢 Acquis | Repo en ligne, push maîtrisé |
| JavaScript/TypeScript | ⏳ Plus tard | — |

---

## Git — Acquis

- ✅ Git installé et configuré (`user.name`, `user.email`)
- ✅ Premier repository local créé (`git init`)
- ✅ Cycle de base maîtrisé : `git add` → `git commit` → `git log`
- ✅ Repo connecté à GitHub (`remote add origin`)
- ✅ Premier `push` réussi
- ✅ Structure interne comprise : `HEAD`, hash, pointeurs, snapshots
- ✅ Branches : créer, travailler, merger (fast-forward), supprimer
- ✅ Workflow professionnel : feature branch → merge → push

---

## SQL — En progression

### Acquis
- ✅ DB Browser for SQLite installé (v3.13.1, Windows 64-bit)
- ✅ Créer une base de données et une table (`CREATE TABLE`)
- ✅ Contraintes : `PRIMARY KEY`, `AUTOINCREMENT`, `NOT NULL`, `UNIQUE`, `FOREIGN KEY`
- ✅ CRUD complet : `INSERT`, `SELECT`, `UPDATE`, `DELETE`
- ✅ Filtres et tri : `WHERE`, `ORDER BY`
- ✅ `INNER JOIN`, `LEFT JOIN`
- ✅ Fonctions d'agrégation : `COUNT`, `SUM`, `AVG`
- ✅ `GROUP BY`, `HAVING`
- ✅ Alias avec `AS`

### À faire
- [ ] Sous-requêtes
- [ ] Index et optimisation
- [ ] Fonctions : `ROUND`, `COALESCE`, `CAST`

---

## Prochaine session — À faire

- [ ] Sous-requêtes SQL
- [ ] Index et optimisation

---

## Sessions

### Session 1
- Installation et configuration de Git
- Création du premier repo local
- Pratique du cycle `add` → `commit` → `log`

### Session 2
- Création compte GitHub
- Connexion repo local → GitHub
- Premier `push` réussi
- Création du fichier `progression.md`

### Session 3
- Compréhension interne de Git : HEAD, hash, pointeurs, snapshots
- Lecture de `.git/HEAD` et `.git/refs/heads/main`
- Création et fusion d'une branche (fast-forward merge)
- Push vers GitHub
- Installation de DB Browser for SQLite

### Session 4
- Création de la base `gestion_commerciale.db`
- Table `clients` et table `commandes` avec `FOREIGN KEY`
- CRUD complet sur les deux tables
- `INNER JOIN` et `LEFT JOIN`
- Agrégation : `COUNT`, `SUM`, `AVG`, `GROUP BY`, `HAVING`