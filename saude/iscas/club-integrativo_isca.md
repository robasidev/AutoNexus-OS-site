# Checklist: Integração Rápida dos Mods de Armadura

_Já cansou de ter mods que não se encaixam nos sistemas de armadura? Eu já passei por isso e encontrei um caminho que funciona rápido._

1. **Confirme a Compatibilidade do Mod** — Verifique a versão do mod e compare com a sua base de armadura. Se não bater, procure a versão correta antes de instalar.
2. **Ajuste o Arquivo de Configuração** — Edite o config.yaml adicionando o caminho do mod e habilitando as flags necessárias. Salve e feche.
3. **Teste em Ambiente de Staging** — Inicie o servidor em staging e verifique se o mod carrega sem erros. Use logs para identificar problemas.
4. **Integre os Dados de Armadura** — Combine as tabelas do mod com as existentes, garantindo chaves únicas e sem duplicatas. Rode scripts de migração se necessário.
5. **Implante e Monitore** — Coloque o mod na produção, habilite a rota de monitoramento e verifique métricas de desempenho. Ajuste se houver queda.

_Quer ir mais fundo? Veja o guia completo de integração no Club Integrativo._