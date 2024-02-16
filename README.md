# fluigdocs

## Acessando a Documentação

A documentação do projeto está disponível no seguinte endereço:

[https://isacfg.github.io/fluigdocs/](https://isacfg.github.io/fluigdocs/)

## Instruções para Configuração do Ambiente

### Configurando o Ambiente Virtual (venv)

1. Crie um ambiente virtual para o projeto. No terminal, navegue até o diretório do projeto e execute o seguinte comando:

```bash
python3 -m venv venv
```

2. Ative o ambiente virtual. No terminal, execute o seguinte comando:

#### Linux

```bash
source venv/bin/activate
```

#### Windows

```bash
venv\Scripts\activate
```

3. Instale as dependências do projeto. No terminal, execute o seguinte comando:

```bash
pip install -r requirements.txt
```

## Servindo o Projeto localmente com o MkDocs

1. No terminal, navegue até o diretório do projeto e execute o seguinte comando:

```bash
mkdocs serve
```

## Publicando a Documentação no GitHub Pages

1. No terminal, faça commit das alterações na branch main do projeto.:

```bash
git add .
git commit -m "Atualizando a documentação"
git push
```
