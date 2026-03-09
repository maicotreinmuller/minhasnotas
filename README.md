Este projeto é uma aplicação web de página única (SPA) para gerenciamento de notas e tabelas dinâmicas, projetada para ser leve, rápida e totalmente funcional sem a necessidade de um servidor (client-side).

Como foi feito
O projeto foi desenvolvido focando em portabilidade e desempenho, utilizando tecnologias web padrão:

HTML5 & CSS3: Estruturação semântica e estilização avançada utilizando Variáveis CSS (Custom Properties) para suporte nativo a temas (Light/Dark Mode) e layouts responsivos com CSS Grid e Flexbox.

JavaScript (Vanilla): Toda a lógica de manipulação do DOM, gerenciamento de estado e interatividade foi escrita em JavaScript puro, sem dependências de frameworks externos como React ou Vue.

Persistência de Dados: Utiliza a API localStorage do navegador para salvar notas, tabelas e configurações do usuário localmente, garantindo que os dados não sejam perdidos ao fechar a aba.

Ícones: Integração com a biblioteca Boxicons para uma interface visual moderna e intuitiva.

Principais Funcionalidades
1. Sistema de Notas (Cards)
Criação de notas rápidas com títulos e descrições.

Organização visual por cores.

Suporte a Drag-and-Drop para reordenar as notas livremente.

Lixeira com sistema de recuperação de notas excluídas.

2. Tabelas Dinâmicas (Estilo Spreadsheet)
Validação de Dados: Configuração de colunas por tipo (Texto, Data com calendário nativo ou Listas Suspensas coloridas).

Manipulação Avançada: Redimensionamento de colunas, ordenação (A-Z / Z-A) e filtragem em tempo real.

Interatividade: Seleção de múltiplas células, "Pincel de Formatação" e alça de preenchimento automático.

Importação/Exportação: Função para copiar tabelas no formato TSV (compatível com Excel e Google Sheets).

3. Interface e UX
Sistema de Abas: Organize diferentes contextos de trabalho em abas separadas.

Modo Escuro/Claro: Alternância de tema global e temas específicos por tabela.

Atalhos de Teclado: Suporte a comandos como Ctrl+Z (Desfazer) e Ctrl+Y (Refazer) para edições nas tabelas.

Como usar
Basta abrir o arquivo minhasnotas.html em qualquer navegador moderno.

Não é necessário instalar nada ou configurar servidores.

Para salvar seus dados permanentemente em outro dispositivo, você pode usar as funções de exportação (futuras implementações) ou simplesmente manter o arquivo e o cache do navegador.

Licença
Este projeto foi desenvolvido para uso pessoal e produtividade. Sinta-se à vontade para clonar e adaptar conforme suas necessidades.
