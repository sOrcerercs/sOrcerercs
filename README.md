### Kağan Öztürk

I run sales quality at a medical tourism group and I build the software that measures it. Five internal products in production: LLM-based call evaluation, OKR tracking, financial reporting, CRM enrichment, and an agent system that runs the recurring reporting work.

#### How I work

- **Measure in production before designing.** Several of my own assumptions have died this way, and that is the point.
- **The model judges; the code computes.** I measured an 18% disagreement between an LLM's reported total and its own criteria data, and moved every calculation out of the prompt.
- **A wrong number is worse than a missing one.** Unconfirmed formulas render as "—", never as a guess.
- **A human presses publish.** Automation proposes; people decide.

#### Selected work

The five products, and where the principles above come from. Two are internal and stay private.

- **sdr-call-quality** · *private*: LLM call quality evaluation and weekly coaching briefings. The model scores each criterion; the code computes the total. `Next.js` `Prisma` `Postgres` `Gemini`
- [**nove-analytics**](https://github.com/sOrcerercs/Nove-Group-Analysis): matches meeting transcripts to CRM contacts with a two-signal confidence gate. `Python` `Next.js` `Postgres`
- **nove-finans** · *private*: financial reporting built on SAP records. A figure whose formula is not confirmed shows "—". `Next.js` `Postgres`
- [**nove-performance**](https://github.com/sOrcerercs/nove-performance): OKR and goal tracking. Public copy with fictional sample data. `Next.js` `Drizzle`
- [**nove-kurul**](https://github.com/sOrcerercs/nove-kurul): the agent system behind the recurring reporting work. Advisor agents draft, an auditor checks the rules, a person presses publish. `Python`

On the side: [**clawd-buyucu**](https://github.com/sOrcerercs/clawd-buyucu), a Claude Code mode where a pixel-art wizard brews potions while you code.

---

Sales Performance & Quality Supervisor @ Nove Group (EsteNove) · Istanbul · [LinkedIn](https://www.linkedin.com/in/kagan-ozturk/)
