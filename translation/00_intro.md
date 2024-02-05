{{meta {load_files: ["code/intro.js"]}}}

# Introdução

{{quote {author: "Ellen Ullman", title: "Perto da Máquina: Tecnofilia e seus Descontentamentos", chapter: true}

Acreditamos que estamos criando o sistema para nossos próprios propósitos. Pensamos que estamos fazendo isso à nossa própria imagem... Mas o computador não é realmente como nós. É uma projeção de uma parte muito pequena de nós mesmos: aquela parte dedicada à lógica, ordem, regra e clareza.

quote}}

{{figure {url: "img/chapter_picture_00.jpg", alt: "Ilustração de uma chave de fenda ao lado de uma placa de circuito de tamanho aproximadamente igual.", chapter: "framed"}}}

Este é um livro sobre instruir ((computadores)). Computadores são tão comuns quanto chaves de fenda hoje em dia, mas são consideravelmente mais complexos, e fazer com que façam o que você quer que façam nem sempre é fácil.

Se a tarefa que você tem para o seu computador é uma comum, bem compreendida, como mostrar seus e-mails ou agir como uma calculadora, você pode abrir o ((aplicativo)) apropriado e começar a trabalhar. Mas para tarefas únicas ou sem um fim definido, muitas vezes não existe um aplicativo.

É aí que a ((programação)) pode entrar. _Programação_ é o ato de construir um _programa_ — um conjunto de instruções precisas dizendo a um computador o que fazer. Porque os computadores são bestas burras e pedantes, a programação é fundamentalmente tediosa e frustrante.

{{index [programação, "alegria de"], velocidade}}

Felizmente, se você conseguir superar esse fato, e talvez até mesmo gostar do rigor de pensar em termos que máquinas burras podem lidar, a programação pode ser gratificante. Ela permite que você faça coisas em segundos que levariam _uma eternidade_ à mão. É uma maneira de fazer sua ferramenta de computador fazer coisas que ela não poderia fazer antes. E, além disso, torna-se um maravilhoso jogo de resolução de quebra-cabeças e pensamento abstrato.

A maioria da programação é feita com ((linguagens de programação)). Uma _linguagem de programação_ é uma linguagem artificialmente construída usada para instruir computadores. É interessante que a maneira mais eficaz que encontramos para comunicar com um computador empresta tanto da maneira como nos comunicamos uns com os outros. Como as linguagens humanas, as linguagens de computador permitem que palavras e frases sejam combinadas de novas maneiras, tornando possível expressar conceitos sempre novos.

{{index [JavaScript, "disponibilidade de"], "computação casual"}}

Em um determinado momento, interfaces baseadas em linguagem, como os prompts do BASIC e DOS dos anos 1980 e 1990, eram o principal método de interação com computadores. Para uso computacional rotineiro, estas foram em grande parte substituídas por interfaces visuais, que são mais fáceis de aprender — mas oferecem menos liberdade. No entanto, as linguagens ainda estão lá, se você souber onde procurar. Uma delas, _JavaScript_, está incorporada em todos os navegadores web modernos ((navegador)) — e, portanto, disponível em quase todos os dispositivos.

{{indexsee "navegador web", navegador}}

Este livro tentará torná-lo suficientemente familiarizado com esta linguagem para fazer coisas úteis e divertidas com ela.

## Sobre programação

{{index [programação, "dificuldade de"]}}

Além de explicar JavaScript, vou introduzir os princípios básicos da programação. Acontece que programar é difícil. As regras fundamentais são simples e claras, mas os programas construídos sobre essas regras tendem a se tornar complexos o suficiente para introduzir suas próprias regras e complexidade. Você está construindo seu próprio labirinto, de certa forma, e pode facilmente se perder nele.

{{index aprendizado}}

Haverá momentos em que ler este livro parecerá terrivelmente frustrante. Se você é novo na programação, haverá muito material novo para digerir. Muito desse material será então _combinado_ de maneiras que exigirão que você faça conexões adicionais.

Cabe a você fazer o esforço necessário. Quando estiver com dificuldades para seguir o livro, não tire conclusões precipitadas sobre suas próprias capacidades. Você está bem — você só precisa continuar insistindo. Faça uma pausa, releia algum material e certifique-se de ler e entender os programas de exemplo e os ((exercícios)). Aprender é um trabalho árduo, mas tudo o que você aprende é seu e tornará o aprendizado futuro mais fácil.

{{quote {author: "Ursula K. Le Guin", title: "A Mão Esquerda da Escuridão"}

{{index "Le Guin, Ursula K."}}

Quando a ação se torna pouco lucrativa, reúna informações; quando as informações se tornam pouco lucrativas, durma.

quote}}

{{index [programa, "natureza de"], dados}}

Um programa é muitas coisas. É um pedaço de texto digitado por um programador, é a força diretora que faz o computador fazer o que faz, é dados na memória do computador, ainda assim controla as ações realizadas nesta mesma memória. Analogias que tentam comparar programas a objetos com os quais estamos familiarizados tendem a ser insuficientes. Uma que se encaixa superficialmente é a de uma máquina — muitas partes separadas tendem a estar envolvidas, e para fazer todo o conjunto funcionar, temos que considerar as maneiras como essas partes se interconectam e contribuem para a operação do todo.

Um ((computador)) é uma máquina física que atua como um hospedeiro para essas máquinas imateriais. Os próprios computadores só podem fazer coisas estupidamente diretas. A razão pela qual são tão úteis é que fazem essas coisas com uma ((velocidade)) incrivelmente alta. Um programa pode combinar de maneira engenhosa um número enorme dessas ações simples para fazer coisas muito complicadas.

{{index [programação, "alegria de"]}}

Um programa é uma construção do pensamento. Não custa nada para construir, é sem peso, e cresce facilmente sob nossas mãos digitadoras. Mas à medida que um programa cresce, sua ((complexidade)) também cresce. A habilidade de programar é a habilidade de construir programas que não te confundam. Os melhores programas são aqueles que conseguem fazer algo interessante enquanto ainda são fáceis de entender.

{{index "estilo de programação", "melhores práticas"}}

Alguns programadores acreditam que essa complexidade é melhor gerenciada usando apenas um pequeno conjunto de técnicas bem compreendidas em seus programas. Eles compuseram regras estritas ("melhores práticas") prescrevendo a forma que os programas devem ter e cuidadosamente permanecem dentro de sua pequena zona segura.

{{index experimento}}

Isso não é apenas chato, é ineficaz. Novos problemas muitas vezes requerem novas soluções. O campo da programação é jovem e ainda está se desenvolvendo rapidamente, e é variado o suficiente para ter espaço para abordagens radicalmente diferentes. Há muitos erros terríveis a serem feitos no design de programas, e você deve ir em frente e cometê-los pelo menos uma vez para que você os entenda. Um senso do que um bom programa parece é desenvolvido com a prática, não aprendido a partir de uma lista de regras.
