# EXPLORE ARACAJU

O Explore Aracaju é um desenvolvimento web feita para facilitar a descoberta e a localização dos principais pontos turísticos de Aracaju – SE. A plataforma permite que turistas e moradores pesquisem atrações, visualizem informações sobre os locais e explorem suas localizações por meio de um mapa interativo.

# Participantes

- Yago Felipe de Oliveira Silva
- Maria Viviane Fontes Araujo
- Kildere de Oliveira Cardozo
- Kevin de Oliveira Cardozo

# 1. Visão Geral

O **Explore Aracaju** é uma aplicação web desenvolvida para facilitar a descoberta e a localização dos principais pontos turísticos de Aracaju – SE. A plataforma permite que turistas e moradores pesquisem atrações, visualizem informações sobre os locais e explorem suas localizações por meio de um mapa interativo.

# 2. Problema

Dificuldade em localizar e acessar informações detalhadas de pontos turísticos em um único lugar.

# 2.1 Contexto

Aracaju, capital do estado de Sergipe, possui diversos pontos turísticos, culturais e de lazer que atraem visitantes e moradores. Entretanto, as informações sobre essas atrações encontram-se distribuídas em diferentes plataformas, dificultando a pesquisa e o planejamento de passeios. Nesse contexto, surge a necessidade de uma ferramenta digital que centralize essas informações e facilite o acesso aos locais turísticos.

# 2.2 Problema Identificado

O principal problema identificado é a dificuldade de encontrar, em um único ambiente, informações sobre os pontos turísticos de Aracaju, incluindo suas características e localizações. Essa dificuldade pode prejudicar a experiência dos turistas e moradores que desejam conhecer novos lugares e organizar seus passeios.

# 2.3 Soluções Existentes

Atualmente, existem plataformas como Google Maps, TripAdvisor e sites de turismo que disponibilizam informações sobre atrações turísticas. Entretanto, essas ferramentas apresentam informações gerais de diversas localidades, não sendo necessariamente direcionadas à divulgação dos pontos turísticos de Aracaju em uma plataforma específica.

# 2.4 Hipótese do MVP

A hipótese do projeto é que o desenvolvimento de uma aplicação web voltada especificamente para os pontos turísticos de Aracaju poderá facilitar a busca por atrações, centralizar informações relevantes e permitir a visualização das localizações em um mapa interativo, contribuindo para uma experiência mais prática e acessível aos usuários.

---

# 3. Público-Alvo

Turistas.

# 3.1 Perfil dos Usuários

O público-alvo da aplicação é composto por turistas que visitam Aracaju, moradores da cidade que desejam conhecer novas atrações e pessoas interessadas em explorar os pontos turísticos da região.

# 3.2 Necessidades

Os usuários necessitam de uma plataforma simples e acessível que permita pesquisar pontos turísticos, consultar informações sobre as atrações, identificar suas localizações e encontrar opções de lazer e entretenimento na cidade.

# 3.3 Cenário de Utilização

A aplicação poderá ser utilizada por meio de computadores, notebooks, tablets e smartphones, especialmente por pessoas que estejam planejando uma viagem ou procurando locais para visitar em Aracaju. O usuário poderá acessar o site, pesquisar atrações, consultar informações e visualizar os destinos em um mapa interativo.

---

# 4. Escopo do MVP

# 4.1 Funcionalidades Principais

Funcionalidade 01 – Listagem de Pontos Turísticos:** Exibir os principais pontos turísticos de Aracaju, apresentando seus nomes e informações básicas.

Funcionalidade 02 – Pesquisa de Atrações:** Permitir que o usuário pesquise pontos turísticos pelo nome.

Funcionalidade 03 – Visualização de Informações:** Apresentar informações e características dos locais selecionados.

Funcionalidade 04 – Mapa Interativo:** Permitir a visualização da localização dos pontos turísticos por meio de um mapa interativo.

---

# 5. Arquitetura da Solução

# 5.1 Visão Arquitetural

O sistema será desenvolvido como uma aplicação web utilizando HTML5, CSS3 e JavaScript. A estrutura será organizada entre a interface do usuário, responsável pela apresentação das informações, e a integração com serviços externos por meio da Overpass API, que consulta dados geográficos do OpenStreetMap. Para a apresentação das localizações, será utilizada a biblioteca Leaflet, permitindo a criação de um mapa interativo.

# 5.2 Fluxo Principal

1. O usuário acessa a página inicial do Explore Aracaju.
2. A aplicação apresenta os pontos turísticos disponíveis e permite a realização de pesquisas.
3. O JavaScript realiza consultas à Overpass API para obter informações geográficas dos locais cadastrados.
4. Os resultados são apresentados na página e suas localizações são exibidas em um mapa interativo.

---

# 6. Tecnologias Utilizadas

| Categoria | Tecnologia | Finalidade |
|---|---|---|
| Linguagem de Programação | JavaScript | Implementar funcionalidades e integração com a API. |
| Front-end | HTML5 | Estruturar o conteúdo da aplicação. |
| Front-end | CSS3 | Desenvolver o visual e a responsividade do site. |
| API Externa | Overpass API | Consultar dados geográficos e pontos de interesse. |
| Biblioteca de Mapas | Leaflet | Criar e exibir o mapa interativo. |
| Dados Geográficos | OpenStreetMap | Fornecer dados cartográficos para o mapa. |
| Ferramentas | Visual Studio Code | Desenvolver e organizar o código. |
| Controle de Versão | Git e GitHub | Gerenciar versões e armazenar o projeto. |

---

# 7. Requisitos

# 7.1 Requisitos Funcionais

- **RF01:** O sistema deverá apresentar uma lista de pontos turísticos localizados em Aracaju – SE.
- **RF02:** O sistema deverá permitir que o usuário pesquise atrações turísticas pelo nome.
- **RF03:** O sistema deverá apresentar informações básicas sobre os pontos turísticos selecionados.
- **RF04:** O sistema deverá permitir a visualização da localização das atrações em um mapa interativo.
- **RF05:** O sistema deverá consultar dados geográficos por meio de uma API externa.

# 7.2 Requisitos Não Funcionais

- **RNF01 – Desempenho:** O sistema deverá realizar consultas e apresentar informações em tempo adequado, considerando a disponibilidade da API externa.
- **RNF02 – Usabilidade:** A aplicação deverá possuir uma interface intuitiva, organizada e de fácil utilização.
- **RNF03 – Responsividade:** O sistema deverá adaptar sua interface a diferentes tamanhos de tela, incluindo computadores, tablets e smartphones.
- **RNF04 – Compatibilidade:** A aplicação deverá funcionar nos principais navegadores modernos.
- **RNF05 – Disponibilidade:** O sistema deverá apresentar mensagens adequadas caso ocorra falha na comunicação com a API externa.
