# Sprint-3---Dynamic-Programming-Documentação-do-Projeto

# Nomes e RM dos Integrantes do Grupo:
Matheus Taylor, RM556211
Henrique Maldonado, RM557270

# Documentação do Projeto : 
Sistema de Gerenciamento de Insumos para Laboratório de Patologia (Com Python)

# Descrição do Projeto:
  Esse é um projeto um sistema que implementa a automatização para gerenciar o consumo de insumos em um laboratório de patologia, substituindo o método manual atual de registro de medidas e consumo. O sistema utiliza estruturas de dados e algoritmos de ordenação para otimizar o gerenciamento de insumos.

# Aplicação no Contexto do Problema: 
- Fila: Utilizada para registrar o consumo diário de insumos em ordem cronológica, garantindo que os primeiros itens consumidos sejam os primeiros a ser processados, evitando perda de dados e mantendo a sequência temporal.
- Pilha: Permite acessar os últimos consumos registrados primeiro, útil para auditorias recentes e verificação rápida dos últimos registros sem precisar percorrer toda a lista.
- Busca Sequencial: Ideal para encontrar insumos em listas pequenas ou não ordenadas, sem necessidade de pré-processamento.
- Busca Binária: Mais eficiente para listas grandes e ordenadas, reduzindo significativamente o tempo de busca em comparação com a busca sequencial.
- Merge Sort: Estável e com complexidade O(n log n) garantida, ideal para ordenar insumos por quantidade consumida ou data de validade, mantendo a integridade dos dados.
- Quick Sort: Geralmente mais rápido na prática que o Merge Sort, útil para ordenações rápidas quando a estabilidade não é um requisito crítico.

# Benefícios do Sistema:
- Redução de erros humanos: Automatização do registro elimina erros de transcrição
- Eficiência: Estruturas de dados otimizadas permitem acesso rápido às informações
- Rastreabilidade: Registro cronológico completo de todos os consumos
- Tomada de decisão: Dados organizados facilitam análise de padrões de consumo
- Controle de validade: Alertas automáticos para insumos próximos do vencimento

