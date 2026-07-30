MRX - Calculadora de Peso — Carga
Uma ferramenta web interativa para calcular, monitorar e otimizar o peso de cargas logísticas industriais. O sistema permite adicionar materiais (bobinas) e caixas, além de calcular a melhor distribuição possível dos itens dentro das embalagens para atingir uma meta específica de peso de frete.

Funcionalidades
Definição de Meta de Peso: Estabeleça um peso total alvo e acompanhe o progresso em tempo real através de uma barra indicadora.

Cálculo Preciso de Materiais: Adicione bobinas especificando o tipo (808C, 808M, 800XC, 913TT), largura e comprimento. O sistema calcula automaticamente os metros quadrados e o peso estimado com base no tipo de material e peso do núcleo.

Inclusão em Lote: Cole uma lista de larguras separadas por vírgula para adicionar múltiplas bobinas de uma só vez.

Gerenciamento de Caixas: Adicione caixas de diferentes tamanhos (P, M, G) com pesos vazios predefinidos para compor o cálculo final da carga.

Cálculo de Fechamento Inteligente: Utiliza um algoritmo de otimização para selecionar a melhor combinação de bobinas que atinja a meta de peso dentro de uma margem de frete (± 15 kg), distribuindo-as automaticamente no volume das caixas cadastradas sem exceder o limite de altura.

Exportação para Excel: Gere e faça o download de uma planilha .xlsx com o detalhamento completo através de abas (Materiais, Caixas, Alocação, Bobinas Restantes e Resumo).

Modo Noturno/Claro: Suporte nativo para alternância entre temas, salvando automaticamente a preferência do usuário no navegador.

 Como Usar
Defina a Meta: Insira o peso alvo no campo "Peso total a atingir" no topo da página.

Adicione os Materiais: Preencha as dimensões das bobinas e clique em "Adicionar à carga". Alternativamente, utilize a seção de "Colar larguras" para adições em massa.

Adicione as Caixas: Indique a quantidade e o tamanho das caixas que farão parte deste frete.

Calcule o Fechamento: Clique em "Calcular fechamento" para gerar a distribuição das bobinas nas caixas e verificar se a carga está dentro da margem estipulada.

Exporte os Dados: Clique em "Exportar Excel" para salvar os resultados consolidados no seu computador.

🛠️ Tecnologias Utilizadas
HTML5 e CSS3: Estrutura e estilização, utilizando CSS Custom Properties (variáveis) para o sistema de cores dinâmicas (Dark Mode).

JavaScript Vanilla: Lógica principal de cálculo, algoritmos de alocação (subset-sum/programação dinâmica) e manipulação da interface.

SheetJS (xlsx): Biblioteca externa importada via CDN para a geração e exportação nativa de planilhas Excel.

⚙️ Instalação e Execução
Este projeto foi construído inteiramente em um único arquivo, eliminando a necessidade de processos de build complexos ou instalações de pacotes:

Baixe ou clone este repositório.

Salve o código principal em um arquivo .html (ex: index.html).

Dê um duplo clique para abrir o arquivo diretamente em qualquer navegador web moderno.

Nota: A funcionalidade de "Exportar Excel" requer uma conexão ativa com a internet na primeira execução para carregar a biblioteca SheetJS através da CDN.
