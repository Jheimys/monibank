<p align="center"> <img src="https://imgur.com/mIBmcEL.png" alt="Javascript: validando formulários"> </p>

<hr>

<p align="center"> <img src="https://github.com/MonicaHillman/aluraplay-requisicoes/blob/main/img/logo.png" alt="Logo da Alura"> </p>
<p align="center">Formulário de criação de contas para o banco virtual MoniBank.</p>

# O Projeto
O projeto Monibank foi o produto final do Curso Javascript: Validando formulários da Alura. Na tela de formulário criamos mensagens 
customizadas para cada tipo de erro que pode ocorrer, por exemplo O campo "Nome" possui duas mensagens de verificação que são ativadas 
através das situações abaixo:
 - Se clicarmos no campo e em seguida clicarmos fora dele, a mensagem "O campo de nome não pode estar vazio." é exibida;
 - Se clicarmos no campo, e digitarmos alguns caracteres antes de clicarmos fora dele, a mensagem "Por favor, preencha um nome válido." 
 será exibida.
 
 E assim segue também para os outros campos. Após o usuário preencher todos os campos do formulário de maneira correta é direcionado a uma 
 nova página para que faça o reconhecimento facial, nela a pessoa usuária será capaz de capturar uma imagem sua com a câmera.
 
<p align=center>
  <image width="570" heigth="570" src='https://github.com/Jheimys/assets/blob/master/formMOnibank.png'> 
</p>
   
 <p align=center>
  <image width="570" heigth="670" src='https://github.com/Jheimys/assets/blob/master/reconhecimentoFacial.png'>
</p>

 ### Para implementarmos o projeto ultilizamos os seguintes conhecimentos:
  
 #### 1 - Atributos do HTML5, como:
- Required que torna o campo obrigatório;
- Type que define o tipo de input;
- min-length e max-length que controlam a quantidade de caracteres do input;
- pattern que deve ser implementado no interior de regexs (expressões regulares, em português);
  
### 2- Ferramentas do Javascript, como:
 - addEventListener que detecta interações da pessoa usuária com o cadastro;
 - verificação de CPF que possuirá uma lógica para validar os seus dois últimos dígitos;
 - verificação de maioridade já que o Monibank não aceita menores de idade abrindo contas;
 - ValidityState para verificar os erros que ocorrem no preenchimento do elemento;
 - manipulação de DOM para imprimir mensagens de erro;
 - localStorage para salvar os dados. Mesmo que nosso formulário seja local, é necessário que suas informações sejam salvas em um local específico.

 
## Tecnologias utilizadas durante o curso
* JavaScript

## Tecnologias utilizadas no projeto
* HTML
* CSS
