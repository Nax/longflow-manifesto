<div align="center">
    <h1>O Manifesto <em>Longflow</em/></h1>
    <em>Versão 1</em>
</div>

## Sobre esse manifesto

O modelo longflow é um fluxo de trabalho centrado na engenharia para desenvolvedores sérios, cansados da besteira de "Agile"/"Scrum".

## A questão do Tempo

### Tempo e Trabalho

Na indústria de software, tal como em qualquer indústria, o dono de um negócio não vende tempo. O dono de um negócio vende um produto.
Contudo, um desenvolvedor de software cobra por tempo trabalhado.

Em algum lugar, tempo deve ser transformado em melhorias ao produto.
A ação de aplicar essa transformação é chamada de trabalho.

Contudo, a relação entre tempo gasto e trabalho realizado é absolutamente *não* linear.
Otimização prematura, por exemplo, é um bom candidato para uma relação logarítimica, na qual mais e mais tempo é investido em cada vez menos benefícios.
Em contrapartida, boa refatoração pode utilizar uma quantia moderada de tempo para um retorno exponencial sobre um longo período de tempo.

Esse é o princípio chave da metodologia longflow: **tudo deve ser feito com objetivos de longo-termo em mente**.

Isso *não* significa prototipação.
Isso *não* significa otimização prematura.
Isso *significa* que qualidade tem um preço: tempo.

### Estimativas

Estimativas devem ser evitadas à todo custo.
Elas criam pressão desnecessária, competição e a participação tóxica na caça-às-bruxas por quem é menos produtivo.

No mundo do desenvolvimento de software, é impossível produzir estimativas significativas, sem falar de precisas, para qualquer coisa que não seja uma nano-tarefa.

É frequentemente impossível dividir uma tarefa em tarefas significativas menores, ainda mais *antes* de iniciar a tarefa original.
Tal como pode ser impossível dividir uma função em funções significativas menores, onde essas funções são coerentes e auto-contidas.

Faça o fluxo de trabalho se ajustar ao projeto, não o inverso.
Isso traça um belo paralelo com o projeto oriendado à dados<sup>[1]</sup>, no qual dados são o núcleo e a lógica deve seguí-lo.

### Eventos Baseados em Tempo

Interações frequentes, baseadas em tempo, entre executivos e engenheiros são um dos melhores jeitos de destruir uma empresa.
Ter uma reunião uma vez por semana/mês ou qualquer outro indicador baseado apenas em tempo é insignificante. Transmite a idéia de que todas as tarefas são iguais, e todo progresso deve ser obtido em um ritmo constante.
Também é um jeito excelente de manter o foco em resultados imediatos ao invés de objetivos à longo-prazo.

Interações entre executivos e engenheiros devem ser limitadas em termos de quantidade e frequência.
Também é melhor ser o menos intrusivo possível: um email pode ser melhor que uma reunião em muitos casos.

Micro-gerenciamento deve ser evitado à todo custo, porque cria interferências entre executivos e engenheiros, e reduz criatividade.

*Maratonas, sprints, etc são tóxicos e perigosos.*

Qualidade é infinitamente superior à quantidade. Engenheiros de software almejam produzir código legível, bonito e que funciona.
Ao forçar datas de entrega à eles, eles são encorajados à produzir o código "menos pior" ao invés do código "melhor possível".
A metodologia longflow advoca ter tarefas significativas médias ou grandes, auto-definidas sempre que possível, na qual desenvolvedores podem utilizar tanto suas habilidades técnicas quanto resolução de problemas.
Faça desenvolvedores não escrever código primeiro, mas simplesmente pensar em como eles podem resolver o problema. Ou até melhor, faça-os perguntar internamente:

 * Há um problema a ser resolvido?
 * Posso melhorar essa parte do código?
 * Existem tarefas que eu gostaria de ter resolvido de outra forma?

Curiosidade e criatividade são habilidades muito importantes para desenvolvedores de software, mas essas habilidades não podem ser desenvolvidas se há pressão para produzir código o mais rápido possível
É prejudicial ter metas longas, sem nem falar das permanentes.

Desenvolvedores deveriam ser permitidos, até mesmo encorajados, a gastar um tempo aprendendo e brincando com novas coisas e conceitos.
Ter a possibilidade de aplicar uma vasta variedade de soluções e conceitos à um problema é crucial para um bom desenvolvedor de software.
Negar seu direito à aprender vai afetar a habilidade dos desenvolvedores de melhorar e produzir código de qualidade.

## A metodologia longflow em simples passos

### Gerenciamento

 * Continue pensando em objetivos de longo-prazo.
 * Deixe os engenheiros determinarem suas próprias tarefas.
 * Valorize qualidade sobre datas de entrega.
 * Deixe os engenheiros fazerem a engenharia.
 * Não micro-gerencie.
 * Não interfira com engenheiros mais do que o estritamente necessário.
 * Nunca se apresse, sempre pense e planeje adiante.
 * Não tema falhar.
 * Evite cultos à carga<sup>[2]</sup> como se fossem pragas.

### Técnico

 * Continue pensando em objetivos de longo-prazo.
 * Determine suas próprias tarefas.
 * Tente corrigir bugs antes de introduzir novas funcionalidades, até um limite.
 * Tente limpar o código antes de introduzir novas funcionalidades, até um limite.
 * Tente escrever o melhor código possível.
 * Não tenha medo de tentar algo diferente.
 * Pense mais, escreva menos.
 * Sempre tente aprender, seja curioso.
 * Não tenha medo de atrasar.
 * Não tema falhar.
 * Evite cultos à carga como se fossem pragas.

## Uma implementação típica

Uma típica implementação do manifesto longflow, do ponto de vista de um engenheiro, é algo parecido com isso:

 1. Eu escolho ou crio uma tarefa.
 2. Eu perco alguns minutos/horas/dias pensando sobre a tarefa. Nós precisamos disso? Eu já fiz algo similar no passado? Que objetivo essa tarefa atinge?
 3. Se a tarefa não for necessária, eu volto pra 1.
 4. Se eu preciso aprender algo para realizar a tarefa, eu aprendo.
 5. Se eu *quero* aprender algo novo, eu aprendo.
 6. Eu penso sobre a tarefa novamente. Eu posso voltar para o 4 ou 1 se as coisas que aprendi mudaram minha opinião sobre a tarefa.
 7. Eu trabalho na tarefa. Eu posso voltar para o item 2 a qualquer momento.
 8. Eu termino a tarefa.
 9. Eu penso sobre a tarefa novamente. Eu posso querer voltar para o 2.
 10. A tarefa agora pode ser considerada terminada, mas eu (ou outra pessoa) posso decidir trabalhar nela a qualquer momento, voltando para o 2.

Pode parecer confuso à princípio, mas um fluxo de trabalho como esse é tanto possível quanto extremamente bom em termos de qualidade do código produzido, porque qualquer um pode melhorar qualquer parte da base de código sempre que quiser.

## Autor

Esse manifesto foi escrito por [Nax](https://github.com/Nax) e traduzido para Português por [alganet](https://github.com/alganet).
Sinta-se livre para modificá-lo.

[1]: https://en.wikipedia.org/wiki/Data-oriented_design
[2]: https://pt.wikipedia.org/wiki/Culto_%C3%A0_carga
