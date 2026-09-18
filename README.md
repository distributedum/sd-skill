# sd-skill

Tutor AI para os exercícios de Sistemas Distribuídos (Universidade do Minho).

O `SKILL.md` é o "Professor Cláudio", um tutor socrático que ajuda nos exercícios
práticos e nos testes sem escrever a solução por ti. Segue o formato
[Agent Skills](https://agentskills.io/specification), por isso funciona como skill
em qualquer assistente que o suporte (por exemplo, o Claude Code), e também pode ser
usado à mão em qualquer assistente de AI.

## Como usar

**Claude Code (como skill):** clona este repositório para dentro da tua pasta de
skills, por exemplo:

```sh
git clone https://github.com/distributedum/sd-skill.git ~/.claude/skills/professor-claudio
```

A partir daí, o Claude Code reconhece e ativa automaticamente o Professor Cláudio
sempre que pedires ajuda num exercício da UC.

**Qualquer assistente (funciona sempre):** copia o conteúdo de `SKILL.md` (só o
texto a seguir ao cabeçalho `---`) e cola-o como primeira mensagem de uma conversa
nova, seguido de "Segue estas instruções durante toda a nossa conversa a partir de
agora." Depois cola (ou anexa) o guião em que estás a trabalhar, para o Professor
Cláudio saber exatamente o que está a ser pedido.

**ChatGPT:** normalmente o texto é demasiado longo para caber nas "Instruções
Personalizadas" (Definições → Personalização), que têm um limite de caracteres
curto (confirma no teu caso). É mais simples usar o método acima, colando como
primeira mensagem. Se tiveres ChatGPT Plus e quiseres que fique guardado, cria um
Custom GPT chamado "Professor Cláudio" e cola o conteúdo de `SKILL.md` no campo
*Instructions* (aí já cabe).

## Feedback

Qualquer aluno pode ajudar a tornar isto mais útil, não é preciso saber programar.
Se o Professor Cláudio te deu uma dica confusa, insistiu numa pergunta depois de já
teres percebido, foi longe demais (ou de menos) numa ajuda, ou achas simplesmente
que uma parte das instruções podia estar mais clara, abre uma
[issue](https://github.com/distributedum/sd-skill/issues) a contar o que aconteceu
(a pergunta que fizeste e a resposta que tiveste ajudam bastante). Se preferires,
propõe diretamente um pull request. Cada relato ajuda a que isto sirva melhor o
estudo e o sucesso de todos na UC.

## Licença

Esta obra está licenciada com uma licença CC BY-NC-SA 4.0 Internacional.
