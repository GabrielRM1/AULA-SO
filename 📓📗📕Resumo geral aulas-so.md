# 📘 Resumo Geral das Aulas de Sistemas Operacionais

## 👨‍🎓 Trabalho Acadêmico

**Disciplina:** Sistemas Operacionais  
**Curso:** Análise e Desenvolvimento de Sistemas  

---

# 📌 Introdução

Este documento apresenta um resumo geral dos principais conteúdos estudados nas aulas de Sistemas Operacionais. Os temas abordam desde a evolução dos computadores até conceitos modernos como virtualização, computação em nuvem, APIs, GitHub e infraestrutura de sistemas.

O objetivo é reunir os principais pontos das aulas em um único material de consulta, organizado de forma simples e clara para publicação no GitHub.

---

# 🖥️ Evolução dos Computadores

A evolução dos computadores ocorreu em diferentes gerações, acompanhando o avanço da tecnologia.

## Primeira Geração

Os computadores utilizavam válvulas eletrônicas, eram grandes, consumiam muita energia e tinham baixa capacidade de processamento.

## Segunda Geração

Com o surgimento dos transistores, os computadores ficaram menores, mais rápidos e mais confiáveis.

## Terceira Geração

O uso de circuitos integrados permitiu maior desempenho e o surgimento da multiprogramação.

## Quarta Geração

A chegada dos microprocessadores popularizou os computadores pessoais e permitiu o desenvolvimento dos sistemas modernos.

---

# ⚙️ Conceito de Sistema Operacional

Um sistema operacional é o software responsável por gerenciar os recursos do computador e permitir a comunicação entre usuário, aplicações e hardware.

## Principais funções

- Gerenciar processos;
- Controlar memória;
- Administrar arquivos;
- Controlar dispositivos;
- Garantir segurança;
- Permitir execução de programas.

Sem o sistema operacional, o usuário teria que controlar diretamente o hardware, tornando o uso do computador muito mais complexo.

---

# 🧠 Estrutura e Arquitetura dos Sistemas Operacionais

A arquitetura de um sistema operacional define como seus componentes internos são organizados.

## Componentes principais

- Kernel;
- Gerenciador de processos;
- Gerenciador de memória;
- Sistema de arquivos;
- Drivers de dispositivos;
- Interface com o usuário.

O sistema operacional atua como uma camada entre o hardware e os programas, garantindo organização, segurança e desempenho.

---

# 🔒 Kernel e Modos de Operação

O kernel é o núcleo do sistema operacional. Ele possui acesso direto ao hardware e controla os recursos principais da máquina.

## Modo usuário

É o modo utilizado por programas comuns, como navegadores, editores de texto e jogos. Possui acesso limitado ao sistema para garantir segurança.

## Modo kernel

É o modo utilizado pelo sistema operacional para executar tarefas críticas, como controle de memória, processos e dispositivos.

---

# 🔄 Processos e Threads

Um processo é um programa em execução. Ele possui recursos próprios, como memória, registradores, arquivos abertos e estado de execução.

## Estados de um processo

- Novo;
- Pronto;
- Executando;
- Bloqueado;
- Finalizado.

As threads são unidades menores de execução dentro de um processo. Elas permitem maior desempenho e paralelismo, pois compartilham recursos do mesmo processo.

---

# ⏱️ Escalonamento de Processos

O escalonamento define qual processo utilizará a CPU em determinado momento.

## Objetivos do escalonamento

- Melhorar o uso da CPU;
- Reduzir tempo de espera;
- Garantir justiça entre processos;
- Melhorar o tempo de resposta.

## Algoritmos estudados

- FCFS;
- Round Robin;
- Prioridade.

---

# 💾 Gerenciamento de Memória

O gerenciamento de memória é responsável por controlar o uso da memória RAM pelos programas.

## Funções principais

- Alocar memória;
- Liberar memória;
- Proteger áreas de memória;
- Evitar conflitos entre processos;
- Controlar memória virtual.

A memória virtual permite que programas maiores que a RAM sejam executados utilizando parte do armazenamento como apoio.

---

# 📁 Sistemas de Arquivos

O sistema de arquivos organiza os dados armazenados no computador.

## Funções

- Criar arquivos;
- Ler arquivos;
- Gravar informações;
- Excluir arquivos;
- Organizar diretórios;
- Controlar permissões.

## Exemplos de sistemas de arquivos

- NTFS;
- FAT32;
- ext4;
- APFS.

---

# 🔌 Gerenciamento de Dispositivos

O sistema operacional controla dispositivos de entrada e saída, como teclado, mouse, monitor, impressora, disco e rede.

Os drivers funcionam como intermediários entre o sistema operacional e o hardware, permitindo que os dispositivos funcionem corretamente.

---

# 🖥️ Tipos de Sistemas Operacionais

Existem diferentes tipos de sistemas operacionais, cada um voltado para uma necessidade específica.

## Principais tipos

