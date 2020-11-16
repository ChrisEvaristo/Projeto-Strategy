# Projeto-Strategy

Classificação->  Padrão comportamental

Também chamado Policy

Intent-> Delegar responsabilidades aumentando coesão e aprimorando a comunicação entre objeto


Applicability ->Quando necessita-se de variantes de um algoritmo;
Quando se precisa ocultar do usuário a exposição das estruturas de dados complexas, específicas do algoritmo;
Quando uma classe define muitos comportamentos e por sua vez eles aparecem como diversos “IFs”. Com isso esses comandos condicionais são movidos para sua própria classe Strategy

Motivatição -> O padrão Strategy ajuda a gerenciar toda essa complexidade imposta pelas lógicas condicionais. O Padrão Strategy sugere que se produza uma família de classes para cada variação do algoritmo e que se forneça para a classe hospedeira uma instância de Strategy para a qual ela delegará em tempo de execução.



Participantes



Strategy: É uma interface comum para todas as subclasses, ou para todos os algoritmos que são suportados. O Contexto usa essa interface para chamar uma das subclasses ConcreteStrategy ou um dos algoritmos definidos.
ConcreteStrategy: Um ou mais algoritmos fornecidos para a aplicação.
Context: É aquele que vai acessar um dos algoritmos das subclasses de interface Strategy.




