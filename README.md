# Support de cours pour le TP Supervision de l'ENSIBS

**Description du repo git**
- /apps : l'application à superviser et le docker compose associé
- /cours : le support de cours .pdf projeté en séance

**Séance en deux parties**
1. Réflexion collective sur la notion d’incident autour de 4 thèmes  - 1h
2. Mise en pratique des outils de supervision Prometheus/Grafana - 2h

---

**Evaluation**
- Chaque étudiant transmettra par mail un rapport à la fin de la séance, comprenant :
  - Une note de synthèse sur la notion d'incident
  - Une capture d'écran avec une note d'explication de votre dashboard Grafana
  -Une description détaillée de l'un des panels qui compose votre dashboard

Le rapport est attendu au format PDF par mail. Le rapport doit comporter clairement votre nom, prénom et groupe.

---

**Démarrage**

dans le répertoire /apps :
docker compose up -d

Grafana :
http://localhost:3000 (admin:admin)

Prometheus :
http://localhost:9090