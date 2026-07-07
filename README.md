# relations-platform
Projektet sætter scenen for arbejdet med at udvikle en samlende samarbejds/relations/administrations -platform til OS2-fællesskabet

# Arbejdsprincipper for projektet

## Formål

Dette repository er projektets fælles arbejdsrum.

Her samles:

- projektets opgaver
- dialog og idéudvikling
- analyser og beslutninger
- dokumentation
- konfiguration af platformen

Projektets mål er **ikke at udvikle ny software**, men at identificere, evaluere og implementere en samlet platform baseret på eksisterende open source-produkter.

---

# Princip 1 – GitHub er den fælles sandhed

Projektets aktiviteter dokumenteres i GitHub.

Det betyder, at:

- opgaver oprettes som **Issues**
- beslutninger dokumenteres i repository'et
- ændringer gennemgås via **Pull Requests**
- projektets status følges i **GitHub Projects**

Information bør så vidt muligt ikke "gemmes" i mails eller private noter.

---

# Princip 2 – Issues beskriver arbejde

Et **Issue** repræsenterer et konkret stykke arbejde.

Det kan eksempelvis være:

- en workshop
- en analyse af et produkt
- en beslutning
- en implementeringsopgave
- dokumentation
- en forbedring

Et Issue bør som minimum beskrive:

- formål
- forventet leverance
- acceptkriterier
- ansvarlig(e)
- relevante labels

Store aktiviteter opdeles i mindre Issues, så fremdriften bliver synlig.

---

# Princip 3 – GitHub Projects giver overblik

GitHub Projects anvendes til projektstyring.

Alle relevante Issues tilknyttes projektet og flyttes gennem workflowet.

Eksempel:

```text
Backlog
    ↓
Klar
    ↓
I gang
    ↓
Review / Afventer
    ↓
Afsluttet
```

Projects giver et samlet overblik over status, ansvar og fremdrift.

---

# Princip 4 – Pull Requests kvalitetssikrer ændringer

Alle væsentlige ændringer foretages gennem en **Pull Request**.

Det gælder både:

- dokumentation
- analyser
- arkitekturbeslutninger
- konfiguration
- scripts
- kode (hvis projektet senere udvikler software)

Pull Requests giver mulighed for:

- review
- kommentarer
- fælles ejerskab
- sporbar historik

---

# Princip 5 – Beslutninger dokumenteres

Projektets væsentlige beslutninger skal kunne findes igen.

Eksempler:

- valg af produkter
- fravalg af produkter
- integrationsprincipper
- arkitektur
- governance

En beslutning bør beskrive:

- baggrund
- alternativer
- beslutning
- begrundelse
- konsekvenser

---

# Princip 6 – Transparens

Projektet bygger på åbenhed.

Derfor bør:

- analyser være tilgængelige
- beslutninger dokumenteres
- diskussioner være åbne
- projektets status kunne følges af alle deltagere

Målet er, at alle kan forstå projektets udvikling og beslutningsgrundlag.

---

# Princip 7 – Genbrug før nyudvikling

Projektets grundlæggende princip er:

> Konfigurer, integrer og anvend eksisterende open source-løsninger frem for at udvikle ny software.

Ved vurdering af produkter prioriteres blandt andet:

- modenhed
- aktivt community
- åbne standarder
- integrationsmuligheder
- dokumentation
- driftsmæssig bæredygtighed

---

# Sammenhæng mellem GitHub-funktionerne

| Funktion | Formål |
|----------|--------|
| **Issues** | Konkrete opgaver og leverancer |
| **Projects** | Planlægning, prioritering og status |
| **Pull Requests** | Review og godkendelse af ændringer |

---

# Typisk arbejdsproces

```text
Idé eller behov
        │
        ▼
Issue
        │
        ▼
Analyse / Implementering
        │
        ▼
Pull Request
        │
        ▼
Review
        │
        ▼
Merge
        │
        ▼
Issue afsluttes
```

---

# Vejen videre

Når projektet modnes, kan disse principper suppleres med:

- Issue-skabeloner
- Pull Request-skabeloner
- Navngivningskonventioner
- Labels og kategorier
- Definition of Done
- Beslutningsskabeloner (ADR)
- Governance og roller
- Retningslinjer for møder og workshops

Målet er at holde arbejdsformen enkel, gennemsigtig og let at deltage i, samtidig med at projektets viden og beslutninger bevares og kan genfindes.
