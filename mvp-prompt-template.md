# 🚀 MVP Prompt Template — Vibe Coding

Usa questo template ogni volta che hai una nuova idea di MVP.
Compilalo prima di iniziare a lavorare su qualsiasi AI tool (Lovable, Cursor, v0, ecc.).

---

## 1. 💡 L'IDEA IN UNA FRASE
> Descrivi il tuo MVP in massimo due righe. Cosa fa? Per chi?

```
[La tua idea qui]
Esempio: "Una piattaforma che permette ai freelance di creare invoice in 30 secondi tramite AI."
```

---

## 2. 👤 UTENTE TARGET
> Chi usa questo prodotto? Sii specifico.

```
- Chi è: [es. freelance designer, 25-35 anni, lavora da remoto]
- Problema che ha: [es. perde tempo a fare le fatture manualmente]
- Come lo risolve il tuo MVP: [es. compila i dati una volta, l'AI genera tutto]
```

---

## 3. ✅ FUNZIONALITÀ CORE (max 3)
> Solo le funzionalità ESSENZIALI per validare l'idea. Tutto il resto è v2.

```
1. [Feature principale — es. Form per creare invoice]
2. [Feature secondaria — es. Download PDF]
3. [Feature di crescita — es. Waitlist / iscrizione email]
```

---

## 4. 🚫 FUORI SCOPE (per ora)
> Cosa NON devi costruire in questa fase. Ti salva dal over-engineering.

```
- [ ] Autenticazione / login utenti
- [ ] Dashboard admin
- [ ] Pagamenti
- [ ] App mobile
- [ ] [Aggiungi altro...]
```

---

## 5. 🎨 STILE VISIVO
> Dai indicazioni sul look & feel per guidare l'AI nella generazione dell'UI.

```
- Mood: [es. minimal, moderno, caldo, professionale, playful]
- Colori principali: [es. bianco + nero + accento arancione]
- Riferimenti: [es. "simile a Notion" oppure "stile Linear"]
- Font: [es. serif elegante per i titoli, sans-serif per il corpo]
```

---

## 6. 🔧 STACK TECNICO
> Cosa usi per costruire. Lascia vuoto se lo decide l'AI tool.

```
- AI Tool: [Lovable / Cursor / v0 / altro]
- Frontend: [React / Next.js / lascia decidere]
- Backend/DB: [Supabase / Firebase / nessuno per ora]
- Integrazioni: [es. Resend per email, Stripe per pagamenti]
- Deploy: [Lovable / Vercel / altro]
```

---

## 7. 📏 DEFINIZIONE DI "FATTO"
> Come sai che il tuo MVP è pronto? Cosa deve funzionare al minimo?

```
Il MVP è completo quando:
- [ ] Un utente può [azione principale]
- [ ] L'utente riceve [feedback / conferma]
- [ ] Io posso vedere [dato / metrica]
```

---

## 8. 📐 SPEC TECNICHE (Spec Driven Development)
> Prima di toccare Lovable, genera questa documentazione tecnica strutturata.
> Puoi usare un'AI (Claude, Gemini, ecc.) con il prompt qui sotto per compilarla.

**Prompt da usare per generare le spec:**
```
Il mio obiettivo è sviluppare [IDEA IN UNA FRASE] utilizzando Lovable per il frontend 
e il sistema backend integrato di Lovable. Aiutami a scrivere la documentazione tecnica 
completa che mi servirà come linea guida strutturata per generare l'app.
Struttura la risposta in queste tre sezioni:

1. Requisiti di Prodotto: elenca le funzionalità base. Chiedimi conferma prima di passare 
alla fase tecnica.

2. Architettura Backend: struttura del database con tabelle, campi e relazioni (Foreign Keys).

3. Architettura Frontend: alberatura dei componenti principali e gestione dello stato.
```

**Una volta generate, incolla qui le spec:**

### 8a. Requisiti di Prodotto
```
[Incolla qui i requisiti generati]
```

### 8b. Architettura Backend
```
[Incolla qui la struttura del database]
```

### 8c. Architettura Frontend
```
[Incolla qui l'alberatura dei componenti]
```

---

## 9. 📣 PROMPT INIZIALE PER L'AI TOOL
> Copia e incolla questo prompt nel tuo tool preferito per iniziare.
> Compilalo con le info delle sezioni precedenti.

```
Build an MVP for [IDEA IN UNA FRASE].

Target user: [UTENTE TARGET]

Core features (and nothing else):
1. [FEATURE 1]
2. [FEATURE 2]
3. [FEATURE 3]

Out of scope for now: [FUORI SCOPE]

Visual style: [STILE VISIVO]

Tech stack: [STACK TECNICO]

The MVP is done when: [DEFINIZIONE DI FATTO]

Keep it simple. No over-engineering. Focus on validating the idea fast.
```

---

## 10. 📝 NOTE & DECISIONI
> Tieni traccia delle scelte importanti che fai durante lo sviluppo.

| Data | Decisione | Motivo |
|------|-----------|--------|
| | | |
| | | |

---

*Template creato per il vibe coding — aggiornalo man mano che impari!*
