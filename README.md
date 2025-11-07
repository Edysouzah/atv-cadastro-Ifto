📚 Cadastro IFTO (POO em JavaScript)

Este projeto demonstra a aplicação de Programação Orientada a Objetos (POO) em JavaScript puro para gerenciar o cadastro simulado de diferentes tipos de pessoas que frequentam o campus do IFTO.

A aplicação utiliza classes para representar herança e atributos específicos para cada categoria: Servidor, Professor, Estudante e Visitante.

⚙️ Tecnologias Utilizadas

HTML5: Estrutura base da aplicação.

JavaScript (ES6): Implementação do algoritmo de Orientação a Objetos e lógica de manipulação do DOM.

Tailwind CSS (via CDN): Framework de utilitários para estilização rápida, responsiva e moderna (tema verde, branco e vermelho).

🚀 Estrutura de Classes (POO)

O sistema é construído sobre a seguinte hierarquia de classes:

Classe Pai

Classe Filho

Atributos Exclusivos

Pessoa

-

nome, cpf, dataCadastro

Pessoa

Visitante

(Nenhum)

Pessoa

Estudante

curso

Pessoa

ServidorBase

funcao, salario

ServidorBase

Servidor

(Herdados)

ServidorBase

Professor

(Herdados)

💾 Simulação de Banco de Dados

Todas as pessoas cadastradas são armazenadas na variável global $pessoaIFTO. Atenção: Como se trata de uma simulação, os dados são armazenados apenas na memória do navegador e serão perdidos ao recarregar a página.

💻 Como Rodar

Basta abrir o arquivo cadastro_ifto.html em qualquer navegador web moderno.