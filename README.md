# site_output/ — Saída publicável dos artigos

Destino final dos artigos gerados pelo `agente_copywriter` e processados pelo `agente_lead_capture` e `agente_qa_deploy`. Desde a ETAPA 3 (PBN Hub Multi-Tenant, ver `_memoria/estrategia.md` e `agentes/README.md`), a estrutura é um subdiretório por **hub de nicho** (nunca por país, nunca genérico) — cada hub com seu Pillar Post, Cluster Posts, `sitemap.xml` próprio e páginas legais (Termos/Privacidade):

```
site_output/
  musica/
    curso-x-vale-a-pena.html      (Pillar Post)
    quanto-tempo-leva-pra-x.html  (Cluster Post)
    termos.html
    privacidade.html
    sitemap.xml
  pets/
  culinaria/
  assets/
  sitemap.xml   (global, cobre todo o site_output/)
  robots.txt
```

O hub de cada produto é resolvido/criado por `agentes/mapeamento_hub.py` a partir do nicho/micronicho real (`_memoria/hubs_nicho.json`); nunca cai numa pasta genérica tipo `geral`/`reviews`. O `agente_qa_deploy` publica o conteúdo dessa pasta via GitHub Pages. Nada aqui deve ser editado manualmente — é saída de pipeline.
