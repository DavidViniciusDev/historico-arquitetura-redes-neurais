# Histórico de Evolução dos Modelos de IA

> Uma página HTML didática que conta a história das redes neurais artificiais — do **Perceptron (1958)** aos **Transformers e LLMs modernos** — com diagramas, analogias e os artigos seminais de cada época.

## Sobre o projeto

Este repositório contém uma **página web educativa de arquivo único** (`index.html`) pensada para quem quer entender, de forma visual e progressiva, **como as arquiteturas de redes neurais evoluíram ao longo de mais de 80 anos**.

A página foi construída em torno de uma ideia simples: cada arquitetura de IA resolveu um problema deixado pela anterior. Lendo as abas em ordem, o leitor acompanha essa "conversa" entre gerações de modelos — entendendo não só o *como*, mas o *porquê* de cada inovação.

## Para quem é

- **Estudantes** começando em machine learning que querem uma visão histórica antes de mergulhar nos detalhes técnicos.
- **Profissionais de áreas correlatas** (engenharia, dados, produto) que precisam entender o vocabulário e a evolução do campo.
- **Curiosos** que ouvem falar de "Transformers", "GPT" e "LLM" e querem saber de onde tudo isso veio.
- **Professores** que precisam de um material visual e auto-contido para usar em aulas ou apresentações.

## O que a página cobre

A página está organizada em **11 abas**, cada uma dedicada a um marco da evolução:

1. **Introdução** — o que é uma rede neural e os três ingredientes universais.
2. **Perceptron (1958)** — Frank Rosenblatt e o primeiro modelo que aprendia.
3. **MLP + Backpropagation (1986)** — a descoberta que tirou as redes neurais do inverno.
4. **CNN (1998 / 2012)** — a arquitetura que aprendeu a "ver" (LeNet, AlexNet, ResNet).
5. **RNN** — quando a rede precisou de memória.
6. **LSTM / GRU (1997 / 2014)** — a engenharia de uma memória longa.
7. **Autoencoders e VAE** — aprendendo a comprimir, depois a gerar.
8. **GANs (2014)** — duas redes que se enganam até criar realidade.
9. **Seq2Seq + Attention (2014 / 2015)** — a ponte que levou ao Transformer.
10. **Transformer (2017)** — "Attention is All You Need".
11. **LLMs Modernos (2018 → hoje)** — BERT, GPT, Claude, LLaMA, Gemini e o paradigma de pré-treino + RLHF.

## O que cada aba contém

Para cada arquitetura, a página oferece:

- **Contexto histórico** — quem fez, quando e por quê.
- **Analogia do mundo real** — uma metáfora cotidiana que torna o conceito intuitivo.
- **Funcionamento técnico** — explicação em prosa, sem assumir conhecimento prévio.
- **Diagrama SVG** — figura inline mostrando a arquitetura.
- **Equações centrais** — as fórmulas-chave em destaque.
- **Prós e contras** — lado a lado, para fixar limitações e vantagens.
- **Artigos seminais** — referências bibliográficas com ano, título e autores.

## Características técnicas

- **Arquivo único** — todo o CSS, JavaScript e SVG estão embutidos no `index.html`. Nenhuma dependência externa, nenhum build, nenhum framework.
- **Funciona offline** — basta abrir o arquivo em qualquer navegador moderno.
- **Pronto para GitHub Pages** — versionar o arquivo na raiz do repositório e ativar Pages é suficiente.
- **Design responsivo** — layout adapta-se a celulares, tablets e desktops.
- **Linha do tempo visual** no topo e **navegação por abas** com rolagem suave.

## Como usar

### Visualizar localmente

```bash
# Clone o repositório
git clone https://github.com/<seu-usuario>/<nome-do-repo>.git
cd <nome-do-repo>

# Abra a página no navegador
# Windows
start index.html
# macOS
open index.html
# Linux
xdg-open index.html
```

### Publicar no GitHub Pages

1. Suba o arquivo `index.html` para o seu repositório.
2. Vá em **Settings → Pages**.
3. Em **Source**, selecione a branch (`main` ou `master`) e a pasta `/ (root)`.
4. Salve. Em poucos minutos a página estará disponível em `https://<seu-usuario>.github.io/<nome-do-repo>/`.

## Estrutura do repositório

```
.
├── index.html      # A página completa (HTML + CSS + JS + SVG, tudo embutido)
└── README.md       # Este arquivo
```

## Sugestões de uso didático

- **Em aulas:** projete a página e percorra as abas em ordem; cada aba dura entre 5 e 10 minutos de explicação.
- **Em estudo individual:** leia uma aba por dia, no ritmo histórico — a evolução fica mais clara assim.
- **Em apresentações:** a página funciona como um "deck navegável"; as analogias e diagramas seguram bem a atenção da plateia.

## Contribuições

Sugestões, correções e expansões são bem-vindas. Como o arquivo é único, basta abrir uma issue ou um pull request apontando o trecho a melhorar.

## Licença

Material didático de uso livre. Sinta-se à vontade para usar em aulas, apresentações e estudos.
