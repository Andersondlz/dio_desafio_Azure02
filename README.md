# Desafio: Criação e Configuração de Máquina Virtual no Azure

## Descrição do Desafio

Este desafio tem como objetivo praticar o processo completo de criação e configuração de uma máquina virtual utilizando o portal do Microsoft Azure. Através desta experiência, busca-se compreender e vivenciar os benefícios da computação em nuvem, explorando os recursos e serviços oferecidos pela plataforma Azure.

## Por que o Azure se destaca?

O Microsoft Azure oferece uma gama de vantagens que o tornam uma excelente escolha para hospedar máquinas virtuais e outras cargas de trabalho. Algumas das principais características incluem:

* **Escalabilidade:** O Azure permite aumentar ou diminuir os recursos da sua máquina virtual (CPU, memória, disco) de forma rápida e fácil, conforme a demanda da sua aplicação. Isso garante que você tenha sempre a capacidade computacional necessária, evitando gargalos em picos de uso e otimizando custos em períodos de menor demanda.

* **Elasticidade:** Similar à escalabilidade, a elasticidade permite que a infraestrutura se adapte automaticamente às variações de carga de trabalho. Você pode configurar regras de autoescalonamento para que novas instâncias de máquinas virtuais sejam adicionadas ou removidas automaticamente em resposta a métricas de desempenho, garantindo a disponibilidade da sua aplicação sem intervenção manual constante.

* **Confiabilidade:** A infraestrutura global do Azure é projetada para oferecer alta disponibilidade. Através de zonas de disponibilidade e regiões emparelhadas, o Azure garante que seus serviços permaneçam online mesmo em caso de falhas de hardware ou outros imprevistos. SLAs (Service Level Agreements) robustos oferecem garantias de tempo de atividade para suas máquinas virtuais.

* **Previsibilidade de Custos:** O Azure oferece diversas opções de precificação, incluindo pagamento por uso, instâncias reservadas e planos de economia. Isso permite que você escolha o modelo que melhor se adapta às suas necessidades e orçamento, tornando os custos mais previsíveis e controláveis. Ferramentas de gerenciamento de custos e orçamentos também auxiliam no acompanhamento e otimização dos gastos.

* **Segurança:** A segurança é uma prioridade no Azure, com múltiplas camadas de proteção física e lógica. O Azure oferece recursos avançados como o Azure Security Center, Azure Defender e Azure Sentinel para ajudar a proteger suas máquinas virtuais contra ameaças, gerenciar vulnerabilidades e garantir a conformidade com regulamentações.

* **Governança:** O Azure fornece ferramentas robustas de governança que permitem controlar e organizar seus recursos de forma eficiente. Azure Policy, Azure Resource Manager (ARM) e grupos de gerenciamento facilitam a aplicação de políticas de segurança, conformidade e custos em toda a sua infraestrutura na nuvem.

* **Gerenciabilidade:** O portal do Azure oferece uma interface gráfica intuitiva para criar, configurar e monitorar suas máquinas virtuais. Além disso, o Azure CLI (Command-Line Interface) e o Azure PowerShell permitem automatizar tarefas de gerenciamento, facilitando a administração em larga escala e a integração com outras ferramentas de DevOps.

## Passos para Criar e Configurar a Máquina Virtual

(Aqui você pode listar os passos que você seguiu para criar e configurar a sua máquina virtual no Azure. Por exemplo:)

1.  Acessar o portal do Azure ([https://portal.azure.com/](https://portal.azure.com/)).
2.  Criar um novo Grupo de Recursos.
3.  Pesquisar e selecionar o serviço "Máquinas Virtuais".
4.  Clicar em "Criar" e preencher as informações básicas da máquina virtual (nome, região, imagem, tamanho, etc.).
5.  Configurar o disco do sistema operacional e os discos de dados (se necessário).
6.  Configurar a rede virtual e o grupo de segurança de rede (NSG) para permitir o acesso desejado.
7.  Escolher o método de autenticação (senha ou chave SSH).
8.  Revisar e criar a máquina virtual.
9.  Conectar-se à máquina virtual (via RDP ou SSH).
10. Realizar as configurações adicionais necessárias (instalação de software, etc.).

## Diagrama Explicativo

```mermaid
graph LR
    A[Usuário] --> B(Portal do Azure);
    B --> C{Autenticação e Autorização};
    C --> D[Criação da VM];
    D --> E(Serviços de Computação do Azure);
    E --> F{Infraestrutura Física Global do Azure};
    F -- Escalabilidade --> G[Mais Recursos];
    F -- Elasticidade --> H[Adaptação Automática];
    F -- Confiabilidade --> I[Alta Disponibilidade];
    F -- Segurança --> J[Proteção Multicamadas];
    B --> K[Configuração da Rede];
    K --> L(Rede Virtual Azure);
    B --> M[Configuração de Disco];
    M --> N(Armazenamento Azure);
    B --> O[Monitoramento e Gerenciamento];
    O --> P(Azure Monitor/Azure Resource Manager);