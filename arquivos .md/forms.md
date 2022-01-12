# Formulários 

Para que serve?

- Capturar dados de entrada (input)
- Interação
- Controle

Pré Requisitos

- Básico HTML

Dominar

- Estilização
- Validação
- Controles customizados
- Javascript

# Tag Form

- Elemento que definirá um formulário
- É um container

Atributos básicos 

- Action
- Method

# TAG Fieldset

- Agrupamento de campos
- Mesmo propósito
- Mais semântico
- Acessibilidade

Atributos especiais

-disabled
    -desabilita todos os elementos internos
    -Não serão enviados ao submeter o formulário

-form
    -o id de um formulario ao que esse fieldset pertence
    -não precisa estar dentro do dormulario

-name 
    -nome do grupo 

# Tag Legend

- Nome do agrupamento 
- primeiro elemento dentro do fieldset

# Tag Label

- associar e identificar uma ou mais tags de entrada de dados
- acessibilidade 
- você poderá clicar pada mudar o foco da entrada de dados

Atributos 

-for 
    -para fazer a conexão entre este label e o input 
    - é feita via id do input
    - só funciona com elementos específicos
        - button, input {not hidden}, meter, output, progress, select e textarea

# Tag button

- Representa um botão
- Usado para enviar formulário
- É estilizado pelo UA

- Atributos

-type
    -submit
    -reset
    -button
-autofocus
-disabled
-name
-value
-form


# Tag Datalist

- Lista de valores como sugestão a uma tag <input>
- Valores sugestivos e não obrigatórios
- Usuário poderá colocar um dos valores ou um outro diferente da sugestão

<datalist id="fruitsdata">
    <option>Banana</option>
    <option>Banana</option>
    <option>Banana</option>
    <option>Banana</option>
    <option>Banana</option>
</datalist>

# list 

- Recebe como valor o id de um datalist residente no mesmo documento

# Tipos de inputs suportados

- text, search, url, tel, email, date, month, week, time, datetime-local, number, range e color.


# Tipos não suportados

- hidden, password, checkbox, radio, file ou qualquer tipo de button
