# Resumo das Aulas de Redes e Internet



## Aula 1 - Fundamentos de Redes



### Conceitos Básicos

- Importância das redes de computadores na vida moderna

- Benefícios: eficiência, conveniência, escalabilidade e redundância

- Compartilhamento de recursos e comunicação facilitada



### Topologias de Rede

- **Estrela**: dispositivos conectados a um ponto central

- **Barramento**: conexão linear compartilhada

- **Anel**: conexão circular entre dispositivos

- **Malha**: múltiplas conexões redundantes



### Princípios de Comunicação

- Elementos essenciais: emissor, receptor, dados, meio e protocolos

- Importância dos protocolos (TCP/IP)

- Escalabilidade: crescimento sem perda de desempenho



---



## Aula 2 - Protocolos de Comunicação



### Tipos de Protocolos

1. **Protocolos de Rede**: roteamento, endereçamento, encapsulamento

2. **Protocolos de Transporte**: TCP (confiável) e UDP (rápido)

3. **Protocolos de Aplicação**: HTTP, SMTP, FTP



### RFC (Request for Comments)

- Papel fundamental na padronização da Internet

- Importância para inovação e referência técnica

- Principais RFCs: TCP, UDP, HTTP, HTTPS, SMTP



---



## Aula 3 - Endereçamento IP e Sub-redes



\### IPv4

- Estrutura em classes

- Endereços privados

- Escassez de endereços disponíveis



### IPv6

- Formato expandido

- Vantagens sobre IPv4

- Solução para escassez de endereços



### Sub-redes

- Máscaras de sub-rede para identificação

- Benefícios: desempenho, segurança, controle de tráfego

- Ferramentas de análise: ping, traceroute



---



## Aula 4 - Serviços Web e APIs



### APIs (Application Programming Interface)

- Definição e funcionamento

- Formatos de comunicação: JSON, XML

- Integração entre sistemas



### Protocolos Web

| Protocolo | Características | Uso Ideal |

|-----------|----------------|-----------|

| **SOAP** | Complexo, robusto, XML | Sistemas empresariais |

| **REST** | Simples, leve, JSON | Aplicações web modernas |



### Arquitetura de Microsserviços

**Características:**

- Desacoplamento de serviços

- Independência tecnológica

- Escalabilidade horizontal

- Implantação contínua



**Vantagens vs Desafios:**

- ✅ Flexibilidade, agilidade, resiliência

- ⚠️ Complexidade de comunicação, orquestração, monitoramento



### Web 2.0

- Interação dinâmica com usuários

- Tecnologia AJAX

- Impacto das redes sociais



---



## Aula 5 - Sistema DNS



### Conceitos Fundamentais

- Tradução de nomes de domínio para endereços IP

- Estrutura hierárquica

- Domínios de topo (TLDs) e subdomínios



### Tipos de Servidores DNS

1. **Servidores de Resolução**: atendem requisições dos clientes

2. **Servidores Autoritativos**: armazenam registros de domínios

3. **Servidores Raiz**: topo da hierarquia DNS



### Processo de Resolução

Navegador → Servidor Resolução → Servidor Raiz → Servidor Autoritativo → IP



---



\## Aula 6 - Infraestrutura da Internet



### Arquitetura

- Internet como "rede de redes"

- Estrutura descentralizada

- Backbones: espinha dorsal da conectividade



### Componentes Principais

- **Backbones**: cabos de fibra óptica e roteadores de alta capacidade

- **IXPs** (Pontos de Troca de Tráfego): otimização e redução de latência

- Principais operadores globais e no Brasil



### Desafios e Soluções

**Problemas:**

- Congestionamento de tráfego

- Falhas de hardware

- Ataques cibernéticos



**Soluções:**

- Redundância de rotas

- Otimização de roteamento

- Monitoramento constante



---



## Aula 7 - Classificação de Redes



### Por Abrangência Geográfica



| Tipo | Alcance | Aplicação |

|------|---------|-----------|

| **PAN** | Pessoal (metros) | Bluetooth, USB |

| **LAN** | Local (até 1 km) | Escritórios, residências |

| **MAN** | Metropolitana (cidade) | Redes municipais |

| **WAN** | Longa distância (global) | Internet, intranets corporativas |



### Protocolos

- **WAN**: IP, BGP, MPLS, VPN, TCP/UDP

- **MAN**: Ethernet Metropolitana, ATM, SONET/SDH



---



## Aula 8 - Segurança de Redes



### Principais Ameaças

- **Malware**: vírus, trojans, ransomware

- **Phishing**: engenharia social

- **DoS/DDoS**: negação de serviço

- **Exploits**: vulnerabilidades de software

- **Injeção de código**: SQL Injection, XSS



### Impactos

- Interrupção de serviços

- Roubo de dados sensíveis

- Comprometimento de integridade

- Prejuízos financeiros e reputacionais



### Medidas de Proteção

1. Atualizações regulares de software

2. Testes de penetração

3. Educação e conscientização de usuários

4. Implementação de firewalls



### Firewalls

**Tipos:**

- Filtro de pacotes

- Stateful (inspeção de estado)

- Aplicação (camada 7)

- Próxima geração (NGFW)



**Funcionalidades:**

- Filtragem de tráfego

- NAT (Network Address Translation)

- Proxy e inspeção profunda



---



## Aula 9 - Segurança na Web e Criptografia



### HTTP vs HTTPS



| HTTP | HTTPS |

|------|-------|

| ❌ Dados em texto claro | ✅ Dados criptografados |

