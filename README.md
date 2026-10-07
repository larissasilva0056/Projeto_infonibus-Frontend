### 2. README para o Repositório do Frontend (`preposto_front`)

```markdown
# InfoOnibus - Painel Frontend (SISMOB / SEMOB-DF)

Interface web interativa para monitoramento em tempo real de linhas, frotas e itinerários do transporte público do Distrito Federal.

---

## Sobre o Projeto

O frontend do InfoOnibus é uma aplicação desenvolvida em React com foco em desempenho, responsividade e experiência do utilizador (UI/UX). A interface integra mapas interativos para exibição de trajetos georreferenciados e monitoramento de veículos em tempo real.

---

## Tecnologias Utilizadas

- React / TypeScript
- React-Leaflet & Leaflet (Mapeamento cartográfico e polylines)
- Tailwind CSS / Estilização modular
- Lucide React (Biblioteca de ícones)
- LocalStorage (Gestão persistente de linhas favoritas)

---

## Principais Funcionalidades

- **Pesquisa Dinâmica**: Consulta otimizada por número ou nome de linha, com exibição de tarifas e detalhes institucionais.
- **Gestão de Favoritos**: Armazenamento local no navegador para acesso rápido às linhas mais consultadas.
- **Mapeamento em Tempo Real**: Renderização de trajetos em formato GeoJSON sobre a malha viária do DF e marcadores personalizados de frotas ativas com atualização periódica.
- **Abas Informativas**: Navegação detalhada por horários de partida, itinerários descritivos, dados oficiais e estado da frota (prefixos, velocidade e sinal GPS).
- **Design Responsivo**: Adaptado para computadores e dispositivos móveis, com navegação fluida em ecrãs de diferentes dimensões.

---

## Instalação e Execução

1. Instale as dependências do projeto:
   ```bash
   npm install
Configure a URL base da API no serviço de configuração de rede.

Inicie a aplicação em modo de desenvolvimento:

Bash
npm run dev
Licença
Desenvolvido para fins institucionais e operacionais no âmbito da Secretaria de Transporte e Mobilidade do Distrito Federal (SEMOB-DF).
