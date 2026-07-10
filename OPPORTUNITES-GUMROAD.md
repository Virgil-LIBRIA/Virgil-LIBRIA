# Opportunites Gumroad — Systeme Point Zero

Note strategique : croisement de l'inventaire d'actifs Virgil-LIBRIA avec le
marche Gumroad 2026. Objectif : identifier les prochains produits a lancer,
par ordre de potentiel.

Date : 2026-07-10

---

## 1. Etat des lieux

### Deja monetise

| Produit | Repo | Categorie Gumroad | Prix |
|---------|------|-------------------|------|
| Souterrain (framework multi-agents Claude Code) | `souterrain-gumroad` | Software Development | n.c. |
| INTemple Prompts (architecture cognitive LLM) | `intemple-prompts` | AI Prompts | 29 EUR |

Deux categories couvertes, toutes deux porteuses. Le reste de l'ecosysteme
(14+ repos) est aujourd'hui non monetise alors qu'une partie est directement
productisable.

### Ce que dit le marche Gumroad 2026

- **Software Development = categorie n°1** (~65,8 M$ cumules, plus haut
  revenu moyen par produit). C'est le terrain le plus favorable et c'est
  deja le votre avec Souterrain.
- **Outils / workflows dev > dumps de prompts.** Les gagnants sont des
  outils et des workflows, pas des paquets de prompts bruts. Acheteurs
  techniques, prix 20–99 $.
- **MCP + agents = demande en forte hausse.** Tout ce qui donne de la
  memoire, de l'orchestration ou de l'outillage a Claude/LLM se vend.
- **Writing & Publishing = pepite cachee.** Plus haut revenu par produit
  des categories « normales », concurrence la plus faible. Pertinent pour un
  corpus de 15 M de caracteres.
- **Formats qui convertissent a froid** : templates, packs, scripts,
  skills — rapides a produire, ~85 % du catalogue, plus gros volumes.

---

## 2. Opportunites classees par potentiel

### Palier A — Quick wins (actif deja pret, categorie n°1)

**A1. `claude-md-viewer` — micro-produit dev**
Navigateur HTML zero-dependance pour fichiers CLAUDE.md. Claude Code est en
pleine adoption ; un visualiseur propre, sans build, se vend seul.
- Positionnement : « CLAUDE.md Viewer — read & navigate your Claude Code
  config, zero deps. »
- Format : le fichier HTML + doc d'usage. Bundle possible avec des templates
  CLAUDE.md prets a l'emploi.
- Prix cible : 9–19 $. Volume eleve attendu, faible effort.

**A2. Pack de SKILLs Claude Code**
Souterrain contient deja des SKILLs (organiseur de fichiers, observateur
web). Extraire et enrichir en un pack autonome « N Claude Code Skills
prets a l'emploi ». Categorie dev, segment peu sature.
- Prix cible : 19–39 $. Upsell naturel des acheteurs de Souterrain.

**A3. `memoire-cinetique` — couche memoire MCP**
Memoire persistante locale (Mem0 + Ollama + MCP). C'est exactement le type
de produit en hausse en 2026 (« donnez une memoire persistante a Claude,
100 % local »).
- Positionnement : « Kinetic Memory — persistent local memory for Claude
  via MCP. No cloud. »
- Format : repo installable + guide de setup + demo.
- Prix cible : 29–59 $ (produit technique, valeur elevee).

### Palier B — Productisation moyenne (repackaging necessaire)

**B1. `corpus-indexer` (CLI `pz`) — indexeur de base de connaissances**
20 modules, 27 commandes pour indexer un corpus markdown. Generalisable
au-dela de Point Zero : « transformez n'importe quel corpus .md en index
interrogeable ». Outil dev/knowledge.
- Prix cible : 24–49 $. Cible : chercheurs, ecrivains, equipes doc.

**B2. Kit « Second cerveau / systeme de savoir »**
Bundle `glossaire-point-zero` + `navigation-point-zero` + `cdt-tool` en un
template de systeme de connaissances : glossaire structure, carte de
navigation interactive, cartographie dimensionnelle. Les templates de
knowledge-management sont un top-seller constant.
- Prix cible : 39–79 $ (bundle). Positionnable aussi comme template Notion-like.

**B3. `chambre` — moteur de resonance semantique**
Moteur Go + spaCy. Plus niche, mais differenciant pour un public technique
NLP. A garder pour un lancement cible plutot qu'immediat.
- Prix cible : 39–69 $.

### Palier C — Fort potentiel, effort de production (Writing & Publishing)

**C1. Le livre « Systeme Point Zero »**
Le prototype `ma-constellation-docs` est deja un sommaire de livre de
synthese. Writing & Publishing est la categorie au plus haut revenu par
produit et a la plus faible concurrence. Un ebook/PDF structure tire du
corpus (15 M caracteres, 6 piliers) est l'actif a plus forte valeur unitaire.
- Format : ebook PDF/EPUB, possiblement decline en volumes par pilier.
- Prix cible : 19–49 $ par volume, ou 79–129 $ en coffret complet.
- C'est le plus gros levier de revenu par unite, mais le plus long a finir.

---

## 3. Strategie de lancement recommandee

1. **Maintenant (30 j)** : A1 + A3. Deux produits dev prets, categorie n°1,
   effort minimal, chacun sert d'upsell a Souterrain.
2. **Ensuite (60–90 j)** : A2 (pack SKILLs) puis B1 (corpus-indexer) —
   consolident une gamme « outillage Claude Code / knowledge dev ».
3. **En parallele, fond de catalogue** : C1 (le livre) — chantier long mais
   plus haut revenu unitaire, sur la categorie la moins concurrentielle.
4. **Bundle transverse** : « Systeme Point Zero Toolkit » regroupant les
   produits dev a prix reduit — augmente le panier moyen.

### Reperes de prix (marche 2026)

- Micro-outils dev : 9–19 $
- Packs / skills : 19–39 $
- Outils techniques (MCP, CLI, moteurs) : 29–69 $
- Ebooks / volumes : 19–49 $ ; coffrets 79–129 $

---

## 4. Principe directeur

Le marche recompense les **outils et workflows**, pas les prompts bruts.
L'avantage de Virgil-LIBRIA est d'avoir deja construit ces outils : la valeur
est surtout dans le repackaging (positionnement, doc, demo, page de vente),
pas dans du developpement neuf. Priorite aux actifs deja fonctionnels de la
categorie Software Development, avec le livre comme pari long terme a forte
marge.

---

## Sources

- [Best-Selling Digital Products on Gumroad 2026 — Insight Raider](https://insightraider.com/en/answers/what-digital-products-sell-best-on-gumroad)
- [Gumroad Trends 2026: What's Selling — Conversion Pro Plus](https://conversionproplus.com/blog/gumroad-trends-2026-what-s-selling-right-now)
- [Top Selling Gumroad Categories — Accio](https://www.accio.com/business/top-selling-gumroad-categories)
- [Sell AI Prompt Pack Gumroad 2026 — Aicap](https://aicap.in/sell-ai-prompt-pack-gumroad-2026/)
- [Trending Gumroad Products & Best Sellers (Jul 2026) — Profitable.app](https://profitable.app/gumroad)
