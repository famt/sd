# CKP7500 - Sistemas Distribuídos e Redes de Comunicação

(Também SMD0050 - Sistemas Distribuídos)

## Ciência da Computação, [Departamento de Computação](http://www.dc.ufc.br), Instituto UFC Virtual ([UFC](http://www.ufc.br))

### Instrutores

* **Professor** - Fernando Trinta ([fernando.trinta@dc.ufc.br](mailto:fernando.trinta@dc.ufc.br))
* **Professor** - Windson Viana ([windson@virtual.ufc.br](mailto:windson@virtual.ufc.br))

* **Assistente de Ensino** - Felipe Gomes ([felipegomes.mourapaiva144@gmail.com](mailto:felipegomes.mourapaiva144@gmail.com))

### Local

UFC, horário: Quartas-feiras (14:00-18:00), Bloco Didático SMD, Laboratório I.

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

A metodologia do curso constará de aulas expositivas, enriquecidas por seminários e debates com a utilização de recursos audiovisuais. As avaliações serão baseadas nas aulas, práticas e trabalhos de teórico/práticos.

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
- 1 prova escrita (AP1);
- 5 práticas (PT1-PT5);
- 1 Trabalho de Prático sobre MQTT/Sockets (TB1);
- A média final da disciplina será calculada por meio de uma média  das notas

**NF = [(AP1 + TB1 + (PT1 + ... + PT5)/5)]/3**

Para alunos da pós-graduação serão realizadas as mesmas atividades, contudo:
- Tudo que é pedido à graduação com maior número de questões, e 
- Com nível de exigência maior na correção e nos quesitos avaliados;

### Plano de aulas

| Aulas      | Parte | Tópicos                      | Recursos | Tarefas/Artigos |
|:-------------:|:----:|-----------------------------|:---------:|:-----------:|
|19 Fev 2020| I | Apresentação da Disciplina. Ementa. Bibliografia. Avaliação. Metodologia. | [Slides Apresentação - PDF](https://docs.google.com/presentation/d/1qsTQLNICmc5I--f2MvAkqfhsuJ-lxy_4KxNw03OXydk/edit?usp=sharing) | - |
|19 Fev 2020| II | Fundamentos de SD (Conceito, Características, Vantagens, Desvantagens) | [Slides Fundamentos SD - PDF](https://docs.google.com/presentation/d/1nM5xKqJM-P4yHbZvgCg9PTtJuCdSStTGYPH8gwiHpqo/edit?usp=sharing) | [Roteiro de estudos revisão de redes](https://github.com/famt/sd/blob/2020.1/roteiros/Aula02_RoteiroDeEstudos-RevisaoDeRedes.pdf) |
|26 Feb 2020| I e II | Carnaval | - | - |
|04 Mar 2020| I e II | Continuação Fundamentos de SD. (Conceito, Características, Vantagens, Desvantagens). | [Slides Fundamentos SD - PDF](https://docs.google.com/presentation/d/1nM5xKqJM-P4yHbZvgCg9PTtJuCdSStTGYPH8gwiHpqo/edit?usp=sharing)  | [Roteiro de estudos revisão de redes](https://github.com/famt/sd/blob/2020.1/roteiros/Aula02_RoteiroDeEstudos-RevisaoDeRedes.pdf) |
|11 Mar 2020| II | Atividade Prática de Revisão de Redes - Wireshark| - | [Link ](https://github.com/famt/sd/blob/2020.1/praticas/aula02_Pr%C3%A1ticaWireshark_Avan%C3%A7ada2020.doc)  |
|18 Mar 2020| I e II | Modelos de Comunicação e Arquitetura | [Slides PDF](https://docs.google.com/presentation/d/11b_woecjabbineXLuXrQncKQhJ6j0PzDTvaEvtypJq0/edit?usp=sharing) | [Texto Interessante](https://towardsdatascience.com/10-common-software-architectural-patterns-in-a-nutshell-a0b47a1e9013) |
|18 Mar 2020| I e II | Modelos de Comunicação e Arquitetura | -  | [Video-Aula ](https://fernandotrinta.my.webex.com/recordingservice/sites/fernandotrinta.my/recording/play/1f866516a3ac4a228eaac2b2e5bb7d3b) |
|25 Mar 2020| I e II | Data Carta Magna do Ceará (Estadual) | -  | - |
|01 Abr 2020| I | Encontros Universitários 2020 | - | - |
|01 Abr 2020| I | Envio Vídeo da atividade sobre Arquitetura de SDs  | - | - |
|01 Abr 2020| I | Modelos de Comunicação e Arquitetura(cont.) | [Slides PDF](https://docs.google.com/presentation/d/11b_woecjabbineXLuXrQncKQhJ6j0PzDTvaEvtypJq0/edit?usp=sharing) | - |
|08 Abr 2020| I | RPC/RMI e mecanismos avançados | [Slides PDF](https://docs.google.com/presentation/d/1y06Gi49f24wjCNmi43foCX-pc5hDF2eGo9k2I7kFbRA/edit?usp=sharing) | [Video-Aula](https://drive.google.com/file/d/1E1_8r0IbaXzFrRbIG3mck3w0p_LDdwlH/view?usp=sharing) |
|08 Abr 2020| I | Revisão e Observações gerais sobre a atividade modelos arquiteturais e estilos arquitetônicos | - | - |
|15 Abr 2020| II | Threads e Processos (Teoria) | [Slides PDF](https://docs.google.com/presentation/d/17-1RGQQZcE5pH2kUQZFhrMtGE_mf5kHyLvj08BNKa9g/edit?usp=sharing) | [Vídeo-Aula](https://drive.google.com/file/d/1UTTNa2A6OPNQkIVAcPs9usFgnHG72vek/view?usp=sharing) |
|15 Abr 2020| I e II | Threads e Processos (Prática) | - | - |
|22 Abr 2020| II | Modelo de Representação de Dados (Aula Invertida) | -  |
|29 Abr 2020| I e II | Protocol Buffer e gRPC | - | - |
|06 Maio 2020| I e II | Algoritmos Distribuídos | - | - |
|13 Maio 2020| I e II | Revisão Sockets e MQTT | Roteiro de Estudos enviado pelo SIGAA | Trabalho |
|20 Maio 2020| I | Relógios Lógicos e Exclusão Mútua. | Estudo Dirigido | - |
|20 Maio 2020| II | Tira Dúvidas para Avaliação | Estudo Dirigido | - 
|27 Maio 2020| I | Prova | Slides PDF | |
|27 Maio 2020| II | P2P, Bit Torrent e DHT | Slides PDF | - |
|03 Jun 2020| I | Consistent Hashing | Slides PDF | - |
|03 Jun 2020| II | SOA | Slides SOA  | - |
|10 Jun 2020| I | Apresentação Trabalho de Socket e MQTT + Entrega Prova 1 | - | - |
|10 Jun 2020| II | WebServices. Restfull/Microsserviços | - | - |
|17 Jun 2020| I e II | Computação em Nuvem e Microsserviços| Slides Cloud PDF / Slides Virtualização PDF | - |
|24 Jun 2020| I e II | Blockchain - Aula Invertida | Slides PDF | Link da Prática |
|01 Jul 2020| I e II | Prova Final | - | - |
