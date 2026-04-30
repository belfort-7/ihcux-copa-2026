# CopaNaMão 📱⚽

Protótipo de baixa fidelidade do aplicativo **CopaNaMão** — app exclusivo para torcedores dentro da arena durante a Copa do Mundo 2026.

> Atividade prática — Lista de Exercícios XIII  
> Disciplina: Interação Humano Computador e UX  
> Centro Universitário UNA — Prof. Daniel Henrique Matos de Paiva

---

## 👥 Integrantes

Joao Victor Belfort Sousa Castro

---

## 🎯 Problema Focado

A dor priorizada foi a **perda de lances importantes enquanto o torcedor está fora do assento**, combinada com as **filas nos quiosques de comida**.

Esses dois problemas se retroalimentam: o torcedor precisa sair para comer, perde o gol e fica frustrado. A solução foi unir pedido de comida com entrega no assento (eliminando a fila) e uma central de replays acessível na palma da mão (eliminando o medo de perder lances).

---

## 🎨 Justificativa de Design

O design foi organizado com base em três princípios de IHC para ambientes de alta distração:

**1. Hierarquia visual agressiva**  
O placar ao vivo ocupa o topo da Home com destaque máximo (fundo escuro, números grandes) porque é a primeira informação que o torcedor busca ao olhar para o celular. Os atalhos rápidos ficam logo abaixo em grid 2x2, com ícones grandes e rótulos curtos — pensados para uso com uma mão e com o sol no olho.

**2. Fluxo de comida em 3 toques**  
Home → Cardápio → Carrinho → Confirmar. O botão de confirmação é grande, de toque único e apresenta o tempo estimado de entrega logo abaixo para reduzir a ansiedade do torcedor.

**3. Navegação fixa e previsível**  
A barra de navegação inferior com 4 ícones permanece em todas as telas, garantindo que o usuário nunca se perca no fluxo — mesmo após um gol, quando a euforia reduz a atenção.

---

## 🗺️ Fluxo do Usuário

### Pedir um lanche

1. **Home** → Toca no atalho "🍔 Pedir comida"
2. **Cardápio Digital** → Visualiza itens por categoria, toca no "+" para adicionar
3. **Carrinho** → Revisa o pedido e o endereço de entrega (assento detectado via GPS)
4. **Pagamento** → Seleciona PIX e toca em "Confirmar pedido"
5. **Notificação push** → Recebe alerta na Home quando o pedido está a caminho

### Ver um replay

1. **Home** → Toca no atalho "▶ Replays" (ou acessa pela barra inferior)
2. **Central de Replays** → Visualiza lista de lances com indicador "NOVO" para os mais recentes
3. **Seleciona o lance** → Vídeo abre em tela cheia com seletor de câmera na parte inferior

---

## 📁 Estrutura do Repositório

```
ihcux-copa-2026/
├── prototipo/
│   ├── prototipo.png
│   └── prototipo.pdf
└── README.md
```

---

## 🖥️ Telas do Protótipo

| # | Tela | Função principal |
|---|------|-----------------|
| 1 | Home / Dashboard | Placar ao vivo + atalhos rápidos + alertas de pedido |
| 2 | Mapa do Estádio | Localização GPS do usuário + pontos de interesse |
| 3 | Cardápio Digital | Lista de alimentos com preços e botão de adicionar |
| 4 | Carrinho / Pagamento | Resumo do pedido + PIX/cartão + confirmação |
| 5 | Central de Replays | Lista de lances recentes com múltiplos ângulos |

---


---

## 💬 Reflexão de IHC

> *"Em um estádio, o brilho do sol e o barulho são ruídos externos constantes. Como seu layout de baixa fidelidade garante que o usuário não se perca no fluxo enquanto comemora um gol?"*

A resposta está na **barra de navegação inferior permanente** e nos **botões de grande área de toque**. Se o torcedor agitar o celular ao comemorar um gol e a tela mudar, basta um olhar para a barra inferior para se reorientar. Além disso, o fluxo de pedido de comida nunca tem mais de 4 passos — o que garante que, mesmo interrompido, o usuário consegue concluir sem precisar reiniciar.
