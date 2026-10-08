# Projeto: Plano de Estudo Analista de Segurança JR

## 1\. Visão Geral e Apresentação do Projeto

O **Gemini Notebook — Plano de Estudo Analista de Segurança JR** é um assistente e parceiro interativo desenvolvido para organizar, acelerar e guiar a preparação de estudantes para o mercado de cibersegurança e exames de certificação, com foco no **CompTIA Security+ (SY0-701)** e trilhas correlatas (**Cisco CCST/CCNA**).

### Principais Funções

* **Orientação Teórica e Prática:** Esclarecimento de conceitos em Redes, Arquitetura Zero Trust, Criptografia, IAM, Resposta a Incidentes e Frameworks (NIST CSF 2.0 / ISO 27001).
* **Análise de Cenários e Logs:** Identificação de vetores de ataque em logs de servidores e firewalls (**SQL Injection, XSS, Directory Traversal**) e interpretação de evidências.
* **Estratégias de Exame:** Orientação sobre a dinâmica de questões baseadas em desempenho (**PBQs**), gestão de tempo e priorização durante a prova.
* **Geração de Conteúdo:** Elaboração de planos de estudo, resumos executivos, simulados e flashcards.
## 2\. Fontes

Abaixo está a relação completa de todas as **22 fontes** integradas ao projeto, organizadas por formato e com uma breve síntese de seu conteúdo:

---

### 📄 Documentos PDF

1. **cartilha-seguranca-internet.pdf** *Guia educativo desenvolvido pelo CERT.br abordando riscos na internet, golpes, malwares e boas práticas de proteção para usuários e dispositivos.*
2. **CISCO.pdf** *Visão geral do programa de treinamento e currículo da certificação Cisco Certified Support Technician (CCST) Cybersecurity.*
3. **CompTIA Security+ PDF PT|BR Marilia Rocha** *Material de revisão focado nos conceitos fundamentais da Security+, incluindo engenharia social, malwares, vulnerabilidades web e protocolos de defesa.*
4. **Cybersecurity Incident CISA Federal Agency.pdf** *Playbooks oficiais da CISA para resposta a incidentes e gerenciamento de vulnerabilidades em agências federais.*
5. **E-BOOK-Seguranca-da-informacao.pdf** *Livro-texto introdutório sobre segurança da informação, políticas nacionais, segurança em nuvem, privacidade de dados e recuperação de desastres.*
6. **Estrutura de Segurança Cibernética do NIST.pdf** *Guia traduzido sobre a implementação do NIST Cybersecurity Framework para gestão e redução de riscos cibernéticos.*
7. **Exemplo de Modelo de Aprendizado** *Guia de estudo estruturado para o exame CompTIA Security+ SY0-701, abrangendo a tríade CIA, estrutura AAA, tipos de controles e dicas estratégicas de prova.*
8. **Guia de estudo.pdf** *Material preparatório para a certificação Cisco CCST Networking, detalhando o modelo OSI, segmentação de rede, roteadores e switches.*
9. **Materoal de suporte.pdf** *Manual focado em controle de acesso (framework AAA), fatores de autenticação multifator (MFA), políticas de senha e funcionamento do protocolo RADIUS.*
10. **NIST Cybersecurity Framework CSF 2.0 Core.pdf** *Documento oficial do NIST CSF 2.0 organizado em 6 funções estratégicas: Govern, Identify, Protect, Detect, Respond e Recover.*
11. **principles\_approaches\_for\_security-by-design-default\_ Federal Agency.pdf** *Diretrizes internacionais sobre o desenvolvimento de softwares sob os princípios de Secure-by-Design e Secure-by-Default.*
12. **Segurança e defesa Cybernetica voltado para nações.pdf** *Coletânea acadêmica analisando a cibersegurança no contexto de segurança nacional, guerra cibernética e proteção de infraestruturas críticas.*
13. **Teoria da Aprendizagem** *Apresentação acadêmica sobre teorias psicológicas da aprendizagem (comportamentalismo, cognitivismo e humanismo) aplicadas ao ensino.*

---

### 🌐 Links e Artigos Web (URLs)

