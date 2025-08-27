📊 État du projet — Arka R1 (fin M2)
✅ Réalisé

M1 livré et validé : test 

Authentification multi-clients et RBAC (viewer / operator / owner).

Création et gestion de projets + agents.

CI/CD de base opérationnelle (tests unitaires, lint).

UX Onboarding conforme aux maquettes (login → création projet → dashboard).

M2 partiellement livré :

Chat persisté (threads + messages) opérationnel.

Schéma de validation messages + tests unitaires robustes.

Intégration UX/UI : flows & composants validés, maquettes disponibles et intégrées côté UI (v1.0).

PMO : tickets de rebaselining rédigés pour SSE, Documents, Agent Events, Export mémoire et Metrics (suivi P0/P1).

Owner Ops : checklist d’environnement (flags, secrets, SSE timeouts, logs).

⚠️ Points d’attention

Back-end M2 incomplet :

SSE streaming, Documents API, Agent Events, Export mémoire, Metrics → spécifiés mais pas encore développés.

Couverture tests : < 50 % (objectif ≥ 80 % avant R1).

CI/QA : pas encore de validation automatique des KPIs (latence TTFT/RTT, % erreurs).

UX/UI : intégration en cours, besoin d’alignement final sur certains écrans (Documents, Observabilité).

Robustesse : soak tests et métriques runtime non encore industrialisés.

🎯 Prochaines priorités (M2 → M3)

Finaliser les capas manquantes M2 (SSE, Documents, Export, Metrics).

Mettre en place tests d’intégration + CI KPIs automatiques.

Stabiliser l’UI (lot Documents + Observabilité) avec les livrables UX.

Préparer vidéo démo + métriques (Kickstarter / AGP).

Monter couverture de tests → viser 70 % fin M2, 80 % avant R1.

👉 En résumé :
Nous avons une base solide (M1 validé + chat M2 opérationnel + UX livrée).
Le risque principal reste le retard sur le back-end M2 (5 features critiques non livrées).
Le cadrage PMO et OwnerOps est en place, mais la priorité immédiate est le rattrapage technique côté Codex sur les APIs SSE, Documents et Metrics.
