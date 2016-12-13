# Linguagens
<p><b>Scala</b> é uma <a href="http://blog.jenkster.com/2015/12/what-is-functional-programming.html">linguagem funcional</a> escalar orientada à objetos que roda sobre a Java Virtual Machine (JVM). Conceitualmente cada valor é um objeto e cada operação é uma chamada de método. É possível utilizar <a href="https://www.toptal.com/scala/why-should-i-learn-scala">Scala e Java</a> no mesmo projeto.</p>

<p><b>Clojure</b> é uma linguagem funcional de programação dinâmica. Apesar de ser compilada, possuindo um rico conjunto de estruturas de dados imutáveis e persistentes, cada feature suportada por <a href="http://clojure.org/">Clojure</a> é suportada em tempo de execução, possuindo ainda uma infraestrutura robusta para programação multithread.</p>

<p><b>Swift</b> é uma linguagem de programação compilada para iOS, macOS, watchOS, tvOS, e Linux. Ela foi desenvolvida para trabalhar com os frameworks <a href="https://en.wikipedia.org/wiki/Cocoa_(API)">Cocoa</a> e <a href="https://en.wikipedia.org/wiki/Cocoa_Touch">Cocoa Touch</a>. É uma linguagem <a href="http://www.infoworld.com/article/2920333/mobile-development/swift-vs-objective-c-10-reasons-the-future-favors-swift.html">alternativa</a> ao <a href="http://blog.teamtreehouse.com/the-beginners-guide-to-objective-c-language-and-variables">Objective-C</a>.</p>

<p><b>Go</b> é uma linguagem semelhante ao C, que foi desenvolvida com o intuito de ser uma linguagem com programação simples,  compilação eficiente e execução rápida. <a href="http://imasters.com.br/linguagens/programacao-com-linguagem-google-go/?trace=1519021197">Go</a> não possui muitas construções, ao contrário das linguagens como Perl, Ruby ou Scala, que usam uma variedade de construções sintáticas ou métodos para um único e mesmo propósito.</p>

<p><b>TypeScript</b> é um projeto open-source que adiciona novas features como <a href="https://www.typescriptlang.org/docs/handbook/interfaces.html">Interfaces</a> e <a href="https://www.typescriptlang.org/docs/handbook/generics.html">Generics</a> ao <a href="https://www.typescriptlang.org/">JavaScript</a>, além de permitir a tipagem dos campos, sendo esta uma das principais vantagens da utilização do <a href="http://stackoverflow.com/questions/12694530/what-is-typescript-and-why-would-i-use-it-in-place-of-javascript">TypeScript<a/>. A maioria dos melhores frameworks JavaScript como <a href="https://angular.io/">Angular 2</a>, <a href="http://aurelia.io/">Aurelia</a>, <a href="http://dojotoolkit.org/">Dojo</a>, <a href="http://emberjs.com/">Ember</a>, <a href="http://ionicframework.com/">Ionic</a>, <a href="https://www.nativescript.org/">NativeScript</a> são escritos em TypeScript.</p>

<p><b>Babel</b> é uma plataforma que permite o desenvolvimento utilizando as novas especificações ECMAScript 6 (ES6) e ECMAScript 5 (ES5) para geração de código que roda no browser ou servidor. O que o <a href="http://codemix.com/blog/why-babel-matters">Babel</a> basicamente faz é converter um código JavaScript escrito na nova especificação para uma outra especificação JavaScript. <a href="http://www.thinkingincrowd.me/2015/12/26/TypeScript-vs-Babel/">Tanto o TypeScript, quanto o <a href="http://coffeescript.org/">CoffeScript</a>, são projetos similares</a> ao Babel.</p>

# Frameworks JavaScript
<p><b>ExpressJS</b> é um framework usado para desenvolver o back-end de uma aplicação em conjunto com o <b>NodeJS</b>, uma vez que o Node não tem intenção de construir sites web. Assim o <a href="https://www.upwork.com/hiring/development/express-js-a-server-side-javascript-framework/">Express</a> fornece as funções necessárias para construir uma aplicação web.<p>

<p><b>MeteorJS</b> é uma <a href="http://joshowens.me/what-is-meteor-js/">plataforma de desenvolvimento</a> com uma coleção de bibliotecas e pacotes que são agrupados de maneira que facilitam o desenvolvimento web.</p>

<p><b>AngularJS</b> é um framework MVC desenvolvido em JavaScript. O angular roda totalmente no lado do cliente, permitindo o binding dos dados entre os controllers e as views, além da injeção de dependências, reduzindo o código a ser desenvolvido. Existem muitas <a href="https://www.sitepoint.com/10-reasons-use-angularjs/">razões para se utilizar o Angular</a>. Muita coisa mudou com a reformulação e criação do <a href="https://angular.io/docs/js/latest/quickstart.html">Angular2</a>, que tem como base desenvolver aplicações utilizando componentes. É possível desenvolver com o Angular2 utilizando tanto o Babel, quanto o <a href="http://stackoverflow.com/questions/12694530/what-is-typescript-and-why-would-i-use-it-in-place-of-javascript">TypeScript<a/>.</p>

