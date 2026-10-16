# Pendências & Roadmap — Painel da Salty

> Lista viva do que ficou pra depois. Atualizada conforme a gente decide.

## 📱 Fase 2 — App do aluno (não é o painel de gestão)
- [ ] **Comunidade de alunos** — alunos se adicionarem/seguirem, verem aulas agendadas de quem seguem, "bater meta junto" / ir na mesma aula.
  - Decisão (14/10/2026): **fica no app do aluno**, não no painel. Começar pequeno e seguro (modelo "squads"/turmas fechadas de 4–6 pessoas, opt-in), rede social aberta só se engajar.
  - Risco a cuidar: privacidade/assédio → sempre opt-in, com bloquear/aceitar; não expor frequência de quem vai pouco.
- [ ] **Área do aluno** base: ver meus créditos, agendar, meu progresso/Wrapped. A comunidade entra como aba disso.

## 💬 Comunicação (fase futura — quando fizer sentido pagar)
- [ ] **WhatsApp API oficial** — hoje NÃO usamos (reduzir custo). Disparo é pelo botão wa.me do painel (recepção envia manual). Sem recibo de entregue/lida.
  - Quando crescer: migrar pra API oficial pra ter recibos automáticos de entregue/lida.
- [ ] **E-mail marketing + rastreio** (enviado/entregue/aberto/clicado). **Ferramenta escolhida: Brevo** (ex-Sendinblue) — plano gratuito (contatos ilimitados, limite por e-mails/dia), API + webhooks, integra com n8n, tem WhatsApp/SMS na mesma plataforma, suporte PT. Alternativa mais simples: MailerLite (grátis até 1.000 contatos / 12.000 e-mails/mês). Integrar quando for a hora.
  - OBS: Salty é um negócio independente — sem relação com Hit Haus, Angular ou qualquer outro sistema. Zero integrações herdadas.

## 🗓️ Em construção / próximo
- [ ] **Escala da recepção v2**: visão mensal + semanal, turnos editáveis (ex: sábado abre 8h, não 6h), só gestor edita (recepção só vê), auto-preenchimento por regra de rodízio (as duas opções: por pessoa e por vaga) + override manual.
- [ ] **Navegação entre semanas/meses** na escala (hoje as setas são ilustrativas).

## 🎨 Melhorias de UX já mapeadas
- [ ] Declutter da lista de agendados (em andamento).

## ✅ Feito recentemente
- Log de engajamento: "Ver aula" abre a aula certa, motivo embaixo do nome, telefone com copiar.
- Catálogo: criar/editar plano com resumo automático da configuração.
- Correção de datas (hoje = quarta 14/10/2026).
