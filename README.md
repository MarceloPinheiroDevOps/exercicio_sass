# Projeto SASS - Layout Responsivo

Um projeto desenvolvido para praticar conceitos de SASS/SCSS com foco em design responsivo e boas práticas de CSS.

## 📋 Sobre o Projeto

Este projeto demonstra a implementação de um layout responsivo para uma página de produtos utilizando SASS como pré-processador CSS. O layout se adapta a diferentes tamanhos de tela (desktop, tablet e mobile) com um sistema de grid flexível.

## 🚀 Tecnologias Utilizadas

- **SASS/SCSS** - Pré-processador CSS
- **CSS Grid** - Sistema de layout
- **Flexbox** - Alinhamento e distribuição
- **Media Queries** - Design responsivo
- **Node.js** - Ambiente de execução
- **npm** - Gerenciador de pacotes

## 📁 Estrutura do Projeto

```
projeto/
├── source/
│   ├── config/
│   │   ├── _reset.scss
│   │   └── _variaveis.scss
│   └── main.scss
├── main.css (gerado automaticamente)
├── package.json
├── .gitignore
└── README.md
```

## 🔧 Instalação e Configuração

1. **Clone o repositório:**
```bash
git clone https://github.com/seu-usuario/projeto-sass.git
cd projeto-sass
```

2. **Instale as dependências:**
```bash
npm install
```

3. **Execute o SASS em modo watch:**
```bash
npm run sass
```

## 📱 Breakpoints Responsivos

O projeto utiliza os seguintes breakpoints:

- **Desktop:** Acima de 1024px - 3 colunas (32.66% cada)
- **Tablet:** Até 1023px - 2 colunas (48% cada)
- **Mobile:** Até 767px - 1 coluna (layout em bloco)

## 🎨 Características do Layout

### Header
- Posicionamento sticky (sempre visível)
- Navegação flexível
- Adaptação para mobile (layout em coluna)

### Grid de Produtos
- **Desktop:** 3 colunas com gap de 1%
- **Tablet:** 2 colunas com gap de 3%
- **Mobile:** Layout em bloco vertical

### Componentes
- Botões estilizados com hover
- Imagens responsivas
- Cards de produtos com bordas arredondadas

## 📦 Scripts Disponíveis

```json
{
  "scripts": {
    "sass": "sass --watch source/main.scss main.css",
    "sass:build": "sass source/main.scss main.css",
    "sass:dev": "sass --watch source/main.scss main.css --style=expanded"
  }
}
```

## 🔍 Funcionalidades SASS Utilizadas

- **@use** - Importação modular
- **Variáveis** - Cores e breakpoints
- **Nesting** - Aninhamento de seletores
- **Mixins** - Reutilização de código
- **Partials** - Organização modular

## 🎯 Aprendizados

Este projeto aborda:

- ✅ Configuração de ambiente SASS
- ✅ Organização modular de arquivos
- ✅ Design responsivo com Grid CSS
- ✅ Posicionamento sticky
- ✅ Boas práticas de CSS
- ✅ Uso de variáveis SASS
- ✅ Media queries eficientes

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer fork do projeto
2. Criar uma branch para sua feature
3. Commitar suas mudanças
4. Fazer push para a branch
5. Abrir um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Seu Nome**
- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- LinkedIn: [Seu Nome](https://linkedin.com/in/seu-perfil)

---

⭐ Se este projeto te ajudou, considere dar uma
