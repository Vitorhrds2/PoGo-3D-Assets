# 🎮 Pokémon 3D Explorer

Um jogo web interativo em 3D para visualizar Pokémon da primeira geração!

## 🚀 Como Jogar

### Opção 1: Abrir Diretamente
Basta abrir o arquivo `index.html` no seu navegador!

### Opção 2: Servidor Local (Recomendado para carregar modelos FBX)
Para carregar os modelos FBX originais, use um servidor web local:

```bash
# Com Python 3
cd game
python -m http.server 8000

# Ou com Node.js
npx http-server

# Ou com PHP
php -S localhost:8000
```

Depois acesse: `http://localhost:8000`

## 🎯 Funcionalidades

### Interatividade 3D
- **🖱️ Rotação**: Clique e arraste para rotacionar a câmera ao redor do Pokémon
- **📱 Zoom**: Use o scroll do mouse ou os botões +/- para aproximar/afastar
- **👆 Touch**: Compatível com dispositivos móveis - toque e arraste para rotacionar, pinça para zoom

### Controles
- **🔄 Auto Rotação**: Liga/desliga a rotação automática do modelo
- **➕ Zoom In**: Aproxima a câmera
- **➖ Zoom Out**: Afasta a câmera
- **🎯 Reset**: Retorna a câmera para a posição inicial
- **💡 Iluminação**: Alterna entre 3 modos de iluminação (Normal, Dramático, Brilhante)

### Galeria de Pokémon
Selecione entre 17 Pokémon populares da primeira geração:
- Starters: Bulbasaur, Charmander, Squirtle
- Evoluções: Venusaur, Charizard, Blastoise
- Icônicos: Pikachu, Eevee
- Lendários: Mewtwo, Mew, Articuno, Zapdos, Moltres
- Outros: Gengar, Lapras, Snorlax, Dragonite

## 🛠️ Tecnologias Utilizadas

- **Three.js**: Motor 3D para renderização WebGL
- **OrbitControls**: Controles de câmera orbital
- **CSS3**: Animações e efeitos visuais
- **JavaScript ES6+**: Lógica do jogo

## 📱 Responsivo

O jogo é totalmente responsivo e funciona em:
- 💻 Desktop
- 📱 Smartphones
- 📟 Tablets

## 🎨 Características Visuais

- Partículas flutuantes douradas
- Plataforma 3D com anel brilhante
- Efeitos de brilho e sparkle
- Animação de flutuação dos modelos
- Sistema de iluminação com sombras
- Interface moderna com blur backdrop

## 📂 Estrutura

```
game/
├── index.html      # Jogo principal (tudo em um arquivo)
└── README.md       # Este arquivo
```

## 🔗 Assets 3D

Os modelos 3D estão localizados em `Pokemon-Gen1/` na raiz do repositório.
Cada Pokémon tem sua própria pasta com:
- Modelo `.fbx`
- Texturas em `tex/`
- Arquivos fonte em `source/`

## 🎮 Aproveite!

Divirta-se explorando os Pokémon em 3D! ⚡
