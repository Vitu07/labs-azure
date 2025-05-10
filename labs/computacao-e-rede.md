# Resumo do Laboratório: Computação e Rede

Este laboratório teve como foco a exploração dos recursos de computação e rede disponíveis na Azure, com ênfase na criação e configuração de máquinas virtuais (VMs).

## Criação de Máquinas Virtuais

Inicialmente, foram apresentadas as diferentes opções de criação de VMs, incluindo:

- Modelos predefinidos com configurações básicas;
- Modelos com aplicações prontas disponíveis em "More VMs and related solutions".

Em seguida, foi demonstrado o processo de criação manual de uma máquina virtual usando a opção padrão. A VM foi adicionada ao grupo de recursos criado em um laboratório anterior. Durante a configuração, foram explorados os seguintes pontos:

- **Dimensionamento**: mostrou-se a possibilidade de escalar a VM horizontalmente, com definição de condições de escalonamento (somente demonstrado, sem aplicar).
- **Instâncias Spot**: explicação sobre seu uso em ambientes não produtivos, como testes e desenvolvimento, devido ao custo reduzido e à possibilidade de interrupção.
- **Tamanhos de Máquinas**: apresentação das diferentes séries de VMs disponíveis e seus respectivos casos de uso.
- **Backup**: opção habilitada, considerando que se trata de uma solução IaaS.
- **Monitoramento**: foram exibidas as opções e métricas disponíveis, porém não ativadas neste laboratório.
- **Configurações Avançadas**: apenas visualizadas, sem alterações aplicadas.

Ao final da configuração, foi exibida uma estimativa de custo para a criação da VM com as opções escolhidas.

## Área de Trabalho Virtual

O laboratório também abordou brevemente o recurso de Área de Trabalho da Azure, apresentando:

- Diferença entre sessões pessoais e em pool para usuários e seus respectivos usos.
- Interface de configuração no portal da Azure.

## Aplicativo de Função (Function App)

Por fim, foi apresentada a funcionalidade de criação de um aplicativo de função (Function App). Não foi aprofundado, mas foi explicado que a escolha da pilha de runtime impacta diretamente no sistema operacional utilizado, sendo ajustado automaticamente.

---

Este laboratório forneceu uma visão prática e conceitual sobre os principais recursos de computação na Azure, com foco em IaaS.
