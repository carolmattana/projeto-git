# Projeto Git — Ferramentas de Qualidade de Software

Página HTML simples criada para a prática de **gerência de configuração** da
disciplina de Qualidade de Software (UFSM — Sistemas de Informação,
Prof. Joel da Silva).

O objetivo é aplicar, na prática, o controle de versões com Git e o fluxo
completo no GitHub: repositório remoto, issue, branch, merge request,
integração contínua (pipeline) e publicação no GitHub Pages.

## Como executar

Não é preciso instalar nada. Basta abrir o arquivo da página no navegador:

```
public/index.html
```

Ou, se preferir servir localmente:

```bash
cd public
python -m http.server 8000
# depois abra http://localhost:8000
```

## Estrutura

```
projeto-git/
├── public/
│   ├── index.html   # página principal
│   └── style.css    # estilos da página
├── .gitignore
├── .gitlab-ci.yml   # validação (test) e publicação (GitLab Pages)
└── README.md
```

## Autor

- **Carol Mattana** — carol.mattana@acad.ufsm.br
- Sistemas de Informação — UFSM

## Links do projeto (GitLab)

- Repositório: https://github.com/carolmattana/projeto-git
- GitHub Pages: https://carolmattana.github.io/projeto-git/
- Issue: https://github.com/carolmattana/projeto-git/issues/1
