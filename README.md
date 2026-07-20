<div align="center">
  <img width="100%" src="https://raw.githubusercontent.com/feryamaha/feryamaha/refs/heads/main/gjeXH.png" />
</div>

<h1 align="center">Fernando Moreira</h1>
<p align="center"><strong>Full-Stack TypeScript (React/Next.js) · OWASP · Autor do Nemesis Defender</strong></p>

<br/>

Desenvolvedor Full-Stack TypeScript com foco em **arquitetura limpa**, **segurança por padrão** e **desenvolvimento assistido por IA sob governança explícita**. Trabalho com React e Next.js App Router em sistemas que exigem previsibilidade, performance e mitigação ativa de risco — sem adivinhar, **com princípios técnicos claros.**

- **Frontend-first** → UI sólida antes de complexidade desnecessária
- **Arquitetura em camadas** → UI → Hooks → Services → BFF
- **Performance real** → RSC híbrido, edge caching, bundle mínimo
- **Segurança aplicada** → CSP strict-dynamic, HSTS, COOP/COEP, validação runtime, OWASP
- **Experiência premium** → pixel perfect, acessibilidade, animações suaves

---

## 🛡️ Nemesis Defender

Sistema de **enforcement determinístico** para desenvolvimento assistido por IA, escrito em **Rust**. Construído ao longo de ~1 ano dentro de um projeto real de produção, evoluindo de regras em markdown → AST linter automático → três camadas independentes.

- **Camada 1** — Pretool Hook: intercepta comandos antes da execução (hard-gate)
- **Camada 2** — Content Scanner: AST + denylist + decoder recursivo, 12 visitors
- **Camada 3** — eBPF Kernel LSM (Linux): bloqueio de syscalls no kernel

> A ideia central: **não confiar que o modelo vai obedecer.** A camada bloqueia mesmo que ele seja enganado ou erre. Validado por ~1 ano em produção real — zero incidente de exclusão de arquivos sem permissão. Portável para Cursor, Windsurf, VS Code, Claude Code e Codex.

---

## + Mentalidade de Engenharia

> "Componentes são detalhes. O que escala é arquitetura."

- Modelagem de UI em **design system** (tokens, composição, semântica)
- **Next.js + React** com **App Router + RSC híbrido**
- **BFF** com Route Handlers + **validação Zod** em runtime
- Estruturas de cache → revalidate, incremental hydration
- **Edge-first**: deploy, SSR, APIs e proteção de credenciais
- **Automação de qualidade**: lint, Prettier, Git hooks, pipelines

---

## + Segurança (OWASP)

- CSP strict-dynamic (nonce)
- HSTS + HTTPS obrigatório
- COOP/COEP (isolamento de contexto)
- X-Frame-Options: DENY
- Runtime validation com **Zod**
- **API Keys isoladas (server-only)**
- **CSR limitado apenas ao que precisa**

> **Frontend ≠ "tela bonita"**
> Frontend moderno é **engenharia de superfície**: UX, estado, rede, cache, risco e produção.

---

## + De onde venho

Antes de software, foram **17 anos em metrologia 3D** — precisão milimétrica, GD&T avançado e engenharia reversa. Não é trivial: é a origem de como penso código. Contratos explícitos, tolerância zero a ambiguidade e qualidade verificável vieram do background de metrologia para a arquitetura e a segurança.

---

## + Contato

- **Portfólio**: https://hub-fernando-dev.vercel.app/
- **LinkedIn**: https://www.linkedin.com/in/feryamaha/
- **Twitter/X**: https://x.com/_feryamaha
- **GitHub**: https://hub-fernando-dev.vercel.app/
- **Nemesis_Defender**: https://dashboard-nemesis-defender.vercel.app/

---

> **"Meu trabalho é fazer produtos que as pessoas amam usar e que os times conseguem manter."**
