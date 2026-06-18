# Blue Loading Spinner 🔵

Animação de carregamento (loading spinner) feita com HTML, CSS e JavaScript, exibida sobre um fundo em gradiente azul.

## 📋 Sobre o projeto

Este projeto exibe uma tela de **loading animado**, composta por:
- Um fundo em gradiente nas tonalidades de azul;
- Um spinner branco em formato de anel parcial (estilo "C"), que gira continuamente para indicar carregamento em andamento.

O visual remete a telas de carregamento de sistemas operacionais e aplicativos, sendo uma boa referência para criar indicadores de loading elegantes e minimalistas.

## 🚀 Tecnologias utilizadas

- **HTML5** — estrutura da página
- **CSS3** — estilização do fundo em gradiente e animação do spinner (via `@keyframes` e `transform: rotate`, ou `border` parcial em um elemento circular)

## 📁 Estrutura do projeto

```
.
├── index.html      # Página principal com a animação
├── style.css       # Estilos do fundo, gradiente e spinner
```

> Ajuste esta estrutura conforme os arquivos reais do seu projeto.

## ▶️ Como executar

Este projeto é estático (HTML/CSS/JS), sem necessidade de instalação de dependências.

### Opção 1: Live Server (VS Code)
1. Abra a pasta do projeto no VS Code.
2. Instale a extensão **Live Server**.
3. Clique com o botão direito em `index.html` → **Open with Live Server**.
4. O navegador abrirá automaticamente em algo como:
   ```
   http://127.0.0.1:5500/index.html
   ```

### Opção 2: Abrir diretamente
Basta abrir o arquivo `index.html` direto no navegador (duplo clique).

## 🎨 Customização

Você pode ajustar facilmente:
- **Cores do gradiente de fundo** — alterando os valores de `background` (linear-gradient) no CSS;
- **Cor e espessura do spinner** — alterando `border-color` e `border-width` do elemento;
- **Velocidade da animação** — alterando o `duration` da animação CSS (`animation: spin 1s linear infinite;`, por exemplo);
- **Tamanho do spinner** — alterando `width`/`height` do elemento.

## 📸 Demonstração

Tela com fundo em gradiente azul e um spinner branco em formato de anel incompleto, girando continuamente para indicar que algo está sendo carregado.

## 📄 Licença

Este projeto é livre para uso e modificação.

---

> 💡 **Nota:** este README foi gerado a partir de uma captura de tela do projeto em execução. Para um README mais preciso (com nomes reais de arquivos, dependências exatas e instruções específicas), envie os arquivos do projeto.
