# **Calculadora de IMC com Feedback Positivo**

## **Descrição Geral do Projeto**  
Este projeto consiste no desenvolvimento de um aplicativo Android, utilizando Java, para o cálculo do Índice de Massa Corporal (IMC) do usuário. Além de fornecer o valor do IMC, o aplicativo apresenta um feedback positivo e personalizado para cada faixa de classificação, incentivando hábitos saudáveis.  

Para garantir uma experiência fluida e intuitiva, a aplicação adota uma estrutura baseada em múltiplas **Activities**, gerenciando de forma eficiente a entrada de dados, o cálculo e a exibição dos resultados. Além disso, foram aplicadas boas práticas de desenvolvimento, incluindo o uso adequado de cores, manipulação de imagens e interação entre telas por meio de **Intents** e **Bundles**.

## **Informações do Aluno**  
- **Nome:** Guilherme de Lima Siqueira  
- **RA:** 21010649  
- **Curso:** Ciências da Computação (Noturno)  
- **Disciplina:** Programação de Dispositivos Móveis  
- **Professor:** Vinicius Heltai  

## **Processo de Desenvolvimento**  

### **Desafios Enfrentados**  
Durante o desenvolvimento do projeto, diversos desafios foram superados, incluindo:  

- **Gerenciamento de múltiplas Activities:** Foi essencial compreender e implementar a navegação entre telas utilizando **Intents** e **Bundles** para garantir a correta transmissão de dados.  
- **Manipulação de layouts:** A construção da interface gráfica exigiu atenção especial ao uso de **XML**, assegurando uma experiência visual agradável e responsiva.  
- **Validação da entrada de dados:** Para evitar erros durante o cálculo do IMC, foram implementadas verificações que garantem a inserção de valores numéricos válidos nos campos de **peso** e **altura**.  
- **Interação eficiente entre telas:** Um dos principais desafios foi garantir que os dados fossem transmitidos corretamente entre as **Activities**, prevenindo erros como **NullPointerException** ou **ActivityNotFoundException**. Para isso, foi necessário aprofundar-se na documentação oficial do Android e em materiais de apoio, como vídeos tutoriais.  
- **Redirecionamento dinâmico com base no IMC:** A lógica de redirecionamento para diferentes telas, conforme a classificação do IMC, exigiu:  
  - A criação de uma estrutura condicional para avaliar a faixa de IMC do usuário.  
  - A configuração de **Intents** dinâmicos, garantindo a abertura da tela correspondente.  
  - O envio de informações como IMC, peso e altura utilizando **putExtra()**.  
  - A implementação de mecanismos de validação para evitar falhas inesperadas.  

### **Decisões Tomadas**  
Para garantir o bom funcionamento do aplicativo e proporcionar uma experiência positiva ao usuário, algumas decisões foram fundamentais:  

- **Uso de uma paleta de cores harmoniosa:** A identidade visual do aplicativo foi cuidadosamente definida para oferecer um design agradável e consistente.  
- **Estruturação organizada do código:** As **Activities** foram separadas em classes distintas, facilitando a manutenção e evolução do projeto.  
- **Feedback positivo e motivacional:** Cada categoria de IMC conta com mensagens personalizadas, incentivando hábitos saudáveis e promovendo o bem-estar do usuário.  
- **Tratamento de erros:** Foram implementadas verificações para impedir falhas durante a navegação entre telas, garantindo que os cálculos fossem realizados apenas com dados válidos.  
