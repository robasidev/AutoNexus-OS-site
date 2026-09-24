# Checklist rápido para otimizar seu ASUS TUF A16 no Linux

_Quando acessei o notebook, os jogos travavam e a tela piscava. Descobri que o Linux KeepOS precisava de alguns ajustes práticos._

1. **Instale drivers NVIDIA** — Baixe o pacote oficial da NVIDIA e instale via terminal: sudo pacman -S nvidia nvidia-utils. Reinicie para que o driver carregue corretamente.
2. **Configure resolução e taxa** — Abra o gerenciador de display, escolha 1920x1080 e ative 144Hz. Salve as alterações e teste com um jogo de teste.
3. **Habilite o modo de jogo** — Edite /etc/systemd/system/gameservice.service para incluir "ExecStart=/usr/bin/gamescope" e ative com systemctl enable --now gameservice. Isso prioriza recursos do sistema para jogos.
4. **Instale monitoramento de desempenho** — Instale o pacote gkrellm ou Conky: sudo pacman -S gkrellm. Configure para exibir FPS, temperatura da GPU e uso da CPU.
5. **Mantenha kernel e drivers atualizados** — Verifique atualizações regulares com sudo pacman -Syu. Se notar queda de desempenho, experimente versões mais recentes do kernel que tragam melhorias para hardware AMD.

_Se quiser aprofundar e resolver cada detalhe, confira o guia completo._