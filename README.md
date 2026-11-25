# Hard Copy — Copywriting Narrativo em 4 Atos (Kishōtenketsu)

> **Skill para Agentes de IA (Claude Code, Cursor, Codex, Antigravity e LLMs)**  
> Estrutura narrativa que vende contando uma história onde o produto não é o assunto até o terceiro ato.

O formato **Hard Copy** é baseado na estrutura clássica de 4 atos (**Kishōtenketsu**):
1. **Ki (Abertura / Lead)**: Começa sempre por uma dor SEMELHANTE, nunca pela dor direta que o produto resolve. Máxima retenção nos primeiros 2 minutos.
2. **Shō (Desenvolvimento)**: Personagens com nomes próprios (protagonista ~60%, antagonista/dor ~20%, NPCs funcionais) e pistas ocultas plantadas desde o início.
3. **Ten (Plot Twist / Revelação)**: Junção da dor semelhante à real, quebra de contexto e introdução do mecanismo único sem autoelogio ("analogia da pizzaria").
4. **Ketsu (Oferta / Pitch)**: Empilhamento de valor em 3 camadas, proibição da palavra "bônus", preço limpo e fechamento calmo sem escassez teatral.

---

## 🚀 Como Instalar

### Opção 1: Claude Code (Global)
Para disponibilizar a skill globalmente em qualquer terminal do Claude Code:
```bash
git clone https://github.com/Labastia/hard-copy.git ~/.claude/skills/hard-copy
```

### Opção 2: Claude Code (No Projeto Local)
Para usar dentro de um projeto específico:
```bash
git clone https://github.com/Labastia/hard-copy.git .claude/skills/hard-copy
```

### Opção 3: Cursor, Windsurf, Antigravity ou Codex
Copie a especificação da skill para a pasta de contexto do seu agente:
```bash
mkdir -p .agents/skills/hard-copy
cp SKILL.md .agents/skills/hard-copy/
```

---

## 💡 Como Usar com a IA

Uma vez instalada, o agente ativa o protocolo sempre que você pedir uma VSL, página de vendas, roteiro narrativo ou revisão de copy.

### Exemplos de comandos / prompts:

- **Criar roteiro do zero:**
  > "Use a skill hard-copy para criar o roteiro de uma VSL de 7 minutos. Subnicho: transição de carreira para profissionais sêniores. Mecanismo único: método reverso de competências."

- **Auditar ou reescrever Lead de alta retenção:**
  > "Analise os primeiros 2 minutos do meu roteiro usando o checklist do Ato 1 da skill hard-copy e reescreva usando o arquétipo Absurdo + Amnésia."

- **Estruturar Oferta em 3 Camadas:**
  > "Monte a oferta do meu produto usando o Ato 4 da skill hard-copy, sem a palavra 'bônus' e eliminando falsa escassez."

---

## 📂 Estrutura do Repositório

- `SKILL.md`: Documentação e regras operacionais completas para agentes de IA.
- `referencia/exemplo-comentado.md`: Anatomia comentada de uma VSL completa passo a passo nos 4 atos.

---

## 📜 Licença

MIT License — Livre para uso pessoal e comercial.
