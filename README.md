# Repositório Estácio CEUT

Repositório central para as disciplinas e minicursos lecionados.

-----

## [Minicursos](https://github.com/evandrojrsilva/minicursos)

Cursos breves, normalmente com 03 ou 04 aulas/partes. Geralmente ministrados durante as férias. O repositório contém, além do `pdf` das aulas, os arquivos fonte do template `beamer` utilizado e códigos fonte, caso envolva programação.

Minicursos disponíveis:

- [Redes de Computadores](https://github.com/EvandroJRSilva/Minicursos/tree/main/Redes)
- [Introdução ao Aprendizado de Máquina](https://github.com/EvandroJRSilva/Minicursos/tree/main/Intro_ML)
- [Introdução à Inteligência Artificial](https://github.com/EvandroJRSilva/Minicursos/tree/main/Introdução_IA)
- [Introdução à Linguagem de Programação Python](https://github.com/EvandroJRSilva/Minicursos/tree/main/Intro_Python)

-----

## Disciplinas

Materiais das disciplinas ministradas: apresentação (com datas e demais informações), slides e códigos de programação.

- [ARA0062 - Desenvolvimento Web em HTML5, CSS, JavaScript e PHP](https://github.com/EvandroJRSilva/ARA0062)
- [ARA0066 - Paradigmas de Linguagens de Programação em Python](https://github.com/EvandroJRSilva/ARA0066)
- [ARA0095 - Desenvolvimento Rápido de Aplicações em Python](https://github.com/EvandroJRSilva/ARA0095)
- [ARA0168 - Tópicos de Big Data em Python](https://github.com/EvandroJRSilva/ARA0168)
- [ARA0301 - Programação de Microcontroladores](https://github.com/EvandroJRSilva/ARA0301)
- [ARA0370 - Protocolos de Redes de Computadores](https://github.com/EvandroJRSilva/ARA0370)
- [CCT0695 - Programação II](https://github.com/EvandroJRSilva/CCT0695)

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