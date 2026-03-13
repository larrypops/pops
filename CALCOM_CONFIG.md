# Configuration Cal.com — Lumora Data
# 3 types de rendez-vous × 3 modalités (Téléphone · WhatsApp · Google Meet)
# Tout est auto-confirmé — pas de validation manuelle requise

---

## ORGANISATION CAL.COM

```
Compte    : lumoradata (cal.com/lumoradata)
Timezone  : Africa/Douala (WAT — UTC+1)
Langue    : Français
```

Créer 3 **Event Types** distincts, un par axe.
Chaque Event Type propose les 3 modalités via le champ "Location" multi-options.

---

## EVENT TYPE 1 — Axe IA
### "Stratégie IA PME — Appel gratuit 30 min"

**Slug** : `strategie-ia-pme`
**URL publique** : `cal.com/lumoradata/strategie-ia-pme`
**Durée** : 30 minutes
**Couleur** : Indigo (#4F46E5)
**Auto-confirmation** : ✅ Oui
**Limite par jour** : 4 rendez-vous maximum
**Plages horaires** : Lun–Ven, 9h–12h et 14h–17h (WAT)
**Buffer avant/après** : 10 minutes

### Description (visible sur la page de booking)
```
Vous avez téléchargé notre guide sur les agents IA. Cet appel est la prochaine étape.

En 30 minutes, on identifie ensemble :
→ Le processus dans votre entreprise qui mérite d'être automatisé en premier
→ Quels outils IA sont adaptés à votre taille et votre budget
→ Une estimation réaliste du coût et du retour sur investissement

Pas de présentation commerciale. Une conversation directe sur votre cas.

À la fin, vous repartez avec un plan d'action concret — que vous travailliez avec nous ou non.
```

### Modalités de rendez-vous (Location — choisir une)
| Option | Valeur |
|--------|--------|
| 📞 Appel téléphonique | Le prospect saisit son numéro — vous l'appelez |
| 💬 WhatsApp | WhatsApp call sur le numéro fourni |
| 🎥 Google Meet | Lien Meet généré automatiquement |

### Questions obligatoires (à configurer dans "Booking questions")

| # | Question | Type | Obligatoire |
|---|----------|------|-------------|
| 1 | Quel est le nom de votre entreprise ? | Texte court | ✅ |
| 2 | Dans quel secteur opère votre entreprise ? | Texte court | ✅ |
| 3 | Combien de personnes travaillent dans votre équipe ? | Choix unique | ✅ |
|   | _Options_ : Juste moi · 2–5 · 6–20 · 21–50 · +50 | | |
| 4 | Quelle tâche répétitive vous prend le plus de temps en ce moment ? | Texte long | ✅ |
| 5 | Avez-vous déjà essayé un outil IA (ChatGPT, Claude, etc.) dans votre travail ? | Choix unique | ✅ |
|   | _Options_ : Jamais · Oui, occasionnellement · Oui, régulièrement | | |
| 6 | Quel est votre budget mensuel approximatif pour un projet IA ? | Choix unique | ✅ |
|   | _Options_ : Je ne sais pas encore · Moins de 100 000 FCFA · 100 000–300 000 FCFA · Plus de 300 000 FCFA | | |
| 7 | Votre numéro WhatsApp (si vous choisissez WhatsApp comme modalité) | Téléphone | ❌ |

### Email de confirmation (à personnaliser dans Cal.com)
**Objet** : Votre appel Stratégie IA est confirmé — ce qu'on va couvrir

**Corps** :
```
Bonjour {{name}},

Votre appel du {{date}} à {{time}} est confirmé.

Ce qu'on va couvrir en 30 minutes :
→ Le ou les processus prioritaires à automatiser dans votre contexte
→ Les outils adaptés à votre équipe et votre budget
→ Un plan d'action concret pour démarrer

Pour préparer notre échange au mieux, réfléchissez à :
1. La tâche répétitive qui vous prend le plus de temps
2. Les outils que vous utilisez déjà (Excel, WhatsApp, ERP, etc.)
3. Ce que vous aimeriez déléguer à une machine si c'était possible

À très vite,
Larry MBILI — Lumora Data
```

### Email de rappel (J-1)
**Objet** : Rappel — votre appel demain à {{time}}

**Corps** :
```
Bonjour {{name}},

Je vous rappelle notre appel demain {{date}} à {{time}}.

Lien / modalité : {{location}}

Si vous devez annuler ou reporter : {{reschedule_link}}

À demain,
Larry — Lumora Data
```

---

## EVENT TYPE 2 — Axe DATA
### "Système de pilotage PME — Appel gratuit 30 min"

**Slug** : `pilotage-pme`
**URL publique** : `cal.com/lumoradata/pilotage-pme`
**Durée** : 30 minutes
**Couleur** : Émeraude (#059669)
**Auto-confirmation** : ✅ Oui
**Limite par jour** : 4 rendez-vous maximum
**Plages horaires** : Lun–Ven, 9h–12h et 14h–17h (WAT)
**Buffer avant/après** : 10 minutes

### Description (visible sur la page de booking)
```
Vous avez téléchargé un template de pilotage. Cet appel est pour aller plus loin.

En 30 minutes, on construit ensemble votre système de pilotage :
→ Les 5 à 8 indicateurs clés adaptés à votre activité spécifique
→ Comment automatiser la collecte depuis vos sources existantes (Excel, caisse, ERP)
→ Un dashboard qui se met à jour sans que vous y touchiez

L'objectif : que le lundi matin, vos chiffres soient là — pas que vous les cherchiez.

Pas de présentation commerciale. On part de votre situation réelle.
```

### Modalités de rendez-vous
| Option | Valeur |
|--------|--------|
| 📞 Appel téléphonique | Le prospect saisit son numéro — vous l'appelez |
| 💬 WhatsApp | WhatsApp call sur le numéro fourni |
| 🎥 Google Meet | Lien Meet généré automatiquement |

### Questions obligatoires

| # | Question | Type | Obligatoire |
|---|----------|------|-------------|
| 1 | Quel est le nom de votre entreprise ? | Texte court | ✅ |
| 2 | Quel est votre secteur d'activité ? | Texte court | ✅ |
| 3 | Taille de votre équipe | Choix unique | ✅ |
|   | _Options_ : Juste moi · 2–5 · 6–20 · 21–50 · +50 | | |
| 4 | Comment suivez-vous vos chiffres en ce moment ? | Choix unique | ✅ |
|   | _Options_ : Excel manuel · Logiciel comptable · Pas de suivi structuré · Autre | | |
| 5 | Quels chiffres aimeriez-vous voir chaque semaine sans avoir à les calculer ? | Texte long | ✅ |
|   | _Exemple_ : Ventes par produit, trésorerie, marge par client... | | |
| 6 | Quel est le problème principal avec votre suivi actuel ? | Texte long | ✅ |
|   | _Exemple_ : Trop de temps pour consolider, données éparpillées, données trop vieilles... | | |
| 7 | Votre numéro WhatsApp (si vous choisissez WhatsApp) | Téléphone | ❌ |

### Email de confirmation
**Objet** : Votre appel Système de pilotage PME est confirmé

**Corps** :
```
Bonjour {{name}},

Votre appel du {{date}} à {{time}} est confirmé.

Ce qu'on va construire ensemble en 30 minutes :
→ Les indicateurs pertinents pour votre activité spécifique
→ Comment automatiser la collecte depuis vos sources existantes
→ La structure de votre dashboard personnalisé

Pour préparer notre échange :
1. Rassemblez les sources où sont vos données aujourd'hui (fichiers Excel, logiciels, etc.)
2. Notez les 3 questions auxquelles vous n'arrivez pas à répondre rapidement sur votre activité
3. Estimez le temps que vous passez chaque semaine à chercher ou consolider des chiffres

À très vite,
Larry MBILI — Lumora Data
```

### Email de rappel (J-1)
**Objet** : Rappel — votre appel pilotage PME demain à {{time}}

**Corps** :
```
Bonjour {{name}},

Notre appel demain {{date}} à {{time}} — {{location}}.

Pour annuler ou reporter : {{reschedule_link}}

À demain,
Larry — Lumora Data
```

---

## EVENT TYPE 3 — Axe AUTOMATISATION
### "Diagnostic automatisation PME — Appel gratuit 30 min"

**Slug** : `diagnostic-automatisation`
**URL publique** : `cal.com/lumoradata/diagnostic-automatisation`
**Durée** : 30 minutes
**Couleur** : Orange (#D97706)
**Auto-confirmation** : ✅ Oui
**Limite par jour** : 4 rendez-vous maximum
**Plages horaires** : Lun–Ven, 9h–12h et 14h–17h (WAT)
**Buffer avant/après** : 10 minutes

### Description (visible sur la page de booking)
```
Vous avez téléchargé notre checklist d'audit. Cet appel est l'étape suivante.

En 30 minutes, on fait votre diagnostic d'automatisation :
→ Les processus dans votre entreprise qui méritent d'être automatisés en priorité
→ Quel quick win vous pouvez mettre en place cette semaine
→ Une estimation réaliste du temps récupérable et du coût

On part de vos processus réels — pas de solutions génériques.

À la fin de l'appel, vous avez un plan d'action concret, même si vous ne travaillez pas avec nous.
```

### Modalités de rendez-vous
| Option | Valeur |
|--------|--------|
| 📞 Appel téléphonique | Le prospect saisit son numéro — vous l'appelez |
| 💬 WhatsApp | WhatsApp call sur le numéro fourni |
| 🎥 Google Meet | Lien Meet généré automatiquement |

### Questions obligatoires

| # | Question | Type | Obligatoire |
|---|----------|------|-------------|
| 1 | Quel est le nom de votre entreprise ? | Texte court | ✅ |
| 2 | Secteur d'activité | Texte court | ✅ |
| 3 | Taille de l'équipe | Choix unique | ✅ |
|   | _Options_ : Juste moi · 2–5 · 6–20 · 21–50 · +50 | | |
| 4 | Quel processus vous prend le plus de temps chaque semaine ou chaque mois ? | Texte long | ✅ |
|   | _Exemple_ : Relances clients, gestion de la paie, rapports, gestion des commandes... | | |
| 5 | Ce processus est-il fait de la même façon à chaque fois ? | Choix unique | ✅ |
|   | _Options_ : Oui, toujours pareil · Souvent pareil, avec quelques variations · Non, ça change à chaque fois | | |
| 6 | Avez-vous déjà essayé d'automatiser quelque chose dans votre entreprise ? | Choix unique | ✅ |
|   | _Options_ : Jamais · Oui, avec succès · Oui, sans résultats convaincants | | |
| 7 | Quel résultat concret espérez-vous de cet appel ? | Texte long | ✅ |
| 8 | Votre numéro WhatsApp (si vous choisissez WhatsApp) | Téléphone | ❌ |

### Email de confirmation
**Objet** : Votre diagnostic automatisation est confirmé — préparez ces 3 infos

**Corps** :
```
Bonjour {{name}},

Votre appel du {{date}} à {{time}} est confirmé.

Ce qu'on va couvrir :
→ Audit rapide de vos processus les plus chronophages
→ Identification du quick win n°1 à automatiser
→ Estimation du temps récupérable et du coût réaliste

Pour qu'on aille droit au but, préparez ces 3 informations :
1. Le processus qui vous prend le plus de temps (paie, relances, commandes, rapports, autre)
2. Combien de fois par semaine ou par mois vous le faites
3. Combien de personnes sont impliquées dans ce processus

À très vite,
Larry MBILI — Lumora Data
```

### Email de rappel (J-1)
**Objet** : Rappel — votre diagnostic automatisation demain à {{time}}

**Corps** :
```
Bonjour {{name}},

Notre appel demain {{date}} à {{time}} — {{location}}.

Pensez à préparer :
→ Le ou les processus qui vous prennent le plus de temps
→ Vos outils actuels (Excel, logiciels, WhatsApp Business, etc.)

Pour annuler ou reporter : {{reschedule_link}}

À demain,
Larry — Lumora Data
```

---

## CONFIGURATION TECHNIQUE CAL.COM

### Intégrations à activer
```
✅ Google Calendar — synchronisation agenda (évite les doubles réservations)
✅ Google Meet — génération automatique des liens Meet
✅ Zoom — alternative si préféré
✅ Stripe — si paiement requis plus tard (laisser désactivé pour l'instant)
✅ Webhook — pour notifier votre backend quand un RDV est booké
```

### Webhook (notifier votre backend)
Configurer un webhook POST vers :
```
https://lumoradata.com/api/bookings/calcom
```

Payload reçu par Cal.com à chaque booking :
```json
{
  "triggerEvent": "BOOKING_CREATED",
  "payload": {
    "uid": "...",
    "title": "Stratégie IA PME — Appel 30 min",
    "startTime": "2025-03-15T09:00:00Z",
    "attendees": [{ "name": "...", "email": "...", "timeZone": "Africa/Douala" }],
    "responses": {
      "name": { "value": "..." },
      "email": { "value": "..." },
      "notes": { "value": "..." }
    },
    "eventTypeSlug": "strategie-ia-pme"
  }
}
```

Utiliser `eventTypeSlug` pour identifier l'axe et mettre à jour le statut du lead en DB :
```sql
UPDATE leads
SET statut = 'rdv_booké',
    score = score + 30,
    updated_at = NOW()
WHERE email = $1;
```

### URLs à utiliser dans les templates email
```
IA            : https://cal.com/lumoradata/strategie-ia-pme
DATA          : https://cal.com/lumoradata/pilotage-pme
AUTOMATISATION: https://cal.com/lumoradata/diagnostic-automatisation
```

### Page d'accueil Cal.com (profile page)
URL : `cal.com/lumoradata`

**Bio à configurer** :
```
Larry MBILI — Fondateur, Lumora Data

On aide les PME africaines à piloter leur activité par les données,
à automatiser leurs processus répétitifs et à intégrer l'IA dans leur quotidien.

Choisissez le type d'appel qui correspond à votre besoin.
```

---

## ORDRE DE CRÉATION SUR CAL.COM

1. Créer le compte `lumoradata` sur cal.com
2. Connecter Google Calendar (Settings → Integrations)
3. Connecter Google Meet (via Google Calendar OAuth)
4. Créer Event Type 1 : "Stratégie IA PME"
5. Créer Event Type 2 : "Système de pilotage PME"
6. Créer Event Type 3 : "Diagnostic automatisation PME"
7. Configurer le webhook vers `https://lumoradata.com/api/bookings/calcom`
8. Tester chaque URL de booking avec une adresse test
9. Mettre à jour les URLs dans les templates email (déjà pré-configurées)
