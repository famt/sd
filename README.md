# CKP7500 - Sistemas Distribuídos e Redes de Comunicação

(Também SMD0050 - Sistemas Distribuídos)

## Ciência da Computação, [Departamento de Computação](http://www.dc.ufc.br), Instituto UFC Virtual ([UFC](http://www.ufc.br))

### Instrutores

* **Professor** - Fernando Trinta ([fernando.trinta@dc.ufc.br](mailto:fernando.trinta@dc.ufc.br))
* **Professor** - Windson Viana ([windson@virtual.ufc.br](mailto:windson@virtual.ufc.br))

* **Assistente de Ensino** - Felipe Gomes ([felipegomes.mourapaiva144@gmail.com](mailto:felipegomes.mourapaiva144@gmail.com))

### Local

Aulas remotas assíncronas eventualmente as Quartas-feiras (14:00-18:00).

### Edições passadas

- Edições passadas à 2018.2, apenas no SigaA. 
- A partir de 2019.1, usar branches específicos no github

### Ementa

Um sistema distribuído é um conjunto de computadores ou entidades computacionais independentes que se apresenta a seus usuários como um sistema único e coerente. Esta disciplina busca apresentar desde conceitos básicos até desafios atuais de pesquisa relevantes relacionados à sistemas distribuídos.

### Tópicos 

Modelos e arquitetura de sistemas distribuídos, comunição entre processos, chamadas remotas: procedimentos e objetos, objetos distribuídos, sistemas de identificação, sistemas de arquivos distribuídos, sincronização de processos distribuídos, transações e concorrência, gestão de replicação de objetos, segurança e privacidade, distribuição e computação em nuvens.

### Bibliografia Sugerida

- TANENBAUM, Andrew S.; VAN STEEN, Maarten. Sistemas distribuídos: Princípios e paradigmas, 2ed. São Paulo: Prentice Hall, 2007.

