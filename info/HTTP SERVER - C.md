# Checklist para Construir um Servidor HTTP em C

Esta checklist cobre os conhecimentos e habilidades necessários para desenvolver um servidor HTTP em C. Marque os itens conforme você avança no aprendizado e implementação.

## Conhecimentos Básicos em C
- [x] **Sintaxe e Estruturas de Dados**
  - [x] Variáveis, tipos de dados e operadores.
  - [x] Estruturas de controle (`if`, `for`, `while`).
  - [x] Arrays, structs e ponteiros.
- [x] **Manipulação de Memória**
  - [x] Alocação dinâmica de memória (`malloc`, `free`).
  - [x] Uso correto de ponteiros.
- [ ] **Funções e Modularização**
  - [ ] Criação e uso de funções.
  - [ ] Modularização do código em múltiplos arquivos.

## Sockets e Programação de Redes
- [ ] **Sockets**
  - [ ] Criação de sockets (`socket()`).
  - [ ] Associação de sockets a endereços e portas (`bind()`).
  - [ ] Escuta por conexões (`listen()`).
  - [ ] Aceitação de conexões (`accept()`).
  - [ ] Envio e recebimento de dados (`send()`, `recv()`).
- [ ] **Protocolo TCP/IP**
  - [ ] Entendimento básico do modelo OSI.
  - [ ] Endereços IP e portas.
  - [ ] Funcionamento do TCP (conexões confiáveis).

## Protocolo HTTP
- [x] **Estrutura de Mensagens HTTP**
  - [x] Requisições HTTP (métodos como GET, POST).
  - [x] Respostas HTTP (códigos de status como 200, 404).
  - [ ] [[Cabeçalhos HTTP]] (`Content-Type`, `Content-Length`, etc.).
- [ ] **Implementação Básica**
  - [ ] Leitura e interpretação de requisições HTTP.
  - [ ] Geração de respostas HTTP simples.

## Manipulação de Arquivos e I/O
- [ ] **Operações de Arquivo**
  - [ ] Abertura, leitura e escrita de arquivos (`fopen`, `fread`, `fwrite`).
  - [ ] Fechamento de arquivos (`fclose`).
- [ ] **Buffering**
  - [ ] Uso de buffers para leitura e escrita eficiente.

## Concorrência e Multithreading
- [ ] **Threads**
  - [ ] Criação e gerenciamento de threads (`pthread_create`, `pthread_join`).
  - [ ] Sincronização com mutexes e semáforos.
- [ ] **Servidor Concorrente**
  - [ ] Implementação de um servidor que lida com múltiplos clientes simultaneamente.

## Segurança Básica
- [ ] **Validação de Entrada**
  - [ ] Prevenção de buffer overflow.
  - [ ] Validação de dados recebidos do cliente.
- [ ] **Boas Práticas**
  - [ ] Uso de funções seguras (`strncpy` em vez de `strcpy`).
  - [ ] Evitar vazamentos de memória.

## Ferramentas e Bibliotecas Úteis
- [ ] **Makefiles**
  - [ ] Criação de Makefiles para compilação automatizada.
- [ ] **Depuração**
  - [ ] Uso do GDB para depuração.
  - [ ] Uso do Valgrind para detecção de vazamentos de memória.
- [ ] **Bibliotecas**
  - [ ] Uso de bibliotecas como `libcurl` (opcional, para requisições HTTP clientes).

## Testes e Depuração
- [ ] **Testes Unitários**
  - [ ] Criação de testes unitários para funções específicas.
- [ ] **Depuração de Rede**
  - [ ] Uso de ferramentas como `netcat` ou `curl` para testar o servidor.
  - [ ] Verificação de erros de concorrência.

## Documentação e Boas Práticas
- [ ] **Documentação**
  - [ ] Documentação do código (comentários e README).
  - [ ] Documentação da API (se aplicável).
- [ ] **Boas Práticas de Codificação**
  - [ ] Código limpo e organizado.
  - [ ] Uso de convenções de nomenclatura consistentes.

## Implementação do Servidor HTTP
- [ ] **Servidor Básico**
  - [ ] Criação de um servidor HTTP que responde a requisições GET.
  - [ ] Respostas simples (ex: "Hello, World!").
- [ ] **Servidor Avançado**
  - [ ] Suporte a múltiplos métodos HTTP (GET, POST).
  - [ ] Servir arquivos estáticos (HTML, CSS, JS).
  - [ ] Tratamento de erros (404, 500).
- [ ] **Otimizações**
  - [ ] Uso de `select()` ou `poll()` para I/O multiplexado.
  - [ ] Implementação de um pool de threads para melhorar desempenho.

## Referências e Recursos
- [ ] **Livros**
  - [ ] "The C Programming Language" (Kernighan & Ritchie).
  - [ ] "Unix Network Programming" (W. Richard Stevens).
- [ ] **Guias Online**
  - [ ] [Beej's Guide to Network Programming](https://beej.us/guide/bgnet/).
  - [ ] [MDN Web Docs - HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP).
- [ ] **Ferramentas**
  - [ ] [GDB Documentation](https://www.gnu.org/software/gdb/documentation/).
  - [ ] [Valgrind Documentation](https://valgrind.org/docs/).

## Conclusão
- [ ] Revisão de todos os tópicos acima.
- [ ] Testes finais e ajustes no servidor.
- [ ] Documentação final e entrega do projeto.

---

**Nota:** Esta checklist é um guia abrangente. Dependendo do seu projeto, alguns itens podem ser opcionais ou adaptados às suas necessidades.