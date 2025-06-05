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
---
## 05 - Computacao e Rede:
 * Conjunto de dimensionamento em vm: É um serviço que permite criar e gerenciar um grupo de máquinas virtuais idênticas que podem ser dimensionadas automaticamente (aumentar ou reduzir) com base na demanda ou em métricas específicas, como CPU, memória ou fila de requisições. Pode ser usado quando aplicações web ou APIs que precisam atender picos de acesso. Grandes processamentos paralelos, como renderização ou análise de dados.
 * vantegens do Vm scale set: **Alta disponibilidade**, **Escalabilidade automática**, **Redução de custos**, **Integração com CI/CD, monitoramento e segurança**.

---

## 06 - IA Azure para análise de texto:
* Este serviço do Azure fornece uma IA para detectar possíveis níveis de sentimentos em textos, como por exemplo, em reclamações ou em feedback de algum serviço ou funcionalidade desenvolvida recentimente. Este serviço é bem útil para se ter uma noção de como está a adaptação de clientes a novos serviços disponibilizados ou pontos a melhorar.
* No exemplo abaixo eu coloquei um poema da Cecília Meireles para ver qual seria a análise retornada. É um poema bem melancólico e triste, porém a acertividade foi de 100% em compreender o nível sentimental a ser transmitido.
* 

![azureLenguage](https://github.com/user-attachments/assets/201ab617-9221-451a-bac6-e34d64632bde)

![azureLenguage2](https://github.com/user-attachments/assets/e077011b-d4f9-4a8e-a21f-40730c064c32)

---
## 07 - AZURE Busca cognitiva:
* Serviço este que é a soma de outros serviços, mas no geral é responsável por verificar padrões em valores de entidades em textos e documentos mais complexos. A utilização do AZURE Storage Account fica responsável por armazenar os tipos de arquivos a serem recebidos e armazená-los em núvem.

## 08 - IA Generativa Responsável:
* A IA generativa é uma área de IA voltada para a criação de novos conteúdos do zero, como por exemplo, imagens, textos, música, vídeo e códigos. Para ser possível acontecer essa IA utiliza profundos amarzenanmentos de dados, códigos complexos, como rede neurais para aprender os padrões e o relacionamento dentro dos dados.
* Logo abaixo está uma imagem como exemplo da IA Copilot, que é uma IA da microsoft me ajudando a desenvolver um código simples. Mas um aviso caso você leia até aqui. A IA chegou para auxiliar nas tomadas de decisões nas nossas vidas e não para substituir nossas decisões, como programador não utilizo muito a IA para gerar códigos, eu ainda prefiro passar algumas horas batendo cabeça com alguma task ou desafio, buscando e lendo artigos ou livros e por ultimo caso utilizo a IA para poder ter um balanceamento se aprendi algo ou ainda não estou pronto para resolver tal problema. Como dito antes a IA é para AUXILIAR no desenvolvimento de algo e não para ser uma escolha definitiva e concreta, logo que muitos códigos de IA tbm contém Erros e bugs, então fiquem atentos e revisem os códigos gerados por IA.

*  
![ia](https://github.com/user-attachments/assets/bfa74d0e-aa32-4903-9d1a-30599a89e1d9)