<p><b>NodeJS</b> é uma plataforma open-source e server-side, construída sobre a <a href="http://thibaultlaurens.github.io/javascript/2013/04/29/how-the-v8-engine-works/">Engine V8 do Google Chrome</a> e que roda em uma única thread (Single-Thread). O <a href="https://www.tutorialspoint.com/nodejs/nodejs_introduction.htm">NodeJS</a> utiliza um <a href="https://www.quora.com/What-do-event-driven-non-blocking-I-O-and-event-loop-mean">modelo dirigido a eventos e não bloqueante de entrada e saída</a> que permite a construção de aplicações escaláveis em dispositivos distribuídos. Todas as bibliotecas do NodeJS são assíncronas, isto é, não bloqueantes.</p>

<p><b>EmbderJS</b> é ...</p>

<p><b>ReactJS</b> é ...</p>

<p><b>MochaJS</b> e <b>Chai.js</b> são bibliotecas usadas para melhorar o processo de desenvolvimento das aplicações com base em <a href="http://www.agiledata.org/essays/tdd.html">Test-driven Development (TDD)</a> e <a href="https://dannorth.net/introducing-bdd/">Behavior-driven Development (BDD)</a>, fornecendo a infraestrutura para organizar e executar os testes unitários de forma automática.</p>

<p><b>GruntJS</b> e <b>GulpJS</b> são usados para automatizar tarefas. Por exemplo, é possível compilar CSS/Sass, otimizar imagens, criar e minificar ou transplantar um pacote. A principal diferença entre GulpJS e GruntJS está relacionada ao fato de que o GruntJS é baseado na configuração separada de tarefas independentes, onde cada tarefa abre, resolve e fecha o arquivo, enquanto o GulpJS é baseado em streams do NodeJS, o que permite reabrir o mesmo arquivo.</p>

<p><b>Webpack</b> é um empacotador de módulos. Ele fornece funcionalidades avançadas como recarregamento de pacotes sem atualização, carregamento sob demanda, divisão de pacotes, entre outos. O <a href="https://webpack.github.io/docs/what-is-webpack.html">Webpack</a> resolve boa parte das deficiências do Gulp e Grunt, porém pode ser complementado com os mesmos para melhorar as tarefas.</p>

<p><b>RequireJS</b> é utilizada para carregar os módulos de uma aplicação utilizando <a href="https://github.com/amdjs/amdjs-api/wiki/AMD">Asynchronous Module Definition (AMD)</a>. </p>

<p><b>Apache Spark</b> é ...</p>

<p><b>MapReduce</b> é ...</p>

<p><b>Hadoop</b> é ...</p>

<p><b>Amazon WebService</b> é ...</p>

<p><b>Karma</b> é essencialmente uma ferramenta que gera um servidor web que executa o código-fonte contra o código de teste para cada um dos navegadores conectados. Os resultados de cada teste em cada navegador são examinados e exibidos através da linha de comando para o desenvolvedor de tal forma que eles podem ver quais navegadores e testes passaram ou falharam. O Karma pode ser integrado ao Jenkins, Travis ou Semaphore, para automatização de tarefas, e seus testes podem ser descritos utilizando tanto o Jasmine, quanto Mocha ou QUnit.</p>

<p><b>Jasmine</b> é framework de desenvolvimento dirigido a comportamento para teste de código JavaScript. Uma das principais características do <a href="https://jasmine.github.io/2.4/introduction.html">Jasmine</a> está relacionada a independência com relação a outros frameworks JavaScript. Ele fornece uma sintaxe clara e objetiva para criação dos testes e é bem como ser utilizado em conjunto com o Karma.</p>

<p><b>npm</b> e <b>bower</b> são gerenciadores de pacotes. Eles fazem apenas o download das dependências e chamam o Webpack / Gulp / Grunt. Uma das principais diferenças do npm e bower é que o npm busca as dependências recursivamente, enquanto que o bower necessita da configuração manual para inclusão das sub-dependências.</p>

# Banco de Dados
<p><b>Apache Cassandra</b> é um <a href="https://academy.datastax.com/resources/brief-introduction-apache-cassandra">banco de dados não relacional</a> open-source que fornece disponibilidade contínua, desempenho escalar linear, simplicidade operacional e fácil distribuição operacional sobre diversos centros de dados.</p>

<p><b>MongoDB</b> é um banco de dados não-relacional que armazena as informações em formato <a href="https://www.mongodb.com/json-and-bson">BSON (Binary JSON)</a>. BSON é a linguagtem <a href="http://www.json.org/">JSON</a> nativa (JavaScript Object Notation), usada para obter informações armazenadas em BSON no back-end. MongoDB possui um excelente desempenho para operações de escrita e é recomendado quando se precisa de um esquema flexível (estrutura de dados). Apesar dos aspectos positivos citados, o <a href="https://www.percona.com/blog/2016/11/14/mongodb-and-mysql-mongodb-through-mysql-lens/">MongoDB não é recomendado quando os dados são altamente relacionais ou estruturados</a>. Além disso, o MongoDB não suporta transações, porém existe atomicidade em nível de documento.</p>
