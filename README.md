# Love Language

**Love Language** é uma *visual novel* desenvolvida em Ren'Py com foco em história, interação com personagens e minigames que enriquecem a jogabilidade. O jogo mistura roteiro romântico com mecânicas adicionais — um sistema de combate basedo em turnos, um minigame de programação (drag-and-drop) e uma loja/inventário — tudo pensado para tornar as rotas dos personagens mais dinâmicas e interessantes. 

## Visão geral

Você interpreta um(a) protagonista que progride ao longo de semanas, interagindo com quatro interesses românticos (Ruby, Java, Python e Lua). Suas escolhas, ações em minigames e vitórias em batalhas aumentam pontos de afeição, desbloqueando rotas únicas e eventos finais específicos para cada personagem. O jogo foi concebido para inovar o gênero Visual Novel ao integrar mecânicas ativas (batalhas, puzzles) à narrativa principal. 

## Principais funcionalidades

* Rotas individuais para os 4 protagonistas (Ruby, Java, Python, Lua) — cada personagem possui eventos únicos e um evento final (roteiro ramificado). 
* Sistema de Afeição (pontos que afetam o desenrolar da história e desbloqueio de eventos). 
* Gameplay base dividido em ciclos: **Semana Canônica → Free-Time Event → Final de Semana** (com minigames opcionais). 
* Minigame de batalha (turnos, menu com opções, uso de habilidades e itens) implementado em `game/battlesys`. 
* Minigame **Drag-and-Drop** (puzzles de programação: *Hello World* e *BubbleSort* para Python, Java, Ruby e Lua — 8 puzzles no total). As peças são arrastáveis e travam quando colocadas na posição correta. `game/dragndrop` contém a implementação. 
* Loja / inventário para compra e uso de itens (itens consumíveis e itens únicos com contadores). 

## Tecnologias e recursos

* **Engine:** Ren'Py (Python) — todo o jogo é implementado em Ren'Py/ Python. 
* **Arte:** sprites e CGs produzidos pela equipe (Medibang e Photoshop foram usados no workflow). 

## Como jogar

* Pode-se baixar apenas a pasta "Projeto Novo Executável" e iniciar o jogo diretamente pelo arquivo ES_Weeks_Impl.exe, sem a necessidade de instalação adicional.
* Para abrir o projeto no Ren'Py Launcher, basta clonar este repositório e utilizar a pasta game, que contém todos os arquivos necessários para execução e edição do jogo dentro da engine.

## Estado do projeto

* A maior parte das features essenciais (rotas, sistema de afeição, batalha, drag-and-drop e loja) foi implementada. Algumas features desejáveis (gacha, eventos aleatórios) foram adiadas ou removidas por limitação de prazo. 
* Melhorias possíveis: polimento visual dos minigames (especialmente batalha e drag-and-drop), adição do gacha/mais itens, expansão do roteiro (mais conteúdo nas semanas), suporte a saves com múltiplas rotas completas.
