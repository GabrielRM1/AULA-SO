# 📘 Estrutura e Arquitetura de Sistemas Operacionais

## 👨‍🎓 Trabalho Acadêmico
Aluno: Gabriel R. Massoni  
Curso: ADS – Sistemas Operacionais

---

# 📌 Introdução

A estrutura de um sistema operacional define como seus componentes internos são organizados para controlar os recursos do computador.

O sistema operacional atua como intermediário entre:
- Hardware;
- Aplicações;
- Usuário.

Sua arquitetura influencia diretamente:
- Desempenho;
- Segurança;
- Estabilidade;
- Eficiência computacional.

---

# 🧩 Componentes do Sistema Operacional

Os sistemas operacionais modernos são compostos por diversos módulos responsáveis pelo gerenciamento dos recursos computacionais.

## Principais componentes

### Kernel
Núcleo principal responsável pelo controle do sistema.

### Gerenciamento de Processos
Executa e controla programas em funcionamento.

### Gerenciamento de Memória
Responsável pela alocação e proteção da memória RAM.

### Sistema de Arquivos
Organiza dados em discos e dispositivos de armazenamento.

### Entrada e Saída (E/S)
Gerencia comunicação com dispositivos externos.

### Drivers
Permitem comunicação entre hardware e sistema operacional.

---

# 🧠 Kernel: O Núcleo do Sistema

O kernel é a parte central do sistema operacional.

Ele possui acesso direto ao hardware e gerencia recursos críticos do computador.

## Principais responsabilidades

- Gerenciamento de processos e threads;
- Controle de memória física e virtual;
- Comunicação entre hardware e software;
- Controle de dispositivos;
- Segurança e proteção do sistema.

---

# ⚙️ Modos de Execução

Os sistemas operacionais utilizam dois modos principais de execução.

## 👤 Modo Usuário

Executa aplicações comuns com acesso limitado ao sistema.

### Características

- Segurança;
- Restrição de acesso ao hardware;
- Menor risco ao sistema operacional.

---

## 🔒 Modo Kernel

Executa funções críticas do sistema operacional.

### Características

- Acesso total ao hardware;
- Controle de recursos do sistema;
- Execução privilegiada.

---

# 🔄 Processos

Um processo é um programa em execução.

Cada processo possui:
- Espaço de memória próprio;
- Estado de execução;
- Recursos associados.

## Estados de um processo

- Novo;
- Pronto;
- Executando;
- Esperando;
- Finalizado.

---

# 💾 Memória e Espaço de Endereçamento

O gerenciamento de memória é fundamental para evitar conflitos entre programas.

## Funções principais

- Alocação de memória;
- Liberação de memória;
- Proteção entre processos;
- Memória virtual;
- Paginação.

---

# 📁 Sistema de Arquivos

O sistema de arquivos organiza informações em dispositivos de armazenamento.

## Funções

- Criar arquivos;
- Ler dados;
- Gravar informações;
- Organizar diretórios;
- Controlar permissões.

## Exemplos

- NTFS
- FAT32
- ext4
- APFS

---

# 🔌 Entrada/Saída e Drivers

Os dispositivos de entrada e saída precisam de gerenciamento específico.

## Exemplos de dispositivos

- Teclado;
- Mouse;
- Impressora;
- SSD/HDD;
- Placa de vídeo.

Os drivers funcionam como tradutores entre hardware e sistema operacional.

---

# 🖥️ Relação entre Hardware e Software

O sistema operacional conecta aplicações ao hardware do computador.

## Estrutura básica

Aplicações → Sistema Operacional → Hardware

Sem o sistema operacional, os programas não conseguiriam utilizar corretamente os recursos físicos da máquina.

---

# 📌 Importância da Arquitetura de Sistemas Operacionais

Uma boa arquitetura proporciona:

- Melhor desempenho;
- Segurança;
- Estabilidade;
- Escalabilidade;
- Facilidade de manutenção.

Os sistemas modernos dependem diretamente dessa organização interna para operar de maneira eficiente.

---

# 📌 Conclusão

A estrutura e arquitetura dos sistemas operacionais são fundamentais para o funcionamento da computação moderna.

O kernel, gerenciamento de memória, processos, drivers e sistemas de arquivos trabalham em conjunto para garantir estabilidade, desempenho e segurança aos usuários e aplicações.

---

# 📚 Referências

- TANENBAUM, Andrew S. Sistemas Operacionais Modernos.
- STALLINGS, William. Operating Systems.
- Material acadêmico da disciplina de Sistemas Operacionais.
- Documentação técnica sobre arquitetura de sistemas.
