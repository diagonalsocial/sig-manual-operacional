# Configurações iniciais

!!! Info "Informação"
    Nesse passo a passo de configuração, apenas as instruções de implantação do fluxo de trabalho serão passadas, para saber detalhadamente de cada menu, acesse os links abaixo de cada passo.

## Perfis de acesso

    A primeira etapa para configurar o sistema é definir os acessos dos usuários.  
    Os perfis de acesso são utilizados para liberação de telas e as ações dentro  
    delas, como por exemplo, criar, visualizar, excluir e atualizar.


Clique no menu `Segurança`, acesse `Perfis de acesso` e siga os passos: 

1. Clique em "Adicionar":

2. Defina um nome para o perfil de acesso.

3. Selecione as permissões que este perfil terá em cada tela.


=== "Passo 1" 

    <figure markdown="span">
     ![Image title](images/profile.png){ width="900" }
    </figure>

=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/profile2.png){ width="900" }
    </figure>

=== "Passo 3"

    <figure markdown="span">
     ![Image title](images/profile3.png){ width="900" }
    </figure>


* Clique em "Salvar" ou "Salvar e voltar" no rodapé da página.

!!! Success "Sucesso"
    Pronto! Você criou um perfil de acesso.


<div class="grid" markdown>
Para mais informações, acesse:
[:octicons-arrow-right-24: Perfis de acesso](access_levels.md) 
{ .card }   
</div>

---

## Níveis organizacionais

    Com os perfis de acesso definidos, agora criaremos os níveis organizacionais.
    Os níveis irão garantir quais os dados que cada usuário irá enxergar dentro  
    de cada tela.

Clique no menu `Segurança`, acesse `Níveis organizacionais` e siga os passos:

1. Clique em "Adicionar".

2. Defina um nome para o nível que está criando. (Campo descrição é opcional).

3. No campo "Nível superior", selecione se o nível que está criando pertence a alguma hierarquia.


=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/orglvl.png){ width="900" }
    </figure>


=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/orglvl1.png){ width="900" }
    </figure>


=== "Passo 3"

    <figure markdown="span">
     ![Image title](images/orglvl2.png){ width="900" }
    </figure>


* Clique em "Salvar" ou "Salvar e voltar".
!!! Success "Sucesso"
    Pronto! Você criou um nível organizacional.


<div class="grid" markdown>
Para mais informações, acesse:
[:octicons-arrow-right-24: Níveis organizacionais](organizational_levels.md) 
{ .card }   
</div>

---



## Usuários 


   Agora que já possuímos os perfis e níveis de acesso definidos na plataforma,  
   podemos cadastrar os primeiros usuários. 

Clique no menu `Segurança`, acesse `Usuários` e seguia os passos:

1. Clique em "Adicionar".

2. Você pode criar um usuário vinculado a um CPF e clicar em `continuar`, ou clicar no botão `Criar sem CPF`.

3. Preencha os campos de nome do usuário, e o email de login dele. (Número de telefone opcional)

4. Selecione seu perfil de acesso e nível organizacional.


=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/user.png){ width="900" }
    </figure>


=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/user1.png){ width="900" }
    </figure>


=== "Passo 3"

    <figure markdown="span">
     ![Image title](images/user3.png){ width="900" }
    </figure>


=== "Passo 4"

    <figure markdown="span">
     ![Image title](images/user4.png){ width="900" }
    </figure>

* Você pode clicar no switch `gerar senha automaticamente` para desabilitar a opção e  
manualmente inserir uma senha para o usuário. 

* Clique em "Salvar" ou "Salvar e voltar" no rodapé da página.

!!! Success "Sucesso"
    Pronto! Você criou um usuário.


<div class="grid" markdown>
Para mais informações, acesse:
[:octicons-arrow-right-24: Usuários](users.md) 
{ .card }   
</div>

---

