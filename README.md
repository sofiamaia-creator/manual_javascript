# MANUAL JAVA SCRIPT

# INTRODUÇÃO:

## O que é JavaScript: 
JavaScript é uma linguagem de programação interpretada de alto nível, essencial para criar sites dinâmicos e interativos. JavaScript é uma versão mais atualizada da linguagem Java, tornando a linguagem JavaScript mais fácil de usar.


## Para que ele serve:
O JavaScript é uma linguagem de programação essencial para a web, usada para tornar páginas estáticas em experiências interativas e dinâmicas. Ele roda diretamente no navegador do usuário permitindo criar animações, validar formulários, etc. Ele também serve para manipular o conteúdo, estilo e comunicação com servidores, gerenciar bancos de dados e lógica de aplicação, tornando o JavaScript uma linguagem full-stack.


## Relação com HTML e CSS:
JavaScript se relaciona com HTML e CSS agindo como o "comportamento" da página, permitindo manipular dinamicamente a estrutura (HTML) e o estilo (CSS) após o carregamento. Ele utiliza o Document Object Model (DOM) para criar interatividade, como atualizar conteúdos, alterar cores ou validar formulários em resposta a eventos do usuário
HTML = Estrutura
CSS = Aparência
JavaScript = Comportamento

## Onde pode ser usado no HTML:
JavaScript pode ser usado no HTML de três formas principais: externa (arquivo .js linkado), interna (tag <script> no head/body) ou inline (atributos de evento diretamente nas tags).

## Diferença entre script dentro do HTML e script em arquivo separado;
A principal diferença é a organização e a performance: scripts dentro do HTML (<script>) são ideais para códigos minúsculos e específicos de uma página, carregando junto com o HTML, enquanto scripts em arquivo separado (.js) são recomendados para a maioria dos casos, promovendo a reutilização de código, facilidade de manutenção e cache do navegador.

##  EXEMPLOS ESTÃO NO ARQUIVO 03: Como declarar variáveis;
Em JavaScript, declara-se variáveis principalmente com let (para valores reatribuíveis) e const (para valores constantes). O uso de var é obsoleto e desencoraja-se por questões de escopo. Variáveis podem armazenar números, strings, objetos, etc., e o JavaScript infere o tipo automaticamente.

## Como declarar variáveis;
Em JavaScript, declara-se variáveis principalmente com let (para valores reatribuíveis) e const (para valores constantes). O uso de var é obsoleto e desencoraja-se por questões de escopo. Variáveis podem armazenar números, strings, objetos, etc., e o JavaScript infere o tipo automaticamente. 

## Diferença entre var, let e const;
A principal diferença entre var, let e const no JavaScript é o escopo (onde a variável existe) e a reatribuição (se o valor pode mudar). var tem escopo de função, let e const têm escopo de bloco. let permite reatribuição, enquanto const cria uma constante fixa. var permite redeclaração, ao contrário de let e const. 

## O que é escopo de variável;
O escopo de uma variável é o contexto ou região do código onde ela é definida e pode ser acessada ou modificada. Ele determina a visibilidade da variável: escopo local (dentro de uma função/bloco) ou global (em todo o programa). Compreender o escopo é fundamental para evitar bugs, gerenciar memória e organizar código. 

## Diferença entre == e ===;
A principal diferença é que == (igualdade) compara apenas os valores, realizando conversão de tipo (coerção) se necessário. Já o === (igualdade estrita) compara tanto o valor quanto o tipo de dado (string, número, etc.), retornando true apenas se ambos forem idênticos, sendo mais seguro e recomendado.
se encontra no arquivo 

## Diferença entre != e !==;
A principal diferença é que != compara apenas o valor (com coerção de tipo), enquanto !== (desigualdade estrita) compara o valor e o tipo. O != retorna falso se os dados forem diferentes, mas conversíveis para o mesmo valor, enquanto !== retorna verdadeiro se forem tipos ou valores diferentes.
se encontra no arquivo 

## Como declarar funções;
Declarar funções envolve definir um nome, parâmetros (opcionais) e um bloco de código, usando palavras-chave específicas da linguagem (como function em JS ou def em Python). A estrutura básica inclui o nome da função seguido de parênteses () e chaves {} ou indentação para o corpo. 

## Como fazer operações aritméticas e lógicas básicas;
são realizadas usando operadores padrão e seguem regras de precedência (PEMDAS: Parênteses, Expoentes, Multiplicação/Divisão, Adição/Subtração), onde parênteses têm a maior prioridade e a ordem é da esquerda para a direita.

## Como usar estruturas condicionais;
Estruturas condicionais (if, else, elif/else if) direcionam o fluxo do código com base em condições verdadeiras ou falsas. Elas funcionam avaliando expressões lógicas (como ou) e executando blocos de código específicos somente se a condição for atendida, permitindo tomadas de decisão inteligentes.
se encotra no arquivo 05.

## Como usar estruturas de repetição;
Estruturas de repetição (loops) automatizam tarefas repetitivas, executando um bloco de código várias vezes enquanto uma condição for verdadeira. Os principais tipos são for (número definido de repetições), while (enquanto a condição for verdadeira) e do-while (executa ao menos uma vez antes de verificar a condição).

## Como JavaScript pode interagir com elementos da página.
JavaScript interage com elementos da página (HTML) manipulando o DOM (Document Object Model). Isso é feito selecionando elementos (por ID, classe, tag), alterando conteúdos (innerHTML, innerText), modificando estilos CSS, adicionando/removendo classes (classList) e respondendo a eventos do usuário (cliques, teclado, carregamento da página).








