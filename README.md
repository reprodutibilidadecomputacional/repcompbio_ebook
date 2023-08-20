# Reprodutibilidade Computacional - Ebook

Work in progress. Futuramente estará disponivel em: https://reprodutibilidade-computacional.github.io/ebook/

## 🖥️ Desenvolvimento local 

Usamos o gerador de sites estático [MkDocs](https://www.mkdocs.org/) para gerar o site. Para instalar o mkdocs, use o comando:

```bash
pip install mkdocs
```

> O projeto inclui um environment.yaml para criar um ambiente conda com as dependências necessárias para o desenvolvimento. Fique a vontade para usa-lo caso já tenha familiaridade com conda.


Para testar suas alterações em seu computador use o comando:

```bash
mkdocs serve
```

Organizamos o site em um branch dedicado (gh-pages). Para gerar o site, use o comando:

```bash
mkdocs gh-deploy
```

> Essa ultima etapa poderemos tornar automática usando GitHub Actions.


## 🤝 Como contribuir

1. Faça um fork do repositório
2. Clone o seu fork do repositório para o seu computador
3. Crie um branch para a sua contribuição
4. Faça as alterações
5. Faça um ou mais commits com as alterações
6. Faça um push para o branch
7. Crie um pull request para o repositório original

Não esqueça de adicionar uma descrição para o seu pull request.
