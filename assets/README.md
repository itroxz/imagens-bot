# Assets - Imagens Pixel Art RPG

Este diretório contém todas as imagens pixel art customizadas criadas para o MMORasek Bot.

## 📁 Estrutura

```
assets/
├── maps/           # Imagens dos mapas (400x300px)
│   ├── floresta.png
│   ├── montanha.png
│   ├── caverna.png
│   └── cemiterio.png
└── bosses/         # Imagens dos bosses (300x300px)
    ├── guardiao_floresta.png
    ├── rei_orc.png
    ├── dragao_sombrio.png
    └── rei_morto_vivo.png
```

## 🎨 Estilo Artístico

Todas as imagens foram criadas no estilo **pixel art 16-bit RPG** usando:
- Paletas de cores temáticas para cada ambiente
- Elementos visuais característicos (árvores, montanhas, cristais, lápides)
- Personagens bosses com design único e intimidante
- Títulos integrados às imagens para identificação

## 🌲 Mapas

### Floresta Encantada
- **Cores**: Verdes naturais, marrons terrosos
- **Elementos**: Árvores pixelizadas, caminhos, grama
- **Atmosfera**: Mágica e acolhedora

### Picos Rochosos
- **Cores**: Cinzas pedregosos, azuis do céu, branco da neve
- **Elementos**: Silhuetas de montanhas em camadas, neve nos picos
- **Atmosfera**: Desafiadora e fria

### Cavernas Profundas
- **Cores**: Tons escuros, roxos dos cristais, amarelos dos brilhos
- **Elementos**: Paredes rochosas, cristais mágicos brilhantes
- **Atmosfera**: Misteriosa e perigosa

### Cemitério Sombrio
- **Cores**: Tons noturnos, cinzas das lápides, amarelo da lua
- **Elementos**: Lápides pixelizadas, névoa, lua cheia
- **Atmosfera**: Sombria e assombrada

## 👹 Bosses

### 🌳 Guardião da Floresta
- **Design**: Ent ancestral com tronco, galhos e folhagem
- **Características**: Olhos brilhantes laranjas, musgo verde
- **Atmosfera**: Protetor natural e majestoso

### 👑 Rei Orc
- **Design**: Orc massivo com armadura e coroa dourada
- **Características**: Machado de guerra, olhos vermelhos
- **Atmosfera**: Bárbaro e conquistador

### 🐲 Dragão Sombrio
- **Design**: Dragão negro com asas abertas
- **Características**: Fogo saindo da boca, chifres, olhos vermelhos
- **Atmosfera**: Lendário e devastador

### 💀 Rei Morto-Vivo
- **Design**: Esqueleto real com manto roxo
- **Características**: Coroa sombria, cetro mágico, olhos verdes brilhantes
- **Atmosfera**: Necromante e aterrorizante

## 🛠️ Como foram criadas

As imagens foram geradas programaticamente usando:
- **Canvas API**: Para desenho 2D
- **Pixel Perfect**: Cada elemento desenhado pixel por pixel
- **Paletas temáticas**: Cores específicas para cada ambiente
- **Padrões procedurais**: Elementos posicionados com algoritmos

## 📝 Geradores

Para modificar ou recriar as imagens:
- `src/utils/mapImageGenerator.js`: Gera imagens dos mapas
- `src/utils/bossImageGenerator.js`: Gera imagens dos bosses

Execute com:
```bash
node src/utils/mapImageGenerator.js
node src/utils/bossImageGenerator.js
```

---
*Imagens criadas especificamente para o MMORasek Discord Bot - Estilo pixel art RPG*
