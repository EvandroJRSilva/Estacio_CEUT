# Repositório Estácio CEUT

Repositório central para as disciplinas e minicursos lecionados.

-----

## [Minicursos](https://github.com/evandrojrsilva/minicursos)

![GitHub last commit](https://img.shields.io/github/last-commit/evandrojrsilva/minicursos?style=for-the-badge)

Cursos breves, normalmente com 03 ou 04 aulas/partes. Geralmente ministrados durante as férias. O repositório contém, além do `pdf` das aulas, os arquivos fonte do template `beamer` utilizado e códigos fonte, caso envolva programação.

Minicursos disponíveis:

- Redes de Computadores
- Introdução ao Aprendizado de Máquina
- Introdução à Inteligência Artificial
- Introdução à Linguagem de Programação Python

-----

## Disciplinas

Materiais das disciplinas ministradas: apresentação (com datas e demais informações), slides e códigos de programação.

- [ARA0062 - Desenvolvimento Web em HTML5, CSS, JavaScript e PHP](https://github.com/EvandroJRSilva/ARA0062)

-----

## Como baixar

Abra seu terminal (e.g., prompt de comando) na pasta desejada (usando `cd`, ou abrindo o terminal a partir da pasta). Digite:

`git clone https://github.com/EvandroJRSilva/Estacio_CEUT`

Ao baixar este repositório, os demais repositórios listados (que estão como submódulos) serão baixados automaticamente. Porém, existe a possibilidade de apenas as pastas dos submódulos serem criadas, mas seus conteúdos não tenham sido baixados. Neste caso você pode escrever os seguintes comandos no terminal:

`git submodule init`

`git submodule update`

Outra maneira de baixar, garantindo que os submódulos serão baixados, com apenas um comando é:

`git clone --recurse-submodules https://github.com/EvandroJRSilva/Estacio_CEUT`

Fique atento para quaisquer modificações tanto neste repositório, quanto nos demais, para que você esteja sempre com a versão mais recente.