| ❌ Vulnerável a interceptação | ✅ Confidencialidade |

| ❌ Sem autenticação | ✅ Autenticação via certificado |

| ❌ Sem integridade garantida | ✅ Integridade dos dados |



\### Ataques ao HTTP

- Sniffing (interceptação)

- Man-in-the-Middle (MITM)

- Falsificação de sites

- Roubo de credenciais



### SSL/TLS

**Componentes:**

- Certificados digitais

- Autoridades Certificadoras (CAs)

- Criptografia simétrica e assimétrica

- Algoritmos: RSA, AES, SHA



**Handshake SSL/TLS:**

1. Cliente solicita conexão segura

2. Servidor envia certificado

3. Verificação do certificado

4. Troca de chaves

5. Estabelecimento de sessão criptografada



---



## Aula 10 - Tendências e Desafios



### Internet das Coisas (IoT)

**Características:**

- Dispositivos conectados em larga escala

- Sensores e atuadores inteligentes

- Integração com redes convencionais



**Desafios:**

- Escalabilidade

- Segurança

- Conectividade



**Protocolos IoT:**

- MQTT, CoAP, Zigbee, LoRaWAN



### SDN (Redes Definidas por Software)

**Conceito:**

- Desacoplamento do plano de controle e plano de dados

- Gerenciamento centralizado

- Programabilidade da rede



**Benefícios:**

- Flexibilidade na configuração

- Automação

- Redução de custos operacionais



**Casos de uso:**

- Data centers

- Provedores de serviço

- Ambientes corporativos



### Web 3.0 e Blockchain

- Descentralização de dados

- Contratos inteligentes

- Segurança aprimorada



---



# Módulo 02 - Controle de Versão com Git e GitHub



## Aula 01 - Fundamentos do Git



### O que é Git?

Sistema de controle de versão distribuído para rastreamento de mudanças no código.



### Conceitos Principais

- **Repositório**: local de armazenamento do projeto e histórico

- **Commit**: snapshot do estado do projeto em um momento

- **Staging Area**: área intermediária antes do commit



### Instalação

- **Windows**: instalação nativa ou via WSL

- **Linux/macOS**: gerenciadores de pacote (apt, brew)



### Comandos Básicos

```bash

git init          # Inicializa repositório

git add           # Adiciona arquivos ao staging

git commit        # Cria snapshot do projeto

git status        # Verifica estado dos arquivos

git log           # Visualiza histórico de commits

```



### Integração com VSCode

- Git nativo integrado

- Extensão GitLens para visualização avançada

- Terminal integrado para comandos



---



## Aula 02 - Branches



### Conceito

Linhas paralelas de desenvolvimento que permitem trabalhar em funcionalidades isoladas.



### Branch Master/Main

- Versão de produção

- Código estável e testado

- Não deve conter commits experimentais



### Fluxo de Trabalho

1. Criar branch para nova funcionalidade

2. Desenvolver e testar isoladamente

3. Fazer merge quando estável



### Comandos

```bash

git branch nome-branch      # Cria nova branch

git checkout nome-branch    # Muda para a branch

git checkout -b nome-branch # Cria e muda para branch

```



### Boas Práticas

- ✅ Criar branches para cada funcionalidade

- ✅ Manter master sempre estável

- ✅ Nomear branches descritivamente

- ❌ Evitar commits de rascunho na master



---



## Aula 03 - Repositórios Remotos e GitHub



### Repositório Remoto

Versão do projeto hospedada em servidor, permitindo:

- Backup automático

- Colaboração entre desenvolvedores

- Sincronização entre máquinas



### Comandos Remotos

```bash

git clone url        # Copia repositório remoto

git fetch           # Busca atualizações sem integrar

git push            # Envia commits locais para remoto

git pull            # Busca e integra atualizações

```



### Plataformas de Hospedagem

- **GitHub**: mais popular, integração com Actions

- **GitLab**: CI/CD integrado

- **Bitbucket**: integração com Atlassian



### Segurança no GitHub

- Autenticação de dois fatores (2FA)

- Tokens de acesso pessoal

- Chaves SSH

- Evitar senhas em texto claro



---



## Aula 04 - Pull Requests



### Conceito

Proposta de mudanças que permite revisão antes da integração ao código principal.



### Benefícios



**Comunicação:**

- Discussões integradas

- Comentários em linhas específicas

- Histórico de decisões



**Organização:**

- Aprovações obrigatórias

- Testes automatizados

- Proteção de branches



**Automação:**

- Integração com CI/CD

- GitHub Actions

- Verificações automáticas



### Fluxo de Pull Request

1. Criar branch e fazer commits

2. Push da branch para repositório remoto

3. Abrir Pull Request no GitHub

4. Revisão e discussão

5. Aprovação e merge



### Resolução de Conflitos

**Ferramentas:**

- Interface "Files Changed" do GitHub

- `git diff branch1..branch2` (dois pontos)

- `git diff branch1...branch2` (três pontos)



**Diferenças:**

- **Dois pontos (..)**: todas as diferenças entre branches

- **Três pontos (...)**: diferenças desde o ancestral comum



### Processo de Revisão

- Análise de código

- Sugestões de melhorias

- Aprovação obrigatória

- Merge após aprovação



---


## Resumo Final



### Redes e Internet

Abordamos desde fundamentos de redes e protocolos até tendências modernas como IoT e SDN, passando por segurança, infraestrutura e serviços web.



### Git e GitHub

Exploramos o controle de versão com Git, desde conceitos básicos até colaboração avançada com branches, repositórios remotos e Pull Requests.

