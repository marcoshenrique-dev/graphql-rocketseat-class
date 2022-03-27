# GraphQL (meu aprendizado)

### O que é GraphQL

uma ferramenta criada dentro do facebook, sendo uma linguagem de realização de query (operações de criação é leitura) através da comunicação de front e back.

Assim como o rest é uma forma de comunicar o back/front, servindo como um padrão diferente.

### Como o graphQL pode ajudar (vantagens)

- evitar Overfetching (buscar mais do que precisa)
- evitar Underfetching (buscar menos do que precisa)

<aside>
💡 Quando trabalha com graphQL quem diz quais dados serão carregados é o front, não o back! Tendo uma rota única onde o front passa os dados

</aside>

### Desvantagens do graphQL

- traz um pouco mais de complexidade (no início)
- mais difícil trabalhar com cache no browser (por ter uma única rota)
- mais difícil lidar com erros por não existir outro status além de 200 no graphql

### Code first vs Schema first

- criar o código primeiro (schema criado automático)
- criar o schema primeiro (mais demorado)

### Query vs mutation

- query → buscar dados
- mutation → criar ou alterar dados

<aside>
💡 graphql playground é um postman do graphql

</aside>

### Anotações

- no graphql quando quer retornar um array coloca colchetes por volta, e não depois