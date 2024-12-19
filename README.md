# Desafio Dev PHP Pleno

Quando programamos, nós tentamos seguir uma gama de melhores práticas e padrões de projeto.

Já que escrever **um bom código é inegociável** no nosso dia a dia, nós esperamos que as pessoas que queiram entrar no nosso time pensem da mesma maneira. Este teste foi criado para encontrar esses programadores.

## Método de Avaliação

Vamos avaliar seu teste baseado em uma série de [atributos de qualidade](https://en.wikipedia.org/wiki/List_of_system_quality_attributes).

Esses são os atributos de qualidade que esperamos que você atenda:
- **Corretude:** O seu código deve seguir os requerimentos apresentados no [item abaixo](#o-que-queremos-que-você-faça);
- **Testabilidade:** Quão fácil é entender e testar o seu código;
- **Manutenibilidade:** Quão fácil é adicionar novas funcionalidades no seu código;
- **Coesão e integridade das informações:** Exclusões de registro de forma que não ocorra corrompimento das informações;
- **Separação de conceitos:** (https://en.wikipedia.org/wiki/Separation_of_concerns);
- **Resolução:** Forma com que você resolve os problemas;

## Como Entregar

- Coloque seu código em um **repositório privado no Github** e adicione o @paulopwm como um de seus colaboradores.
  Essa conta no Github (@paulopwm) será utilizada para baixar o seu código e revisá-lo.
- **Após finalizar o desafio, por favor submeta as informações por meio deste formulário:**
  https://forms.gle/uhLL4qMRHQtoeQUTA

## O que queremos que você faça

1. Uma aplicação simples que a partir de um form efetue:

   **A. Aplicação**
   - [ ] Inserção de informações em uma tabela;
   - [ ] Liste todos os itens cadastrados nessa tabela; 
   - [ ] A partir da listagem, efetue a exclusão de um registro;

   **B. Banco de dados com as informações abaixo:**
   - O banco deve conter no mínimo as seguintes tabelas:
     - Tabela **Funcionário**
       - Nome
       - Documento
     - Tabela **Cartão**
       - Número
       - Saldo
     - Tabela **Operadora**
       - CNPJ
       - Nome

   **Regras de negócio:**
   - [ ] Cada cartão somente pode estar vinculado a uma operadora;
   - [ ] Os funcionários podem ter 1 ou mais cartões;
   - [ ] Crie um formulário de busca, que a partir de um documento ou número de cartão mostre as informações cadastradas;

2. Um script que acesse o Google e:
   - [ ] Efetue uma busca (por qualquer termo);
   - [ ] Efetue uma busca por **VT Soluções**;
   - [ ] A partir da busca acima, retorne um array com:
     - Telefone
     - Endereço

3. Um script que acesse o site da VT Soluções (https://www.vtsolucoes.com.br) e obtenha a última notícia do blog e:
   - [ ] Retorne um array com:
     - Título
     - Resumo
     - URL da imagem

### Observações
- Utilize PHP para a realização do teste;
- Você pode utilizar ou não framework, fica a seu critério. Vamos avaliar a sua lógica; 
- Se utilizar framework, pode ser o que você estiver mais acostumado(a);
- Pode utilizar qualquer banco de dados relacional (MySQL, MariaDB, PostgreSQL, etc...);
- Qualquer dúvida, não deixe de entrar em contato conosco.
