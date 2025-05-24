# Lab-cloud-computing-studies
Repositório apenas para fins de fixação de conhecimentos e assuntos abordados durante estudos sobre cloud computing com AZURE.

## 01 - Computacao na nuvem: 
  * Computação em nuvem é o fornecimento de recursos de TI (servidores, armazenamento, redes, bancos de dados, software, análise e mais) pela internet, de forma escalável e sob demanda, com modelo de pagamento conforme o uso.
  * A computacao em nuvem possue diferentes modelos de nuvens, como nuvem pública, privada e hibrida:
  - **Nuvem Pública**: São um modelo de computação em nuvem que disponibiliza recursos como computação, armazenamento, aplicações e infraestrutura a qualquer pessoa que queira utilizá-los, através da internet. As nuvens públicas oferecem uma alternativa acessível à infraestrutura local, pois as organizações pagam apenas pelos serviços que utilizam, sem a necessidade de investir em hardware e software. 

  - **Nuvem privada**: É um ambiente de computação em nuvem dedicado a uma única organização, onde todos os recursos de hardware e software são exclusivos e acessíveis apenas por essa organização. A nuvem privada pode ajudar a reduzir os custos de infraestrutura, pois a organização pode otimizar o uso dos recursos e evitar a necessidade de adquirir e manter equipamentos.

  - **Nuvem hibrida**:  combina uma infraestrutura local (ou nuvem privada) com uma nuvem pública. A nuvem híbrida é útil para empresas que precisam de flexibilidade e controle, escalando recursos quando necessário e mantendo dados confidenciais em locais seguros
---

## 02 - Máquinas Virtuais no AZURE:
 * As máquinas virtuais na sua forma mais simples, uma máquina virtual, ou VM, é uma versão digitalizada de um computador físico. As máquinas virtuais podem executar programas e sistemas operacionais, armazenar dados, conectar-se a redes e realizar outras funções de computação.
* fora isso a computação em nuvem possue vários benefícios como **Escalabilidade**, **Elasticidade**, **Confiabilidade**, **Previsibilidade**, **Segurança**, **Governança** e **Gerenciabilidade**. Cada um desses benefícios tem suas características
  - **Escalabilidade** :  Refere-se a capacidade de ajustar os recursos para atender à demanda.
  - **Elasticidade** : Capacidade de aumentar ou reduzir automaticamente os recursos de acordo com a demanda. Isso permite que aplicações lidem com picos de acesso sem a necessidade de comprar infraestrutura física.
  - **Confiabilidade** : Infraestrutura robusta distribuída globalmente, garantindo alta disponibilidade e recuperação de desastres. Dados são replicados entre zonas de disponibilidade e regiões, evitando perda por falhas locais.
  - **Previsibilidade** : Modelos de cobrança previsíveis com base no consumo. Ferramentas de monitoramento e análise de custos ajudam no controle orçamentário. Serviços como Azure Cost Management + Billing fornecem alertas, previsões e recomendações de otimização de custos.
  - **Segurança** : Proteção de dados com criptografia em trânsito e em repouso. A segurança na nuvem é frequentemente mais robusta que em data centers próprios.
  - **Governança** : Permite que empresas controlem quem faz o quê, onde e como, dentro do ambiente de nuvem. Ferramentas como Azure Policy, Management Groups, BluePrints e Role-Based Access Control (RBAC) garantem governança efetiva.
  - **Gerenciabilidade** : Centralização da administração de recursos em portais, APIs, CLI e automações. Monitoramento contínuo com Azure Monitor, Log Analytics e Application Insights.
---
## 03 - Tipos de Servicos na nuvem: 
 * A nuvem dispobinibiliza 3(Três) principais servicos, são eles Iaas(Infraestrutura como servico), Paas(Plataforma como servico) e Saas(Software como servico). E logo cada um tem o seu nível de controle:
 * **Iaas** : Fornece recursos de computação, armazenamento e rede sob demanda, como máquinas virtuais, servidores e armazenamento em disco. Você gerencia: Rede, servidores, sistemas operacionais, armazenamento. O provedor cuida: Da infraestrutura física (datacenters, energia, hardware).
 * **Paas** : Oferece uma plataforma para desenvolver, executar e gerenciar aplicações, incluindo hardware e software de desenvolvimento. Você gerencia: Apenas o aplicativo e os dados. O provedor cuida: Da infraestrutura, sistema operacional, runtime, servidores e banco.
 * **Saas** : Fornece software de forma online, como aplicativos de produtividade, CRM e ERP, acessíveis através de um navegador web. O provedor gerencia tudo: Infraestrutura, aplicação, dados, manutenção, atualizações. O usuário consome: O software pronto.
---
## 04 - Componentes de Arquitetura do AZURE: 
 * Pares de Região: Os pares de Região do AZURE garantem uma melhor performance e garantia de recuperação caso haja algum problema com catastrofes que não estejam a nosso alcance para serem evitadas, como o maior exemplo nos EUA são os furacões e tempestades que atingem uma boa parte da costa leste do continente, e assim derrubando e desestabilizando conexões por toda parte do país. Para isso existe a estratégia de pares de região que podem suprir e ajudar a recompor os serviços que foram afetados garantindo **Alta disponibilidade**, **Recuperação de desastre** e **Redundância dos Dados**. Como por exemplo, a região principal do Brasil é Brasil-sul(São-Paulo) e sua região pareada é Brasil-Sudeste(Rio-SP).
* Grupo de recursos: É um container lógico onde você agrupa recursos do Azure como; Bancos de dados, Maquinas virtuais, Redes, Storage e Web Apps. A sua principal finalidade é organizar recursos por projeto, aplicação ou ambiente (dev, homologação, produção).