## Tipos de trabalho

    Para que seja possível o registro de tarefas dos usuários na plataforma,  
    é preciso configurar os tipos de trabalho e seus campos específicos para  
    preenchimento, para isso vamos separar este processo em duas etapas:
    Tipos de trabalho e Campos personalizados.

### Configurando tipos de trabalho

Clique no menu `Configurações`, acesse `Tipo de trabalho` e siga os passos:

1. Clique em "Adicionar".

2. Insira o nome do tipo de trabalho. (Campo descrição opcional).

3. Configure os **campos nativos** do tipo de trabalho:
    Você pode escolher se eles serão exibidos, se são obrigatórios e até renomeá-los!
4. Adicione os **campos personalizados**. 

=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/type1.png){ width="900" }
    </figure>


=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/type.png){ width="900" }
    </figure>
    

=== "Passo 3"

    <figure markdown="span">
     ![Image title](images/type2.png){ width="900" }
    </figure>


=== "Passo 4"

    <figure markdown="span">
     ![Image title](images/type3.png){ width="900" }
    </figure>


* Clique em "Salvar" ou "Salvar e voltar".
!!! Success "Sucesso"
    Pronto! Você criou um Tipo de trabalho.

* Veja as informações sobre `parâmetros de negócio`, `produtos` ou `padrões` abaixo:

<div class="grid" markdown>
Para mais informações, acesse:
[:octicons-arrow-right-24: Tipos de trabalho](work_item_types.md) 
{ .card }   
</div>

---

### Configurando campos personalizados

Clique no menu `Configurações`, acesse `Campos personalizados` e siga os passos:

1. Clique em "Adicionar".

2. Defina um nome interno para o campo personalizado.
    O campo "Label" será o título do campo visível nas tarefas.

3. Selecione o tipo do campo.


=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/custom.png){ width="900" }
    </figure>


=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/custom1.png){ width="900" }
    </figure>


=== "Passo 3"

    <figure markdown="span">
     ![Image title](images/custom2.png){ width="900" }
    </figure>

* Dependendo do tipo de campo selecionado, a plataforma abrirá a configuração daquele campo:

<figure markdown="span">
 ![Image title](images/custom3.png){ width="900" }
</figure>

* Repare que no exemplo, ao selecionar o tipo "número" o sistema me possibilita especificar o número de casas decimais.


* Clique em "Salvar" ou "Salvar e voltar".
!!! Success "Sucesso"
    Pronto! Você criou um Campo personalizado.



<div class="grid" markdown>
Para mais informações, acesse:
[:octicons-arrow-right-24: Campos personalizados](custom_fields.md) 
{ .card }   
</div>

---

## Configurações do contrato

    Esta etapa é a de configuração de medição do contrato, criação do banco  
    de produtos, funções e definição dos parâmetros para medição.

### Criando produtos do contrato

Clique no menu `Configurações`, acessse `Produtos do contrato` e siga os passos:

1. Clique em "Adicionar".

2. Defina um nome para o Produto.(O campo descrição é opcional).

=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/product.png){ width="900" }
    </figure>


=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/product1.png){ width="900" }
    </figure>
    

* Clique em "Salvar" ou "Salvar e voltar".
!!! Success "Sucesso"
    Pronto! Você criou um produto.


<div class="grid" markdown>
Para mais informações, acesse:
[:octicons-arrow-right-24: Produtos](contract_products.md) 
{ .card }   
</div>

---

### Criando funções de trabalho

Clique no menu `Configurações`, acesse `Funções de trabalho` e siga os passos:

1. Clique em "Adicionar".

2. Defina um nome para a função de trabalho.(O campo descrição é opcional).

=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/function.png){ width="900" }
    </figure>

=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/function1.png){ width="900" }
    </figure>


* Clique em "Salvar" ou "Salvar e voltar".
!!! Success "Sucesso"
    Pronto! Você criou uma função de trabalho.


<div class="grid" markdown>
Para mais informações, acesse:
[:octicons-arrow-right-24: Funções de trabalho](job_functions.md) 
{ .card }   
</div>