1. **Análise Sobre Performance** *Análise técnica sobre a dinâmica das questões baseadas em desempenho (PBQs) da CompTIA, diferenciando Simulações de Ambientes Virtuais.*
2. **Exemplo de modelo de Aprendizado** *Guia de estudos web detalhando os 5 domínios do exame CompTIA Security+ SY0-701 e suas respectivas ponderações na prova.*
3. **GitHub - vaamonde/ccna-v7-200-301: Curso GRÁTIS Laboratório Prático da NOVA Certificação Cisco CCNA v7 200-301** *Repositório com roteiros práticos de laboratório para preparação da certificação Cisco CCNA v7 (200-301).*
4. **Habilidades Necessárias | Any consulting** *Artigo mapeando o perfil, competências técnicas e soft skills exigidas do Analista de Segurança da Informação pelo mercado.*
5. **Habilidades Necessárias | IBSEC** *Guia do Instituto Brasileiro de Cibersegurança detalhando as 10 habilidades essenciais para profissionais em início de carreira.*
6. **Questões CompTIA Security+** *Simulado de questões de múltipla escolha com gabarito para autoavaliação nos temas do exame Security+.*

---

### 🎥 Vídeos (YouTube)

1. **Exemplo de modelo de Aprendizado** *Vídeo instrutivo orientando sobre o aprendizado de redes, sistemas operacionais e desenvolvimento de soft skills para a carreira em cibersegurança.*
2. **Questões CompTIA Security+** *Vídeo com resolução comentada de questões simuladas focadas no exame SY0-701 da CompTIA.*

---

### 📝 Textos e Notas

1. **Objetivo Principal do Professor de TI** *Prompt e diretrizes de mentoria para estruturação de planos de estudo personalizados voltados a analistas júniores.*

2. # Tópico 3: Perguntas e respostas

**Pergunta:** Qual é a diferença entre TCP e UDP?

**Resposta:**

O **TCP (Transmission Control Protocol)** e o **UDP (User Datagram Protocol)** são os dois principais protocolos que operam na Camada de Transporte (camada *Host-to-Host* do modelo TCP/IP)[1]. A diferença fundamental entre eles reside na confiabilidade, no estabelecimento de conexão e na quantidade de *overhead* de processamento e rede exigida durante a transmissão de dados[4].

---

### 1\. Transmission Control Protocol (TCP)

* **Orientado à Conexão (** **Connection-oriented** **):** Estabelece um circuito virtual e confirma a comunicação entre a origem e o destino por meio de um aperto de mão de três vias (*three-way handshake*) antes do envio de dados[6].
* **Confiabilidade e Ordenação (** **Reliable &amp; Sequenced** **):** Garante a entrega exata da informação dividindo o fluxo em segmentos numerados, exigindo confirmações de recebimento (*acknowledgments* ou ACKs), retransmitindo pacotes perdidos e aplicando controle de fluxo (*windowing*) para evitar a sobrecarga do receptor[6].
* **Overhead de Rede:** Por conter um cabeçalho mais complexo e gerenciar o estado da sessão, gera um **maior overhead** de banda e processamento[4].
* **Aplicações Típicas:** Utilizado por serviços que exigem integridade absoluta dos dados, como **HTTP (porta 80), HTTPS (porta 443), SSH (porta 22), FTP (portas 20/21), Telnet (porta 23) e SMTP (porta 25)**[13][14].

---

### 2\. User Datagram Protocol (UDP)

* **Sem Conexão (** **Connectionless** **):** Transmite os pacotes diretamente ao destino sem criar sessões prévias ou realizar contato de preparação[5].
* **Não Confiável e Não Sequenciado (** **Unreliable &amp; Unsequenced** **):** Não atribui números de sequência, não exige confirmações de recebimento e não realiza controle de fluxo ou retransmissão[6].
* **Baixo Overhead:** Por ser um protocolo leve (*thin protocol*), economiza recursos de rede e proporciona transmissões **mais rápidas e com menor latência**, sendo ideal para tráfego em tempo real, como VoIP e chamadas de vídeo[4].
* **Aplicações Típicas:** Utilizado por **TFTP (porta 69), DHCP (portas 67/68), SNMP (porta 161) e NTP (porta 123)**[13]. O **DNS (porta 53)** pode alternar entre TCP e UDP conforme o tipo de operação realizada[14].

---

### 📑 Fontes Identificadas no Projeto

* **Guia de estudo.pdf:** Apresenta a fundamentação teórica da Camada de Transporte, detalhando a estrutura de cabeçalho do TCP/UDP, o processo de *three-way handshake*, janelas de controle de fluxo e a tabela comparativa de características operacionais dos dois protocolos[1].
* **Exemplo de Modelo de Aprendizado:** Contém o mapeamento prático de portas lógicas e a atribuição de serviços e protocolos aos canais TCP e UDP para o exame CompTIA Security+[13].
