# Cidades Quiz

Aplicação web estática, em português, com seis perguntas de múltipla escolha sobre capitais de países. Cada questão tem uma única resposta correta. Ao concluir todas as respostas, a aplicação mostra a pontuação e disponibiliza um botão para reiniciar o quiz.

## Estrutura

```text
cidades-quizz/
├── index.html  # Estrutura, estilos e comportamento do quiz
└── README.md   # Documentação do projeto
```

O projeto foi mantido sem dependências ou etapa de build para que possa ser executado diretamente no navegador.

## Acesso online

O quiz publicado está disponível em:

<https://groffedemos.github.io/cidades-quizz/>

## Execução

Abra `index.html` em um navegador moderno.

## Funcionamento

1. Selecione uma alternativa em cada uma das seis perguntas.
2. Clique em **Ver resultado**.
3. Consulte a quantidade de acertos ou clique em **Fazer o quiz novamente** para reiniciar.

## Publicação

Os pushes para a branch `main` acionam o workflow do GitHub Actions que publica o site no GitHub Pages. Também é possível executar o deploy manualmente pela aba **Actions**, selecionando o workflow **Deploy static site to Pages** e clicando em **Run workflow**.
