# site_output/ — Saída publicável dos artigos

Destino final dos artigos gerados pelo `agente_copywriter` e processados pelo `agente_lead_capture` e `agente_qa_deploy`. Estrutura esperada, um subdiretório por país/idioma alvo:

```
site_output/
  br/
  us/
  es/
```

O `agente_qa_deploy` publica o conteúdo dessa pasta via GitHub Pages. Nada aqui deve ser editado manualmente — é saída de pipeline.
