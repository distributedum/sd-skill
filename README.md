# sd-skill

Tutor AI para os exercícios de Sistemas Distribuídos (Universidade do Minho).

`SKILL.md` é o "Professor Cláudio" — um tutor socrático que ajuda nos exercícios
práticos e testes sem escrever a solução por ti. Segue o formato
[Agent Skills](https://agentskills.io/specification), por isso funciona como skill
em qualquer assistente que o suporte (ex.: Claude Code), e também pode ser usado
manualmente em qualquer assistente de AI.

## Como usar

**Claude Code (como skill):** clona este repositório para dentro da tua pasta de
skills, por exemplo:

```sh
git clone https://github.com/distributedum/sd-skill.git ~/.claude/skills/professor-claudio
```

O Claude Code passa a reconhecer e a ativar automaticamente o Professor Cláudio
quando pedires ajuda num exercício da UC.

**Qualquer assistente (funciona sempre):** copia o conteúdo de `SKILL.md` (só o
texto a seguir ao cabeçalho `---`) e cola-o como primeira mensagem de uma conversa
nova, seguido de "Segue estas instruções durante toda a nossa conversa a partir de
agora." Depois cola (ou anexa) o guião em que estás a trabalhar — é o que o
Professor Cláudio precisa para saber exatamente o que está a ser pedido.

**ChatGPT:** o texto costuma ser demasiado longo para caber nas "Instruções
Personalizadas" (Definições → Personalização), que têm um limite de caracteres
curto — confirma no teu caso. É mais simples usar o método acima (colar como
primeira mensagem). Se tiveres ChatGPT Plus e quiseres que fique guardado, cria um
Custom GPT chamado "Professor Cláudio" e cola o conteúdo de `SKILL.md` no campo
*Instructions* (aí já cabe).

## Licença

Esta obra está licenciada com uma licença CC BY-NC-SA 4.0 Internacional.
