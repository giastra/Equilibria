# Equilibria

> Uma aplicação web gamificada que ajuda os estudantes a equilibrar o desempenho académico e o bem-estar mental.

A Equilibria transforma as tarefas do dia a dia académico (entregar um trabalho, cumprir uma sessão de estudo, preparar um exame) em pequenos passos de um percurso visível, tratando o descanso e o autocuidado como parte do progresso e não como tempo perdido.

> **Estado atual:** fase inicial. O Game Design Document (GDD) está parcialmente concluído (ver [`docs/`](docs/)); o desenho da interface e a implementação ainda não começaram.

## Porquê a Equilibria?

A pressão académica leva muitos estudantes a sacrificar o descanso em nome da produtividade, o que alimenta o stress, a ansiedade e o esgotamento. Estima-se que **15% a 25% dos estudantes do ensino superior** sofram de algum tipo de problema de saúde psicológica (Universidade do Algarve, 2024).

A Equilibria pretende ajudar o estudante a passar de uma relação reativa e ansiosa com os estudos (prazos de última hora, sobrecarga, culpa por descansar) para uma relação organizada, consciente e equilibrada com o seu percurso académico.

## Ideias principais

- **Sistema de Energia.** Cada dia começa com 100 pontos de Energia. O trabalho académico consome-a; o descanso e o autocuidado recuperam-na.
- **XP, níveis e mapa virtual.** A progressão desbloqueia novas regiões, conquistas e itens de personalização do avatar.
- **Missões.** Opcionais, adaptáveis e escolhidas pelo estudante, geradas a partir de tarefas e exames.
- **Streaks flexíveis.** Um dia de descanso registado nunca quebra a streak.
- **Registo emocional.** Questionário diário (humor, stress e sono) que cria um calendário de carimbos.
- **Planeador.** Disciplinas, tarefas, exames e sessões de estudo, com temporizador Pomodoro (25 min de trabalho e 5 min de pausa).
- **Cooperação em vez de competição.** Tarefas partilhadas e metas de grupo, sem rankings nem comparações de desempenho.
- **Estatísticas.** Resumos semanais claros e visuais.

A progressão valoriza o **equilíbrio e a participação**, e não as notas elevadas, as horas estudadas ou os estados emocionais positivos.

## Funcionalidades previstas

| Área | Funcionalidades |
|---|---|
| Organização | Disciplinas, tarefas, exames, planeador de longo prazo, calendário |
| Estudo | Sessões de estudo, temporizador Pomodoro |
| Bem-estar | Registo emocional, conteúdos de gestão do stress, recursos de apoio |
| Gamificação | XP, níveis, Energia, missões, conquistas, streaks, avatar, mapa virtual |
| Social | Tarefas partilhadas, metas de grupo, partilha opcional de conquistas |

## Tecnologias

- [Vue.js](https://vuejs.org/) no front end
- [Pinia](https://pinia.vuejs.org/) para o estado global
- GitHub Pages para a demonstração (previsto)

Estado global (previsto): `userPoints`, `energy`, `currentLevel`, `unlockedRegions`, `unlockedBadges`, `avatar`, `subjects`, `tasks`, `studySessions`, `activeMissions`, `moodLog`, `streak`, `groupGoals`.

## Como começar

> Ainda não disponível. As instruções de instalação serão adicionadas com o primeiro protótipo.

```bash
# brevemente
git clone https://github.com/giastra/Equilibria.git
cd Equilibria
npm install
npm run dev
```

## Roteiro

- [x] Game Design Document, parte A (framework 6D, Teoria da Autodeterminação e Teoria do Fluxo)
- [ ] Game Design Document, restantes partes
- [ ] Wireframes e design da interface
- [ ] Estrutura inicial do projeto (Vue + Pinia)
- [ ] Onboarding e criação de avatar
- [ ] Disciplinas, tarefas e exames
- [ ] Sistema de Energia e XP
- [ ] Missões e conquistas
- [ ] Registo emocional e calendário
- [ ] Temporizador de estudo (Pomodoro)
- [ ] Mapa virtual e progressão de níveis
- [ ] Painel de estatísticas
- [ ] Tarefas partilhadas e metas de grupo
- [ ] Demonstração pública no GitHub Pages

## Documentação

- Game Design Document: ver [`docs/`](docs/)
- Demonstração: _brevemente_
- Vídeo de documentação: _brevemente_

## Equipa

Desenvolvido no âmbito da unidade curricular de *Gamificação e Narrativas Interativas* (Licenciatura em Tecnologias e Desenvolvimento Web).

- Clara Mota
- Afonso Duarte
- Giancarlo Stracquadanio
- Diogo Fernandes

## Licença

Distribuído sob a [Licença MIT](LICENSE).
