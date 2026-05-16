# 🛠️ Engenharia de Requisitos e Prototipagem: Sistema de Gestão para Oficina Mecânica

Este repositório reúne o desenvolvimento de ponta a ponta para a análise de negócio, mapeamento de processos e prototipagem de um sistema de software voltado para a otimização operacional de uma oficina mecânica. 

O projeto foi desenvolvido ao longo da disciplina de **Prototipagem de Sistemas Computacionais**, simulando o papel de um Analista de TI/Requisitos focado na resolução de gargalos e na melhoria da experiência do cliente.

---

## 📌 Etapa 1: Modelo de Negócio (Business Model Canvas)
Antes de pensar em código ou telas, o primeiro passo foi compreender a estratégia de mercado da organização. Utilizando a ferramenta Canvas, estruturei a proposta de valor, o relacionamento com o cliente e os canais de entrega.

* **Foco Principal:** Transparência no orçamento, agilidade na entrega de veículos e atendimento humanizado.

<img width="3090" height="1320" alt="image" src="https://github.com/user-attachments/assets/9ea96606-46fa-4376-9ec7-93048e2ffebb" />

---

## 📊 Etapa 2: Mapeamento de Processos Atual (As-Is)
Analisei a jornada atual do cliente e o fluxo de trabalho da oficina desde o momento em que o veículo chega até a entrega das chaves. Essa etapa foi fundamental para entender a rotina real e identificar onde o fluxo operacional sofria atritos.

* **Competências:** Análise de fluxos de trabalho e mapeamento de jornadas de usuário.

<img width="1340" height="740" alt="image" src="https://github.com/user-attachments/assets/c3f0e5e1-6fc3-4166-970e-f7f7d763a6ab" />

---

## 📉 Etapa 3: Modelagem de Sistemas e Solução (UML)
Com os requisitos definidos, utilizei a notação UML para mapear a arquitetura e o comportamento do sistema da oficina. Essa etapa garante a consistência técnica entre as regras de negócio e o que será desenvolvido.

### 1️⃣ Diagrama de Classes (Estrutural)
Mapeia a estrutura de dados do sistema, definendo as entidades principais como `OrdemDeServico`, `Mecanico`, `Cliente` e `Peca`, garantindo a correta relação e encapsulamento das informações.

<img width="1408" height="727" alt="image" src="https://github.com/user-attachments/assets/2a21744c-5c34-4d03-891f-47e3283710fe" />

### 2️⃣ Diagrama de Sequência (Comportamental)
Representa a troca de mensagens e a interação em tempo real entre os atores (Mecânico/Produtor Rural) e os componentes do sistema durante os fluxos críticos, como a aprovação digital de orçamentos.

<img width="1380" height="752" alt="image" src="https://github.com/user-attachments/assets/8a1e2320-d7c5-4a52-ba16-2f26126c0a54" />

### 3️⃣ Diagrama de Atividades (Comportamental)
Ilustra o fluxo lógico passo a passo dos processos dentro do software, prevendo caminhos alternativos e tomadas de decisão (como o cancelamento de uma O.S. ou o fluxo de aprovação).

<img width="1380" height="752" alt="image" src="https://github.com/user-attachments/assets/8e230a3f-fb65-4436-85cb-76653e0287e7" />

---

## 📱 Etapa 4: Prototipagem da Interface (UI/UX no Canva)
Diante de desafios técnicos com a ferramenta Figma, adotei uma postura ágil e resiliente, utilizando o **Canva** para materializar e validar as interfaces móveis do sistema da oficina de forma estável e rápida.

O design foi totalmente centrado no ser humano e orientado por requisitos funcionais e não funcionais críticos:
* **Acessibilidade e Usabilidade:** Uso estratégico de fontes ampliadas (29px) e textos em negrito para garantir uma leitura clara e sem esforço, pensando tanto nos mecânicos em campo quanto nos produtores rurais.
* **Atendimento Humanizado:** Interfaces limpas, botões intuitivos e fluxos diretos para reduzir o estresse de usuários que não têm tanta familiaridade com tecnologia.

### 📸 Telas do Protótipo Mobile
Aqui estão os mockups das principais telas da solução:

<img width="1365" height="763" alt="image" src="https://github.com/user-attachments/assets/a505f495-35e7-4608-b297-274bd16cc495" />
<img width="1122" height="628" alt="image" src="https://github.com/user-attachments/assets/3e3860ad-83eb-44d2-810a-0528bf046606" />


### 🔗 Protótipo Interativo
Você pode navegar e testar a usabilidade do sistema completo diretamente no ambiente onde o projetei:
👉 [**Clique aqui para testar o Protótipo Navegável no Canva**](https://www.canva.com/design/DAHIdn_QVj0/UnLDfxBalBqEXiHy6r7xJg/view?utm_content=DAHIdn_QVj0&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlld=hfaf2ca6629)
