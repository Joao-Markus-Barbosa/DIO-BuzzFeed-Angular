# Projeto BuzzFeed: Quiz "Herói ou Vilão?"

Contribuí em um projeto inspirado no BuzzFeed do professor Felipe Aguiar, onde você pode conferir o [código original aqui](https://github.com/felipeAguiarCode/angular-buzzfeed-quizz-clone).  

Trata-se de um quiz interativo que testa se o jogador seria um **super-herói** ou um **supervilão** com base em suas escolhas. O foco foi criar uma experiência imersiva e dinâmica para o usuário.  

### Principais Funcionalidades:
- ✅ **Responsividade Avançada** – Adaptação perfeita para celulares, tablets e desktops.
- ✅ **Estilização Imersiva** – Efeitos visuais modernos, como gradientes, blur, sombras e animações suaves.
- ✅ **Experiência Dinâmica** – Transições fluidas e feedback visual ao responder.

---

### 🔎 Como o Jogo Funciona:

#### Perguntas Temáticas:
- O quiz apresenta 5 questões sobre poderes, escolhas morais e personalidade.
- Exemplos de perguntas: 
  - "Qual superpoder você escolheria?"
  - "Quem você salvaria primeiro?"

#### Sistema de Pontuação:
- Cada resposta é marcada como "A" (Vilão) ou "B" (Herói) nos bastidores.
- No final, o algoritmo verifica qual opção (A ou B) predominou e exibe o resultado.

#### Resultado Personalizado:
- **Maioria A**: "Você seria um supervilão!" 😈
- **Maioria B**: "Você seria um super-herói!" 🦸

#### Jogar Novamente:
- Um botão de reinício permite que o usuário repita o quiz sem precisar recarregar a página.

---

### Tecnologias Utilizadas:

#### 🛠 **Frontend (Interface e Lógica)**:
- **Angular**: Framework principal para estruturação de componentes reativos.
- **TypeScript**: Tipagem estática e organização do código.
- **CSS Moderno**:
  - Grid, Flexbox, pseudo-elementos.
  - `backdrop-filter` para efeito de vidro fosco.
- **Animações CSS**: Transições suaves e efeitos de hover.

#### 📊 **Lógica do Quiz**:
- **Algoritmo de Pontuação**: Utilização do método `reduce()` para calcular as respostas predominantes.
- **JSON**: Armazenamento das perguntas e respostas em um arquivo externo.

#### 🎨 **Design Responsivo**:
- **Media Queries**: Ajustes para celulares, tablets e desktops.
- **Unidades Relativas**: Utilização de `rem`, `%`, `vw`/`vh` para escalabilidade.

---
# Funcionamento do Sistema
![GIF](/assets/Funcionamento-buzzfeed.gif)
