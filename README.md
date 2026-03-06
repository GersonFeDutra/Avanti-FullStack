# Problema: Banco de Trocas de Conhecimento

## Objetivo

Desenvolver uma aplicação web funcional que permita registrar, visualizar e gerenciar
ofertas de conhecimento. A aplicação deve possibilitar o cadastro de pessoas dispostas a
compartilhar um conhecimento, a publicação das ofertas e a consulta dessas informações
de forma simples e intuitiva.

<details>

<summary>Contexto</summary>

Muitas pessoas desejam aprender novas habilidades, mas não possuem recursos
financeiros para pagar cursos, aulas particulares ou mentorias. Ao mesmo tempo, essas
mesmas pessoas possuem conhecimentos que poderiam ser compartilhados com outras.
Atualmente, essa troca acontece de forma desorganizada, por meio de redes sociais ou
grupos de mensagens, dificultando a busca e o acompanhamento das ofertas disponíveis.
Com o objetivo de tornar esse processo mais acessível e organizado, será desenvolvida
uma aplicação web que permita o cadastro e a visualização de conhecimentos oferecidos
por pessoas da comunidade, facilitando a conexão entre quem quer ensinar e quem quer
aprender.

</details>

## Instalação

Faça um clone deste repositório usando:

```bash
git clone --recurse-submodules git@github.com:GersonFeDutra/Avanti-FullStack.git
```

Ou atualize-os após o clone com:

```bash
git submodule update
```

Cada sub-módulo possui o seu próprio `README.md` com instruções de instalação e execução.

> [!TIP] Se você estiver no **Linux** basta executar o comando abaixo no seu terminal:
>
> ```bash
> for dir in back front; do
>   cd ./$dir
>   chmod +x ./scripts/setup.sh
>   ./scripts/setup.sh
>   cd ..
> done
> ```

### Requisitos

- Node
- Docker
