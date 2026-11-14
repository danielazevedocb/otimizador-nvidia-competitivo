# Otimizador NVIDIA Competitivo

Skill para Claude Code que configura PC com GPU NVIDIA para FPS competitivo (CS2, Valorant, Fortnite, Apex, Warzone, Overwatch 2) replicando o setup de jogadores profissionais: driver, Windows, monitor, mouse e ajustes in-game.

## Instalação

Clone o repositório e copie a pasta da skill.

**Windows (PowerShell):**

```powershell
git clone https://github.com/danielazevedocb/otimizador-nvidia-competitivo.git
Copy-Item -Recurse .\otimizador-nvidia-competitivo\otimizador-nvidia-competitivo "$env:USERPROFILE\.claude\skills\"
```

**Linux / macOS:**

```bash
git clone https://github.com/danielazevedocb/otimizador-nvidia-competitivo.git
cp -r otimizador-nvidia-competitivo/otimizador-nvidia-competitivo ~/.claude/skills/
```

Abra uma nova sessão do Claude Code.

## Uso

Invoque com `/otimizador-nvidia-competitivo` ou peça em linguagem natural:

- "Quero a config do TenZ no Valorant"
- "Reduzir input lag no CS2 com minha RTX 3060"

## Aviso

Valores de pro players mudam por patch e temporada. A skill busca dados atuais e cita a fonte, mas confirme antes de aplicar. Ajustes de driver e Windows são reversíveis; crie ponto de restauração antes. Resultados variam por hardware: meça antes e depois.

## Licença

MIT © 2026 BB8FPS. Veja [LICENSE](LICENSE).
