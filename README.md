# CKP7500 - Sistemas Distribuídos e Redes de Comunicação

(Também SMD0050 - Sistemas Distribuídos)

## Ciência da Computação, [Departamento de Computação](http://www.dc.ufc.br), Instituto UFC Virtual ([UFC](http://www.ufc.br))

### Professores

* **Professor** - Fernando Trinta ([fernando.trinta@dc.ufc.br](mailto:fernando.trinta@dc.ufc.br))
* **Professor** - Windson Viana ([windson@virtual.ufc.br](mailto:windson@virtual.ufc.br))

### Local

Aulas remotas assíncronas eventualmente as terças-feiras e quintas-feiras (16:00-18:00) pelo Google Meet.

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
 1 avaliação individual adaptativa (AIA);
 6 atividades práticas (AT1-AT6);
 1 Seminário final (SEM);

A média final é uma média ponderada das notas
**NF = [(0.2*AIA + 0.2*SEM + 0.1*(AT1 + ... + AT6)]**


### Plano de aulas

| Aulas      | Parte | Tópicos                      | Recursos 2023 | Material Legado de 2021 |
|:-------------:|:----:|-----------------------------|:---------:|:-----------:|
|14 Mar 2023| I | Apresentação da Disciplina. Ementa. Bibliografia. Avaliação. Metodologia. | [Slides Apresentação](https://docs.google.com/presentation/d/1TDpoG2tagK5W-MLwkZHbCwsTcrlQZ6p-AKuRVS6Tf40/edit?usp=sharing) | [Slides Apresentação](https://docs.google.com/presentation/d/1SGAkG5VkT3mJu5b4g4_Gu9Q1DWQ5CG5f09jsGOlWlyY/edit?usp=sharing), [Vídeo - Aula](https://drive.google.com/file/d/16d2LOJDifBN9O-PK-dPF_VGZqVuMbtvc/view?usp=sharing) |
|16 Mar 2023| I | Fundamentos de SD (Conceito, Características, Vantagens, Desvantagens) | [Slides Fundamentos SD](https://docs.google.com/presentation/d/1GOIAw0MgvHV-y9S9eOa2viWKUoskH45IFg9GDsWil9w/edit?usp=sharing) | [Slides Fundamentos SD](https://docs.google.com/presentation/d/1nM5xKqJM-P4yHbZvgCg9PTtJuCdSStTGYPH8gwiHpqo/edit?usp=sharing), [Vídeo - Aula](https://drive.google.com/file/d/1LOSWsIcbBUeR1UGSw5BdDnKdK_x2jiXi/view?usp=sharing) |
|21 Mar 2023| II | Fundamentos de SD (Conceito, Características, Vantagens, Desvantagens) | - | [Slides Fundamentos SD](https://docs.google.com/presentation/d/1nM5xKqJM-P4yHbZvgCg9PTtJuCdSStTGYPH8gwiHpqo/edit?usp=sharing), [Vídeo - Aula](https://drive.google.com/file/d/1hL3yivKN03DbdkL3SfYJvEcUEsEj2rO7/view?usp=sharing)|
|23 Mar 2023| I | Atividade Prática de Revisão de Redes - Wireshark (AT1)| - | [Roteiro de Estudo](https://docs.google.com/document/d/1x1pQkacABFVx5cVMz03ssR1QDWyWH_fcdYBq8fhGCAQ/edit?usp=sharing), [Atividade](https://docs.google.com/document/d/17o74YyhMWitWC0CQpGtu3vQpvzOqoKqpISZHP1x6i38/edit?usp=sharing) |
|28 Mar 2023| I | Modelos e Estilos Arquitetônicos de um SD | [Slides](https://docs.google.com/presentation/d/11b_woecjabbineXLuXrQncKQhJ6j0PzDTvaEvtypJq0/edit?usp=sharing) | [Slides](https://docs.google.com/presentation/d/11b_woecjabbineXLuXrQncKQhJ6j0PzDTvaEvtypJq0/edit?usp=sharing), [Texto Interessante](https://towardsdatascience.com/10-common-software-architectural-patterns-in-a-nutshell-a0b47a1e9013), [Video-Aula_Parte 1](https://www.youtube.com/watch?v=ohXmcFZchCs), [Video-Aula_Parte 2](https://www.youtube.com/watch?v=XhvTjuArDDE)|
|30 Mar 2023| II | Modelos e Estilos Arquitetônicos de um SD (Tira dúvidas da AT1) | - | - |
|04 Abr 2023| I | Estudo sobre o seu SD (AT2) | [Descrição da Tarefa] (https://docs.google.com/document/d/1iMh4fFaARjP8-OXhAk3RRXPNBL9FJ-EJrvqSSChuBOg/edit?usp=sharing) | [Descrição da Tarefa](https://docs.google.com/document/d/1Pf4gBAxFtl5k8wBhz4xz-EO68avxgSP0ViqGDA5tUIs/edit?usp=sharing), [Escolha o Tema](https://docs.google.com/document/d/1plJ8TkYylTDTQxpm78byH8V7f4yMQboad1HBPAxzNE0/edit?usp=sharing) |
|06 Abr 2023| - | FERIADO | - | - |
|11 Abr 2023| I | Apresentação (Vídeo ou Slides) - Arquitetura (AT2) | - | - |
|13 Abr 2023| I | Paradigmas de Comunicação - Overview | [Slides](https://docs.google.com/presentation/d/1y06Gi49f24wjCNmi43foCX-pc5hDF2eGo9k2I7kFbRA/edit?usp=sharing) | [Slides PDF](https://docs.google.com/presentation/d/1y06Gi49f24wjCNmi43foCX-pc5hDF2eGo9k2I7kFbRA/edit?usp=sharing), [Roteiro da aula](https://docs.google.com/document/d/1b5w44_XbeXNJPcGILghJYf_SAcr3Ro5tzF90cGlNX6M/edit?ts=60c89350) |
|18 Abr 2023| II | Paradigmas de Comunicação -  Parte 1 & 2 | [Parte 1](https://docs.google.com/document/d/1FX1QfASdDkyVP8SYNhHPCvNWQq9n8el0I_gsgXOY6yM/edit?usp=sharing), [Parte 2](https://docs.google.com/document/d/1k5KIAQhLcIENmeCoqtuk7No87jRb3WatCIR9FV_zeAE/edit?usp=sharing) | [Roteiro da aula](https://docs.google.com/document/d/16TgBxDgTp8KeCTG9htv65HIxo3x5oP07jyj2bh0REq0/edit?usp=sharing) |
|20 Abr 2023| I | Algoritmos Distribuídos - Relógios Lógicos e Exclusão Mútua. | [Roteiro de Estudo](https://docs.google.com/document/d/1z582doTfWXif-FZ66fF1D0nLADWX0LO6AU0uQ8LO_bM/edit?usp=sharing)   | [Slides](https://docs.google.com/presentation/d/1bl51LAz48ZJC31Ynm7Kj2mtkqEWtbpKiIgjkYWcixXk/edit?usp=sharing), [Roteiro da aula](https://docs.google.com/document/d/1z582doTfWXif-FZ66fF1D0nLADWX0LO6AU0uQ8LO_bM/edit?usp=sharing) |
|25 Abr 2023| II | Algoritmos Distribuídos - Relógios Lógicos e Exclusão Mútua. | - | - |
|27 Abr 2023| I | Invocação Remota e Comunicação Indireta - Overview | - | - |
|02 Mai 2023| II | Invocação Remota e Comunicação Indireta (AT03) | - | [Roteiro da aula](https://docs.google.com/document/d/16dekWzI3OyvoHPDc2DErTEjmGnLj4xOY3lMWgEd3Vvg/edit?usp=sharing) |
|04 Mai 2023| III | Invocação Remota e Comunicação Indireta (AT03) | - | [Roteiro da aula](https://docs.google.com/document/d/16dekWzI3OyvoHPDc2DErTEjmGnLj4xOY3lMWgEd3Vvg/edit?usp=sharing) |
|09 Mai 2023| I | Estudo sobre Interoperabilidade (Modelos de Representação de Dados) | - | [Slides](https://docs.google.com/presentation/d/1kOuOLCtfoxjaXI4qnkBc68En07XrmDi6Zbrymnhq-QI/edit?usp=sharing), [Roteiro Aula](https://docs.google.com/document/d/1M4q1QjFJC152jYjBggKwA79thQ-U0UIw-CXjOlDlXmQ/edit?usp=sharing) |
|11 Mai 2023| II | Interoperabilidade. Aula PBL. | - | - |
|16 Mai 2023| I | SOA e Microserviços - Overview | - | [Slides](https://github.com/famt/sd/blob/2020.1/slides/soa.pdf), [Roteiro Aula](https://docs.google.com/document/d/1Ugt9m5-nTuUd7ol5JkGLSbLCfOb5-SnmwVfYBFTUvv0/edit?usp=sharing) |
|18 Mai 2023| II | SOA e Microserviços | - | - |
|23 Mai 2023| I | Carlos Henrique - Serpro (Gov.BR) | - | - |
|25 Mai 2023| I | Algoritmos Distribuídos - Algoritmos de Eleição - Overview (AT05) | - | [Slides](https://docs.google.com/presentation/d/19m_Xf451JBIYeIH68XLZNgIbm6RopaI7tDvw6r3Jmw0/edit?usp=sharing), [Roteiro da aula](https://docs.google.com/document/d/1vEI9abYg7PILytS4M9OoanM_voHUnOkgw6yE2Ohq1nU/edit?usp=sharing) |
|30 Mai 2023| II | Algoritmos Distribuídos - Algoritmos de Eleição | - | [Slides](https://docs.google.com/presentation/d/19m_Xf451JBIYeIH68XLZNgIbm6RopaI7tDvw6r3Jmw0/edit?usp=sharing), [Roteiro da aula](https://docs.google.com/document/d/1vEI9abYg7PILytS4M9OoanM_voHUnOkgw6yE2Ohq1nU/edit?usp=sharing) |
|01 Jun 2023| I | Computação em Nuvem - Tira dúvidas da avaliação |  | [Slides](https://docs.google.com/presentation/d/1YfmZx9BHQEPICXu1crt_n2fxe1s19k72T-LXsZNGv8A/edit?usp=sharing), [Roteiro de Aula](https://docs.google.com/document/d/1pMLajeHFmaZ4P461J-iNVfW7Ozihgv3-gr3vvznvwPY/edit?usp=sharing) |
|06 Jun 2023| II | Computação em Nuvem | - | - |
|08 Jun 2023| - | FERIADO | - | - |
|13 Jun 2023| I | Avaliação | - | - |
|15 Jun 2023| I | Mensageria | - | - |
|20 Jun 2023| I | Apresentação - SDs - ATO6 (em grupo) | - | - |
|22 Jun 2023| I | Preparação para os seminários | - | - |
|27 Jun 2023| I | Seminários Individuais | - | - |
|29 Jun 2023| II | Seminários Individuais | - | - |
|04 Jul 2023| I | BACKUP | - | - |
|06 Jul 2023| I | Provas Finais | - | - |
