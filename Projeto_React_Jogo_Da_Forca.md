# Jogo da Forca — Projeto React

Descrição
---
Este é um projeto simples em React que implementa o clássico Jogo da Forca. A aplicação apresenta uma palavra aleatória, um desenho progressivo do boneco conforme erros, um teclado interativo com efeitos e feedback visual para acertos/erros, e telas de vitória/derrota.

Principais recursos
---
- Seleção aleatória de palavras
- Interface responsiva e estilizada com animações e hover
- Entrada por clique ou teclado físico
- Indicação visual de letras corretas e erradas
- Botão para reiniciar a partida

Como rodar
---
1. Instale as dependências:

```bash
npm install
```

2. Inicie a aplicação em modo de desenvolvimento:

```bash
npm start
```

A aplicação abrirá em `http://localhost:3000` por padrão.

Estrutura do projeto
---
- `public/` — arquivos estáticos e `index.html`.
- `src/` — código-fonte React.
  - `src/App.js` — componente principal com a lógica do jogo.
  - `src/App.css` — estilos e animações do jogo.
  - `src/index.js` — entrada da app.

Como jogar
---
1. Clique nas letras do teclado exibido ou pressione as teclas do teclado físico.
2. Cada letra errada adiciona uma parte ao boneco; após 6 erros, você perde.
3. Revele todas as letras antes de atingir o limite de erros para vencer.
4. Use o botão "Reiniciar" para jogar novamente.

Customização rápida
---
- Para alterar as palavras disponíveis, edite o array `WORDS` em `src/App.js`.
- Para mudar o número máximo de erros, altere a constante `maxWrong` em `src/App.js`.
- Para ajustar cores ou animações, edite `src/App.css`.

Próximos passos sugeridos
---
- Adicionar categorias de palavras e seleção pelo usuário.
- Persistir estatísticas de partidas no `localStorage`.
- Adicionar som e efeitos visuais (confete) na vitória.
- Internacionalização (i18n) se desejar outras línguas.

Licença
---
Sinta-se livre para usar e modificar este projeto. Adicione uma licença formal se for publicar.

Autor
---
Projeto gerado e estilizado via assistente. Edite conforme suas preferências.
---

 # Link do projeto
 https://github.com/Isabelly-Caroline/primeiro-projeto