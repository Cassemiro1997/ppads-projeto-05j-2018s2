# Casos de uso

## CDU001 - Realizar Doação
Ator Principal: Doador
Resumo: Este caso de uso permite que o doador possa cadastrar uma doação.

### Fluxo principal
1. Ator seleciona a opção de realizar doação.
2. Sistema apresenta as opções com os tipos de itens para doação: vestuário, móveis e alimentos (FA1).
3. Sistema apresenta as opções de solicitar retirada (FA2) ou não informar endereço de retirada (FA3).
4. Ator confirma a solicitação.
5. Sistema valida a doação e encerra o caso de uso.
#### Fluxo Alternativo 1
1. Ator informa a quantidade e tipo de itens para doação.
2. Sistema solicita confirmação do ator referente aos dados preenchidos.
3. Ator confirma ou edita a solicitação e retorna ao passo 3 do Fluxo Principal.
#### Fluxo Alternativo 2
1. Sistema apresenta formulário de preenchimento com o endereço do doador para efetuar a retirada.
2. Ator preenche o formulário.
3. Sistema apresenta um aviso de confirmação da solicitação e retorna ao passo 4 do Fluxo Principal.
#### Fluxo Alternativo 3
1. Sistema apresenta formulário de preenchimento com os dados de contato do doador (telefone e/ou e-mail).
2. Ator preenche o formulário.
3. Sistema apresenta um aviso de confirmação da solicitação e retorna ao passo 4 do Fluxo Principal.

## CDU002 - Cadastrar Doação
Ator Principal: Receptor
Resumo: Este caso de uso permite que o receptor possa cadastrar um local que necessita doação.

### Fluxo principal
1. Ator seleciona a opção de cadastrar doação.
2. Ator inserir os tipos de itens para doação.
3. Sistema apresenta as opções de solicitar entrega (FA1) ou retirada pelo próprio receptor (FA2).
4. Ator confirma a solicitação.
5. Sistema valida a doação e encerra o caso de uso.
#### Fluxo Alternativo 1
1. Ator informa a quantidade e tipo de itens que necessitam de doação.
2. Sistema solicita confirmação do ator referente aos dados preenchidos.
3. Ator confirma ou edita a solicitação e retorna ao passo 3 do Fluxo Principal.
#### Fluxo Alternativo 2
1. Sistema apresenta formulário de preenchimento com o endereço de entrega da doação.
2. Ator preenche o formulário.
3. Sistema apresenta um aviso de confirmação da solicitação e retorna ao passo 4 do Fluxo Principal.
#### Fluxo Alternativo 3
1. Sistema apresenta formulário de preenchimento com os dados do receptor para efetuar a retirada da doação.
2. Ator preenche o formulário.
3. Sistema apresenta um aviso de confirmação da solicitação e retorna ao passo 4 do Fluxo Principal.

## CDU003 - Encaminhar Doação
Ator Principal: Doador/Receptor
Resumo: Este caso de uso permite que o doador ou receptor possam encaminhar uma doação para um local necessitado.

### Fluxo principal
1. Ator seleciona a opção de encaminhar doação.
2. Sistema apresenta lista com os locais que necessitam uma doação.
3. Ator seleciona uma opção.
4. Sistema informa os itens necessitados.
5. Sistema apresenta as opções de solicitar entrega (FA1) ou retirada da doação (FA2).
6. Ator confirma a solicitação.
5. Sistema valida doação e retira da lista de pendentes.
#### Fluxo Alternativo 1
1. Sistema apresenta formulário de preenchimento com o endereço de entrega da doação.
2. Ator preenche o formulário.
3. Sistema apresenta um aviso de confirmação da solicitação e retorna ao passo 6 do Fluxo Principal.
#### Fluxo Alternativo 2
1. Sistema apresenta endereço de retirada da doação.
2. Sistema apresenta um aviso de confirmação da solicitação e retorna ao passo 6 do Fluxo Principal.
