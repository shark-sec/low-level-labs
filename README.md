# Low-Level Research & Reverse Engineering Labs

Este repositório centraliza meus estudos, análises estáticas/dinâmicas, desenvolvimento de exploits e laboratórios práticos focados em Engenharia Reversa (EVM & Arquiteturas Tradicionais) e Segurança Ofensiva.

O objetivo principal é documentar a fundo o comportamento de softwares em baixo nível, mapeamento de fluxos de execução e pesquisa de vulnerabilidades.

## 🛠️ Tecnologias & Ferramentas Utilizadas
*   **Linguagens:** C, Assembly, Python
*   **Plataformas/Ambientes:** EVM (Ethereum Virtual Machine), Linux (Kali OS)
*   **Ferramentas de Análise:** Solvers de CFG, Mapeadores de Opcode, ferramentas de análise estática.

## 📂 Estrutura do Repositório

*   **`/EVM-Web3`**: Análise de bytecode bruto, engenharia reversa de Smart Contracts em produção e reconstrução de Grafos de Fluxo de Controle (CFG).
*   **`/Binaries-x86_64`**: Desafios de RE clássica, crackmes e análise de binários compilados.
*   **`/Exploit-Dev`**: Desenvolvimento de exploit code em C, automações de payloads e manipulação de pilha/memória.
*   **`/Reports`**: Relatórios técnicos detalhados e writeups de vulnerabilidades identificadas.

---
## 🚀 Destaques Recentes

### [Análise de Fluxo de Controle e Bytecode na EVM](./EVM-Web3/bold-project)
Mapeamento completo da lógica de roteamento interna de um contrato inteligente a partir do bytecode bruto, identificando desvios condicionais (`JUMPI`), seletores de funções (`PUSH4`, `EQ`) e tratamento de exceções (`REVERT`) no bloco `0x8d2e`.

---
*Aviso: Todas as análises e códigos disponibilizados aqui possuem fins estritamente educacionais e de pesquisa de segurança.*