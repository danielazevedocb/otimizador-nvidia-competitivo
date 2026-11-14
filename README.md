# Otimizador NVIDIA Competitivo

Skill para Claude Code que configura PC com GPU NVIDIA para FPS competitivo (CS2, Valorant, Fortnite, Apex, Warzone, Overwatch 2) replicando o setup de jogadores profissionais: driver, Windows, monitor, mouse e ajustes in-game.

## Instalação

**Opção 1 — Plugin (recomendado).** Dentro do Claude Code:

```
/plugin marketplace add danielazevedocb/otimizador-nvidia-competitivo
/plugin install otimizador-nvidia-competitivo@bb8fps
```

Reinicie a sessão. Atualizações: `/plugin marketplace update bb8fps`.

**Opção 2 — Cópia manual da skill.**

Windows (PowerShell):

```powershell
git clone https://github.com/danielazevedocb/otimizador-nvidia-competitivo.git
Copy-Item -Recurse .\otimizador-nvidia-competitivo\skills\otimizador-nvidia-competitivo "$env:USERPROFILE\.claude\skills\"
```

Linux / macOS:

```bash
git clone https://github.com/danielazevedocb/otimizador-nvidia-competitivo.git
cp -r otimizador-nvidia-competitivo/skills/otimizador-nvidia-competitivo ~/.claude/skills/
```

**Claude Desktop / claude.ai:** compacte a pasta `skills/otimizador-nvidia-competitivo` em `.zip` e envie em Configurações → Capacidades → Skills.

## Uso

Invoque com `/otimizador-nvidia-competitivo` ou peça em linguagem natural:

- "Quero a config do TenZ no Valorant"
- "Reduzir input lag no CS2 com minha RTX 3060"

## Aviso

Valores de pro players mudam por patch e temporada. A skill busca dados atuais e cita a fonte, mas confirme antes de aplicar. Ajustes de driver e Windows são reversíveis; crie ponto de restauração antes. Resultados variam por hardware: meça antes e depois.

## Licença

MIT © 2026 BB8FPS. Veja [LICENSE](LICENSE).
