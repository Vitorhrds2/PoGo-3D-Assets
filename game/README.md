# 🎮 Pokémon World - Kanto Adventure

Um jogo completo de Pokémon para navegador com mundo aberto e Pokédex interativa!

## 🚀 Como Jogar

Abra o arquivo `index.html` no navegador para acessar o launcher, ou acesse diretamente:
- **`world.html`** - Jogo de Mundo Aberto
- **`pokedex.html`** - Pokédex Interativa

## 🌍 Modo Mundo Aberto (NOVO!)

Explore a região de Kanto livremente em um mundo 2D com:

### Exploração
- Mapa grande com diferentes áreas (Pallet Town, Route 1, Viridian City, Viridian Forest)
- Movimentação livre pelo mundo
- Grama alta com encontros aleatórios
- Pokémon selvagens visíveis no mapa
- Minimapa para navegação

### Sistema de Batalha
- Batalhas por turno estilo RPG clássico
- 4 opções: Fight, Bag, Pokémon, Run
- Sistema de HP e dano baseado em stats
- Experiência e level up ao vencer
- Captura de Pokémon com Pokébolas

### Recursos do Jogo
- Party de até 6 Pokémon
- Pokédex que registra Pokémon encontrados
- Sistema de save (LocalStorage)
- Pokémon inicial aleatório (Bulbasaur, Charmander, Squirtle ou Pikachu)
- Pokébolas para captura

### Controles

| Ação | Teclado | Mobile |
|------|---------|--------|
| Mover | WASD ou Setas | D-Pad virtual |
| Interagir | A | Botão A |
| Cancelar | B ou ESC | Botão B |
| Menu | ESC | Botão Menu |

## 📱 Pokédex

Pokédex interativa com design clássico:

- **151 Pokémon** da Gen 1
- **Sprites animados** quando disponíveis
- **Stats completos** (HP, ATK, DEF, SP.A, SP.D, SPD)
- **Tipos** com cores oficiais
- **Descrições** da Pokédex
- **Altura e peso**
- **Som do grito** do Pokémon

## 🛠️ Tecnologias

- **HTML5 Canvas/CSS3**: Renderização do mundo e UI
- **JavaScript ES6+**: Engine do jogo e lógica
- **PokéAPI**: Dados e sprites oficiais
- **LocalStorage**: Sistema de save

## 📂 Estrutura

```
game/
├── index.html      # Launcher principal
├── world.html      # Jogo de mundo aberto
├── pokedex.html    # Pokédex interativa
└── README.md       # Este arquivo
```

## 🎮 Features do Mundo Aberto

### Áreas
- 🏠 **Pallet Town** - Cidade inicial
- 🛤️ **Route 1** - Primeira rota com Pokémon selvagens
- 🏙️ **Viridian City** - Cidade com Pokémon Center e Mart
- 🌲 **Viridian Forest** - Floresta com Pokémon tipo Bug

### Pokémon Selvagens
Encontre Pokémon como:
- Pidgey, Rattata, Spearow
- Ekans, Sandshrew, Nidoran
- Zubat, Oddish, Paras
- E muitos outros!

### Itens
- 💰 Pokéyen para compras
- 🔴 Pokébolas para captura

## 🔗 API

Utiliza a [PokéAPI](https://pokeapi.co/) para:
- Sprites oficiais (front e back)
- Dados de tipos e estatísticas
- Informações de moves
- Base stats para cálculos

## 📊 Assets do Repositório

O repositório contém assets 3D originais:
- **333 modelos FBX** de Pokémon
- **Texturas PNG** (Body, Eye, Mouth)
- **Arquivos C4D** para Cinema 4D
- **Efeitos** (Incense, etc.)

Estes assets podem ser usados em engines 3D como Unity ou Blender.

## 🎮 Aproveite a aventura!

Capture todos os 151 Pokémon e torne-se um Mestre Pokémon! ⚡
