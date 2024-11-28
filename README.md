# Compreendendo Ataques DDoS e Como Proteger Sua Rede
![Ataque DDoS](https://github.com/marrcialuiza/defesas-ciberneticas/blob/main/imagens/ddos-attack.png?raw=true)


## O que é um Ataque DDoS?
Um ataque DDoS (Distributed Denial of Service) visa interromper o funcionamento de sistemas, como servidores ou websites, sobrecarregando-os com uma quantidade massiva de tráfego, tornando-os inacessíveis para usuários legítimos.

## Tipos Comuns de Ataques DDoS
- **Ataques Baseados em Volume**: Sobrecarga de largura de banda. Exemplo: Inundações UDP.
- **Ataques de Protocolo**: Explorando vulnerabilidades em protocolos de rede. Exemplo: Inundações SYN.
- **Ataques de Camada de Aplicação**: Foco na camada onde as páginas web são geradas. Exemplo: Slowloris.

## Exemplos Famosos de Ataques DDoS
- **Bancos dos EUA, 2012**: Ataque coordenado a seis grandes bancos dos EUA.
- **Mirai e Krebs, 2016**: O site de segurança de Brian Krebs sofreu um dos maiores ataques DDoS da época, com 665 Gbps.
- **GitHub, 2018**: Ataque com 1,35 Tbps, mitigado pela Cloudflare.

## Como um Ataque DDoS é Executado
1. **Infiltração e Preparação (Botnet)**: O atacante infecta dispositivos, como câmeras ou roteadores, criando uma botnet para controlar e lançar ataques.
2. **Controle e Coordenação**: A botnet é gerida via servidor de comando e controle, permitindo que os bots executem ataques coordenados.
3. **Envio de Tráfego ao Alvo**: Diversas técnicas são usadas para inundar o alvo com tráfego, como as Inundações TCP SYN.

## Prevenção e Mitigação
- **Arquitetura de Rede Forte**: Redundância para absorver e desviar ataques.
- **Análise de Tráfego**: Monitoramento constante para detectar padrões anormais.
- **Serviços de Proteção DDoS**: Ferramentas especializadas para bloquear tráfego malicioso.
- **Configuração de Firewalls**: Ajustes para descartar pacotes relacionados a ataques.

## O que Esperar de DDoS para 2025
- **Aumento de Ataques Políticos**: Motivados por interesses políticos, com foco em sites governamentais.
- **Requisitos de Conformidade Mais Rígidos**: Empresas precisam atender a regulamentações de segurança mais rigorosas.
- **Integração de IA em Ataques**: Usando inteligência artificial para tornar os ataques mais sofisticados e difíceis de mitigar.