- Sistemas para computadores pessoais;
- Sistemas para servidores;
- Sistemas embarcados;
- Sistemas móveis;
- Sistemas de tempo real;
- Sistemas de mainframes.

Cada tipo possui características próprias de desempenho, segurança, disponibilidade e finalidade.

---

# 🏢 Sistemas Operacionais de Servidor

Os sistemas de servidor são utilizados para fornecer serviços em rede.

## Exemplos de serviços

- Hospedagem de sites;
- Banco de dados;
- Compartilhamento de arquivos;
- Controle de usuários;
- Aplicações corporativas.

## Exemplos de sistemas

- Linux Server;
- Windows Server;
- UNIX.

---

# ☁️ Computação em Nuvem e Sistemas Operacionais

A computação em nuvem permite acessar recursos computacionais pela internet.

## Recursos oferecidos

- Servidores;
- Armazenamento;
- Bancos de dados;
- Redes;
- Aplicações;
- Máquinas virtuais.

Os sistemas operacionais são fundamentais na nuvem, pois gerenciam os recursos físicos e virtuais utilizados pelos serviços.

---

# 🌐 Modelos de Serviço em Nuvem

## IaaS

Infraestrutura como serviço. Fornece máquinas virtuais, redes e armazenamento.

## PaaS

Plataforma como serviço. Oferece ambiente pronto para desenvolvimento e publicação de aplicações.

## SaaS

Software como serviço. Permite utilizar aplicações diretamente pela internet.

---

# 🧱 Virtualização

A virtualização permite executar vários sistemas operacionais em um único computador físico.

Ela cria ambientes isolados chamados máquinas virtuais.

## Vantagens

- Economia de hardware;
- Ambientes isolados;
- Facilidade para testes;
- Execução de múltiplos sistemas;
- Melhor aproveitamento dos recursos.

---

# 🖥️ Máquina Virtual

Uma máquina virtual é um computador simulado dentro de outro computador.

## Elementos principais

- Host: sistema principal;
- Hipervisor: software de virtualização;
- Guest: sistema operacional instalado na máquina virtual.

Ferramentas como Oracle VirtualBox permitem criar e configurar máquinas virtuais para testes e estudos.

---

# 🐳 Containers

Containers são ambientes leves e isolados utilizados para executar aplicações.

## Vantagens

- Inicialização rápida;
- Menor consumo de recursos;
- Portabilidade;
- Facilidade de deploy;
- Padronização de ambientes.

## Ferramentas comuns

- Docker;
- Docker Compose;
- Kubernetes.

---

# 🚀 API REST com Express

Uma API REST permite a comunicação entre sistemas utilizando requisições HTTP.

## Métodos HTTP

- GET;
- POST;
- PUT;
- DELETE.

Com Node.js e Express.js é possível criar APIs de forma simples para integrar aplicações web, mobile e serviços em nuvem.

---

# 🌍 Deploy no Render

O Render é uma plataforma de hospedagem em nuvem utilizada para publicar aplicações, APIs e serviços web.

## Benefícios

- Deploy simples;
- Integração com GitHub;
- Certificado SSL;
- Atualizações automáticas;
- Hospedagem online.

---

# 🧑‍💻 Git e GitHub

O Git é um sistema de controle de versão utilizado para registrar alterações em projetos.

O GitHub é uma plataforma online que permite armazenar, organizar e compartilhar repositórios.

## Benefícios

- Controle de versões;
- Organização dos trabalhos;
- Histórico de alterações;
- Colaboração em equipe;
- Portfólio profissional.

---

# 📌 Boas Práticas no GitHub

Para manter um repositório organizado, é importante:

- Criar arquivos com nomes claros;
- Utilizar README.md;
- Escrever mensagens de commit objetivas;
- Organizar trabalhos por temas;
- Usar Markdown para documentação.

## Exemplos de mensagens de commit

- Adiciona trabalho sobre virtualização;
- Atualiza resumo de sistemas operacionais;
- Adiciona material sobre computação em nuvem;
- Corrige documentação do projeto.

---

# 📚 Conclusão

As aulas de Sistemas Operacionais apresentaram conceitos fundamentais para compreender como os computadores funcionam internamente e como os recursos são gerenciados.

Foram estudados temas como evolução dos computadores, estrutura dos sistemas operacionais, kernel, processos, memória, arquivos, virtualização, nuvem, APIs e GitHub.

Esses conhecimentos são importantes para a formação em Análise e Desenvolvimento de Sistemas, pois ajudam a compreender a base da computação moderna e a organização de ambientes tecnológicos utilizados no mercado.

---

# 📖 Referências

- TANENBAUM, Andrew S. Sistemas Operacionais Modernos.
- STALLINGS, William. Sistemas Operacionais.
- SILBERSCHATZ, Abraham; GALVIN, Peter B.; GAGNE, Greg. Fundamentos de Sistemas Operacionais.
- Documentação oficial do GitHub.
- Documentação oficial do Node.js.
- Documentação oficial do Express.js.
- Documentação oficial do Render.
- Material acadêmico da disciplina de Sistemas Operacionais.
