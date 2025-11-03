**Projeto: ChamadaFacil**

O Sistema de Chamada por Biometria foi desenvolvido com o objetivo de modernizar e automatizar o processo de registro de presença de alunos em ambiente escolar. Utilizando tecnologia de leitura de digitais, o sistema identifica cada estudante de forma rápida, segura e precisa, eliminando a necessidade de chamadas manuais ou listas de papel.

Com a autenticação biométrica, cada aluno é reconhecido instantaneamente ao colocar o dedo no sensor, registrando automaticamente sua presença, data e hora no banco de dados. O sistema também permite o cadastro e exclusão de digitais, além de gerar relatórios de frequência e integrar-se com sistemas administrativos da escola.

**Principais Funcionalidades:**

Cadastro de alunos com identificação biométrica.

Registro automático de presença com data e hora.

Armazenamento dos dados em banco local.

Funçaõ para exportar a chamada por Execel.

**Tecnologias utilizadas:**

![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) Responsável pela estruturação da página e exibição das informações.

![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3) Utilizado para o design e estilo da interface, proporcionando uma experiência visual agradável.

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)Usado para sistemas como filtros, comunicação com o servidor e data e hora.
 
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) e ![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white) Servem como servidores do projeto.

Além disso, utilizamos o ngrok para criar um tunel online, onde passamos as informações da chamada (lista de presença) por meio de uma API.

Também é utilizado My SQLite, um banco de dados q usamos para armazenar a lista de presença e login do corpo docente.

À um Arduino uno sendo ultilizado no projeto, equipado com um sensor biometrico AS608, display LCD I2c, 3 LEDs e 3 botões para o meio fisico(Hardware). Sendo programado pelo Arduino IDE na linguagem C++.
