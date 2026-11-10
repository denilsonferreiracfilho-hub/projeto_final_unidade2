# PlanoUni

Plataforma de estudos para universitários, feita como protótipo em **HTML e CSS**.

Projeto final da disciplina de **Desenvolvimento Front-End para Web**.

## Sobre o projeto

O PlanoUni nasceu da dificuldade de dividir o tempo de estudo entre várias disciplinas, provas e trabalhos na universidade. A proposta é que o universitário escolha suas matérias, informe os dias e horários em que pode estudar, cadastre suas provas e trabalhos e receba um cronograma semanal de estudos.

## Para quem é

Para estudantes universitários que precisam organizar a rotina de estudos entre diferentes matérias.

## Status do projeto

Esta versão é um **protótipo inicial**, construído apenas com HTML e CSS:

- Os formulários **não enviam nem guardam dados**.
- O cronograma da página **Cronograma** é um **exemplo fixo**, escrito à mão.
- O JavaScript, que faria a validação dos formulários e a geração do cronograma, **não foi usado** nesta versão.

## Páginas

| Página | Arquivo | O que mostra |
|---|---|---|
| Início | `inicio.html` | Apresentação da plataforma e como ela funcionaria |
| Cadastro | `cadastro.html` | Formulário com nome, e-mail, curso e semestre |
| Matérias | `materias.html` | Formulário para escolher as disciplinas, com sugestões |
| Disponibilidade | `disponibilidade.html` | Dias da semana e horários livres para estudar |
| Provas e trabalhos | `provas_trabalhos.html` | Formulário com tipo, matéria, data e dificuldade |
| Cronograma | `cronograma.html` | Tabela semanal de exemplo, com progresso e carga de estudo |
| Dicas de estudo | `dicas_estudo.html` | Hábitos de estudo, música para focar e vídeo de apoio |
| Perguntas frequentes | `perguntas_frequentes.html` | Dúvidas comuns em blocos que abrem e fecham |
| Sobre | `sobre.html` | Objetivo do projeto e autor |
| Contato | `contato.html` | Formulário de contato (demonstração) |
| Recursos de estudo | `recursos_estudo.html` | Links úteis para pesquisa e estudo |

Todas as páginas têm o mesmo menu de navegação, para ir de qualquer página para qualquer outra.

## Tecnologias utilizadas

- **HTML5**
- **CSS3**

## Estrutura de pastas

```
projeto/
├── README.md
├── html/      páginas do site
├── css/       estilos (base.css comum + um arquivo por página)
├── img/       imagens
├── audio/     áudio da página Dicas de estudo
└── video/     vídeo da página Dicas de estudo
```

O arquivo `base.css` reúne o estilo comum a todas as páginas. O CSS de cada página importa esse arquivo e acrescenta só o que é específico dela, como o destaque da página atual no menu.

## Como executar

Não é preciso instalar nada. Baixe o projeto e abra o arquivo `html/inicio.html` em um navegador. A partir do menu, as demais páginas podem ser acessadas.

## Próximos passos a serem realizados futuramente

- Validar os formulários com JavaScript.
- Gerar o cronograma semanal a partir das matérias, dos horários e das provas informados.
- Guardar os dados no navegador.

## Mídias

| Arquivo | Onde é usado |
|---|---|---|
| `audio/leberch-deep-concentration-263073.mp3` | Dicas de estudo | 
| Imagem da pasta `img/` | Sobre | 
| Vídeo da pasta `video/` | Dicas de estudo | 

## Autor

**Denilson Ferreira de Carvalho Filho**