---

### Criando as definições do contrato

Clique no menu `Configurações`, acesse `Definições do contrato` e siga os passos:

1. Clique em "Adicionar".

2. Insira o nome do contrato, defina o status entre Previsto, Ativo ou Encerrado e preencha as datas de início e término do contrato.

3. Selecione o tipo de medição do contrato.


=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/definitions.png){ width="900" }
    </figure>


=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/definitions1.png){ width="900" }
    </figure>

=== "Passo 3"
 
    <figure markdown="span">
     ![Image title](images/definitions2.png){ width="900" }
    </figure>


* Agora, um passo imporante:
     Após selecionar o tipo de medição entre por Produtos, funções ou ambos, a plataforma irá pedir algumas configurações:


<figure markdown="span">
 ![Image title](images/definitions3.png){ width="900" }
</figure>

Para configurar a medição por **produtos**, siga os passos:

1. Clique em "Adicionar produto".

2. Selecione um produto previamente cadastrado em [produtos do contrato](contract_products.md).

3. Selecione a unidade de medição.

4. Indique a quantidade minima e máxima do produto e seu valor unitário.


=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/definitions4.png){ width="900" }
    </figure>

=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/definitions5.png){ width="900" }
    </figure>

=== "Passo 3"

    <figure markdown="span">
     ![Image title](images/definitions6.png){ width="900" }
    </figure>

=== "Passo 4"

    <figure markdown="span">
     ![Image title](images/definitions7.png){ width="900" }
    </figure>


 * Clique em "Salvar e fechar"
 * Repita os passos para todos os produtos que pertecem ao contrato.

Para configurar a medição por **Horas técnicas**, siga os passos:

1. Clique em "Adicionar  funções"

2. Selecione uma função de trabalho previamente cadastrada em [funções de trabalho](job_functions.md)

3. Indique a quantidade mínima e máxima de horas no contrato e seu valor/hora. 

=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/definitions8.png){ width="900" }
    </figure>

=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/definitions9.png){ width="900" }
    </figure>

=== "Passo 3"

    <figure markdown="span">
     ![Image title](images/definitions10.png){ width="900" }
    </figure>


* Clique em "Salvar e fechar"
* Repita os passos até cadastrar todas as funções do contrato.

---

* Clique em "Salvar" ou "Salvar e voltar" no rodapé da página
!!! Success "Sucesso"
    Pronto! Você criou uma Definição de contrato.

<div class="grid" markdown>
Para mais informações, acesse:
[:octicons-arrow-right-24: Definições do contrato](contract_definitions.md) 
{ .card }   
</div>

---

## Territórios

  No menu Territórios, iremos definir os locais de trabalho em que as tarefas  
  serão registradas pelos usuários no menu Trabalho, divididos entre  
  Áreas territoriais e Empreendimentos.

### Áreas territoriais

* No menu `Territórios`, acesse `Áreas territoriais` e siga os passos:

=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/add.png){ width="300" }
    </figure>
    
    * Clique em "Adicionar"

=== "Passo 2"
    
    <figure markdown="span">
     ![Image title](images/enterprise.png){ width="900" }
    </figure>
    
    * Insira o nome da Área territorial

=== "Passo 3"

    <figure markdown="span">
     ![Image title](images/enterprise2.png){ width="900" }
    </figure>
    
    * Selecione o Tipo de área entre Área ou [Regional]("conjunto de áreas").
    * Selecione a abrangência entre Estado, município ou regiões.

=== "Passo 4"

    <figure markdown="span">
     ![Image title](images/enterprise3.png){ width="900" }
    </figure>
   
    * Selecione um nível organizacional.

    <figure markdown="span">
     ![Image title](images/save.png){ width="300" }
    </figure>

    * Clique em "Salvar" ou "Salvar e voltar".
    !!! Success "Sucesso"
        Pronto! Você criou uma Área territorial.



