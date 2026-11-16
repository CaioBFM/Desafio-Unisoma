# Desafio UniSoma 2026 — ABC Aprendiz

Sistema de otimização para distribuição de alunos entre turmas.

## Funcionalidades

- Validação e edição dos dados de alunos e turmas.
- Distribuição otimizada por turno, com equilíbrio entre turmas.
- Exportação dos resultados em Excel e PDF.

## Windows

Baixe [`ABC_Aprendiz.exe`](dist/ABC_Aprendiz.exe) na pasta `dist/` deste repositório e abra o arquivo. O aplicativo inicia no navegador e **não requer instalação de Python**.

## Tecnologias

Python, Streamlit, PuLP/CBC e PyInstaller.

## Estrutura do projeto

```text
.
├── .streamlit/
│   └── config.toml                 Configurações visuais e de execução do Streamlit.
├── assets/
│   ├── abc1024x279.webp            Arte de identidade visual usada pela interface.
│   ├── abc-logo-1024x798.webp      Logotipo usado como ícone do aplicativo.
│   └── interface.css               Estilos personalizados da interface.
├── dist/
│   └── ABC_Aprendiz.exe            Aplicativo pronto para abrir no Windows.
├── docs/
│   ├── MANUAL_USUARIO.md           Manual do usuário em formato editável.
│   └── MANUAL_USUARIO.pdf          Manual do usuário em formato PDF.
├── scripts/
│   └── generate_user_manual.py     Gera o PDF do manual a partir da documentação.
├── static/
│   └── abc-aprendiz-identity.txt   Identifica o servidor local iniciado pelo launcher.
├── ABC_Aprendiz.spec              Configuração do PyInstaller para gerar o executável.
├── app.py                         Valida planilhas, otimiza a distribuição e prepara resultados.
├── launcher.py                    Inicia o aplicativo local e abre a interface no navegador.
├── pdf_report.py                  Monta os relatórios de distribuição em PDF.
├── requirements.txt               Lista as dependências Python do projeto.
├── streamlit_app.py               Implementa as telas e interações da aplicação.
├── .gitattributes                 Define regras de tratamento de arquivos pelo Git.
├── .gitignore                     Lista arquivos e pastas que o Git deve ignorar.
└── README.md                      Apresenta o projeto, seus recursos e esta estrutura.
```

## Participantes

- [Caio — @caiobfm](https://github.com/caiobfm)
- [Tobias Maugus — @TobiasMaugus](https://github.com/TobiasMaugus)
- [Thaís — @thaisgiolopes](https://github.com/thaisgiolopes)