- [Versão Digital - Distributed Systems 3rd edition (2017)](https://www.distributed-systems.net/index.php/books/distributed-systems-3rd-edition-2017)

- Coulouris, Dollimore, Kindberg and Blair. Distributed Systems: Concepts and Design. Edition 5, ©Addison-Wesley 2012.

- COULOURIS, George et al. Sistemas Distribuídos: Conceitos e Projeto. 5ª ed. Porto Alegre: Bookman, 2013.

### Bibliografia Complementar

- Artigos de periódicos IEEE, ACM e Springer da área de redes e sistemas distribuídos.

- CARDOSO, J. Programação de Sistemas Distribuídos em Java. 1ª. Edição, ISBN: 978-972-722-601-6: Portugal, 2008.

- RIBEIRO, U. E. Sistemas distribuídos: desenvolvendo aplicações de alta performance no linux . 1ª. Edição, Rio de Janeiro: Axcel Books , 2005.

- GARG, Vijay K. Concurrent and distributed computing in Java. John Wiley & Sons, 2005.

- [In Search of an Understandable Consensus Algorithm](https://www.usenix.org/conference/atc14/technical-sessions/presentation/ongaro)

### Bibliografia sobre Ferramentas, Frameworks e Tecnologias

- [Wireshark](https://www.wireshark.org/)

- [Eclipse](https://www.eclipse.org/downloads/packages/)

- [Conhecendo o MQTT](https://www.ibm.com/developerworks/br/library/iot-mqtt-why-good-for-iot/index.html)

### Blogs, Disciplinas, Treinamentos

### Business Cases

### Objetivos

 - Objetivo Geral

 - Objetivos Específicos

### Metodologia

Em função da pandemia de Covid-19, a metodologia utilizará uma abordagem de ensino remoto emergencial. As aulas já se encontram gravadas com os tópicos do curso. Alunos utilizarão estas aulas para estudo, do modo (horário e local) que lhes for mais conveniente. Encontros síncronos nos horários previstos para aulas presenciais serão utilizados para sanar dúvidas. 

### Pré-Requisitos

Para participar deste curso é desejável que os participantes tenham:

- **Inglês técnico** para leitura, estudo e acompanhamento das atividades propostas, uma vez que a maior parte do material disponível está em inglês.
- Conhecimento básico de redes, engenharia de software.
- Conhecimento de plataformas de desenvolvimento web;

#### Artigos
Estes artigos podem ser obtidos a partir da rede da UFC, mediante acesso ao portal de periódicos da CAPES.


#### Glossário de Ferramentas


#### Referências de outros cursos correlatos


### Avaliação
Para alunos da graduação serão realizadas três atividades e mais práticas em sala:
- 1 avaliação individual (AP1);
- 4 atividades práticas (AT1-AT4);
- 1 Seminário final (Sem1);
- A média final da disciplina será calculada por meio de uma média  das notas

**NF = [(AP1 + Sem1 + (PT1 + ... + PT4)/4)]/3**


### Plano de aulas

| Aulas      | Parte | Tópicos                      | Recursos | Tarefas/Artigos |
|:-------------:|:----:|-----------------------------|:---------:|:-----------:|
|22 Jul 2020| I | Apresentação da Disciplina. Ementa. Bibliografia. Avaliação. Metodologia. | [Slides Apresentação - PDF](https://docs.google.com/presentation/d/1qsTQLNICmc5I--f2MvAkqfhsuJ-lxy_4KxNw03OXydk/edit?usp=sharing) | - |
|22 Jul 2020| I | Fundamentos de SD (Conceito, Características, Vantagens, Desvantagens) | [Slides Fundamentos SD - PDF](https://docs.google.com/presentation/d/1nM5xKqJM-P4yHbZvgCg9PTtJuCdSStTGYPH8gwiHpqo/edit?usp=sharing) | [Roteiro de estudos revisão de redes](https://github.com/famt/sd/blob/2020.1/roteiros/Aula02_RoteiroDeEstudos-RevisaoDeRedes.pdf) |
|22 Jul 2020| I e II | Continuação Fundamentos de SD. (Conceito, Características, Vantagens, Desvantagens). | [Slides Fundamentos SD - PDF](https://docs.google.com/presentation/d/1nM5xKqJM-P4yHbZvgCg9PTtJuCdSStTGYPH8gwiHpqo/edit?usp=sharing)  | [Roteiro de estudos revisão de redes](https://github.com/famt/sd/blob/2020.1/roteiros/Aula02_RoteiroDeEstudos-RevisaoDeRedes.pdf) |
|22 Jul 2020| II | Atividade Prática de Revisão de Redes - Wireshark (AT1)| - | [Link ](https://github.com/famt/sd/blob/2020.1/praticas/aula02_Pr%C3%A1ticaWireshark_Avan%C3%A7ada2020.doc)  |
|22 Jul 2020| I e II | Modelos de Comunicação e Arquitetura | [Slides PDF](https://docs.google.com/presentation/d/11b_woecjabbineXLuXrQncKQhJ6j0PzDTvaEvtypJq0/edit?usp=sharing) | [Texto Interessante](https://towardsdatascience.com/10-common-software-architectural-patterns-in-a-nutshell-a0b47a1e9013) |
|29 Jul 2020| I e II | Modelos de Comunicação e Arquitetura | -  | [Video-Aula ](https://drive.google.com/file/d/1zJSKl0ndcJTTZhlHVAjJDGeIsr6sSfwe/view?usp=sharing) |
|05 Ago 2020| I | Envio Vídeo da atividade sobre Arquitetura de SDs (AT2) | - | - |
|05 Ago 2020| I | Modelos de Comunicação e Arquitetura(cont.) | [Slides PDF](https://docs.google.com/presentation/d/11b_woecjabbineXLuXrQncKQhJ6j0PzDTvaEvtypJq0/edit?usp=sharing) | - |
|05 Ago 2020| I | RPC/RMI e mecanismos avançados | [Slides PDF](https://docs.google.com/presentation/d/1y06Gi49f24wjCNmi43foCX-pc5hDF2eGo9k2I7kFbRA/edit?usp=sharing) | [Video-Aula](https://drive.google.com/file/d/1E1_8r0IbaXzFrRbIG3mck3w0p_LDdwlH/view?usp=sharing) & [Tarefa (AT3) - Comunicação simples](https://docs.google.com/document/d/1XOE_2dnhXEAQFUiBx-LXcrJOoFVjhW_HFgftEdQ67SU/edit?usp=sharing)|
|12 Ago 2020| II | Threads e Processos (Teoria) | [Slides PDF](https://docs.google.com/presentation/d/17-1RGQQZcE5pH2kUQZFhrMtGE_mf5kHyLvj08BNKa9g/edit?usp=sharing) | [Vídeo-Aula](https://drive.google.com/file/d/1Xb4AhNX-300LwWGbTR7iFzcwdMJkiL6R/view?usp=sharing) |
|12 Ago 2020| I e II | Threads e Processos (Prática) | - | [Exemplos IPC](https://github.com/famt/sd/blob/2020.1/exemplos_code/ExemplosThreads.zip) |
|19 Ago 2020| I e II | Algoritmos Distribuídos - Relógios Lógicos e Exclusão Mútua. | [Slides](https://docs.google.com/presentation/d/1bl51LAz48ZJC31Ynm7Kj2mtkqEWtbpKiIgjkYWcixXk/edit?usp=sharing)  | [Vídeo-Aula](https://drive.google.com/file/d/1Gv8Z5hGoCp2jm_txeuXq2pYGDIC0Xe4R/view?usp=sharing)
|26 Ago 2020| I e II | Modelos de Representação de Dados (Aula Invertida) |  [Slides](https://docs.google.com/presentation/d/1kOuOLCtfoxjaXI4qnkBc68En07XrmDi6Zbrymnhq-QI/edit?usp=sharing)  | [Roteiro Aula Invertidas](https://docs.google.com/document/d/1PVh_aoVnh3cERheUpfsz4csVLKZFGT9HI_sxPkddTcw/edit?usp=sharing) &  [Vídeo-Aula](https://drive.google.com/file/d/1Hkznpxd-YwucZQ4VsOpTS_F5iivCQc4Z/view?usp=sharing) & [Tarefas (AT4)](https://docs.google.com/document/d/1mqrGuvmrGTPytnkYvxZaNiO79YUwEMmL9ODbu6CM-gE/edit?usp=sharing)|
|02 Set 2020| I e II | Algoritmos Distribuídos - Algoritmos de Eleição | [Slides](https://docs.google.com/presentation/d/19m_Xf451JBIYeIH68XLZNgIbm6RopaI7tDvw6r3Jmw0/edit?usp=sharing) | [Vídeo-Aula Parte I](https://drive.google.com/file/d/1jeb3cdvJzqZy2sqcXXe4Tg8KYiWgCpgJ/view?usp=sharing) [Vídeo-Aula Parte II](https://drive.google.com/file/d/1h6F6cqeK9oyyWUiNIbYUOwbIgZJlcqUB/view?usp=sharing) |
|09 Set 2020| II | SOA | [Slides](https://github.com/famt/sd/blob/2020.1/slides/soa.pdf)  | [Video-Aula](https://drive.google.com/file/d/1KTfGvShLNWoqUKHCTbiRc1SG7249gHdE/view?usp=sharing) |
|09 Set 2020| II | Tira Dúvidas para Avaliação | [Estudo Dirigido](https://docs.google.com/document/d/12Df41DFg8AvknQUdyj8WYF2JWsaC5UUmPqNDoRsGthU/edit?usp=sharing) | - 
|16 Set 2020| I | Avaliação Oral  | - | - |
|23 Set 2020| I | Computação em Nuvem | [Slides](https://docs.google.com/presentation/d/1YfmZx9BHQEPICXu1crt_n2fxe1s19k72T-LXsZNGv8A/edit?usp=sharing) | [Video-Aula](https://drive.google.com/file/d/1MHqgDfl30XHZ0Dm-3oCpx62P0adF3-O_/view?usp=sharing) |
|30 Set 2020| I | Seminários |
|07 Out 2020| I | Prova Final |