<div class="grid" markdown>
Para mais informações, acesse:
[:octicons-arrow-right-24: Áreas territoriais](regions.md) 
{ .card }   
</div>

---

### Empreendimentos

* No menu `Territórios`, acesse `Empreendimentos` e siga os passos:

=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/add.png){ width="300" }
    </figure>
    
    * Clique em "Adicionar"

=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/region1.png){ width="900" }
    </figure>

    * Insira o nome do Empreendimento. 
    * Neste menu, apenas o nome é obrigatório.

=== "Passo 3"

    <figure markdown="span">
     ![Image title](images/region2.png){ width="900" }
    </figure>

    * Preencha os demais campos de acordo com as informações  
    do empreendimento que está cadastrando e insira seu **nível organizacional**.

    <figure markdown="span">
     ![Image title](images/save.png){ width="300" }
    </figure>

    * Clique em "Salvar" ou "Salvar e voltar".
    !!! Success "Sucesso"
        Pronto! Você criou um Empreendimento.


<div class="grid" markdown>
Para mais informações, acesse:
[:octicons-arrow-right-24: Empreendimentos](enterprises.md) 
{ .card }   
</div>

---

## Planejamento macro

    Chegou o momento de criar o planejamento de trabalho, onde vamos inserir todo  
    o escopo de itens que compõem o fluxo de trabalho.

### Criando Projetos

* Clique no menu `Planejamento`, acesse `Projetos` e siga o passo a passo:

=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/add.png){ width="300" }
    </figure>
    
    * Clique em "Adicionar"

=== "Passo 2"
    
    Você será direcionado para a aba de `informações` do projeto.

    <figure markdown="span">
     ![Image title](images/plans.png){ width="900" }
    </figure>

    * Preencha os campos de Nome, contrato, data início e data término do projeto.

=== "Passo 3" 

    <figure markdown="span">
     ![Image title](images/plans2.png){ width="900" }
    </figure>

    * Clique na opção "modelo" para habiltiar o plano como um modelo.
    * Selecione o nível organizacional.
    * Clique em "Salvar".

Agora, com as informações do `Projeto` salvas, você será redirecionado para  
aba `Planejador`, onde iremos criar os Itens do plano. Sendo que os itens de  
nível "Tarefa" serão os que aparecerão no menu trabalho para preenchimento  
dos usuários.
 Siga os passos:

=== "Passo 1"

    Na aba `planejador`:

    <figure markdown="span">
     ![Image title](images/plans3.png){ width="900" }
    </figure>
    
    * Clique em "Adicionar"

=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/plans4.png){ width="900" }
    </figure>

    * Insira o nome do item.
    * Selecione seu **nível** entre Etapa, Macroprocesso, Processo, Ativdade e Tarefa.
    * Clique em "Salvar e fechar"

=== "Passo 3"

    O item deve ficar desta forma:

    <figure markdown="span">
     ![Image title](images/plans5.png){ width="900" }
    </figure>

    * Neste exemplo, um item nível **Tarefa** foi criado.
    
    * Se um item nível **Atividade** for criado, esta tarefa agora
    pode ser vinculada aquela atividade. Como no exemplo:

    <figure markdown="span">
     ![Image title](images/plans6.png){ width="900" }
    </figure>

=== "Passo 4"

    Monte o planejamento da forma que se encaixe melhor no seu fluxo de trabalho.

    <figure markdown="span">
     ![Image title](images/save.png){ width="300" }
    </figure>

    * Clique em "Salvar" ou "Salvar e voltar".
    !!! Success "Sucesso"
        Pronto! Você criou um Projeto.

!!! Warning "Atenção"
    Se o contrato tem como base de medição "Entrega de produtos", deve-se  
    adicionar um produto quando o nível do item for "Atividade"  
    Os itens de nível "Tarefa" são obrigatórios selecionar um "Tipo de trabalho".







### Criando Ordem de serviço



### Criando a Distribuição



