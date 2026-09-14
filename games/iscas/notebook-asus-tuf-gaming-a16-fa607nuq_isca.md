# Checklist de Primeira Sessão no ASUS TUF Gaming A16

_Depois de tantas partidas que não saíam no pico de 60fps, eu descobri que tudo que precisava era de ajustes simples antes de ligar o notebook._

1. **Teste a placa gráfica no modo alto desempenho** — Acesse o NVIDIA Control Panel e selecione "Max Performance" na aba de gerenciamento de energia.
2. **Configure o resfriamento ativo** — No BIOS, ative o perfil "Gaming" e ajuste a curva de temperatura para que o ventilador entre em ação a partir de 55°C.
3. **Limpe os drivers Linux** — Use "sudo apt remove nvidia-driver-*" e depois instale a versão mais recente via PPAs para garantir estabilidade.
4. **Desative recursos visuais desnecessários** — No jogo, reduza sombras, anti-aliasing e efeitos de partículas para manter a taxa de quadros alta.
5. **Monitore o consumo de energia** — Instale o "tlp" ou "powertop" para ver se a CPU está realmente no modo turbo; ajuste se necessário.
6. **Teste a performance com benchmarks** — Execute o 3DMark Fire Strike ou Unigine Heaven para comparar antes e depois dos ajustes.

_Se quiser aprofundar nos detalhes e evitar armadilhas comuns, o guia completo cobre tudo de forma prática._