
# Trabalho


O menu `trabalho` é onde o usuário poderá visualizar os itens de trabalhos atribuídos e criados por ele.


## Visualização 


No canto superior direito da tela do menu trabalho, é possível localizar o um botão de seleção de visualização, 
em `lista`, `kanban` ou `calendário`:


=== "Lista"

    <figure markdown="span">
     ![Image title](images/lista.png){ width="900" }
    </figure>
     
     * Exibe os itens listados.
     * Utilize o botão `classificar` para selecionar a ordem de classificação da lista desejada.

=== "Kanban"

    <figure markdown="span">
     ![Image title](images/kanban.png){ width="900" }
    </figure>

    * Exibe os itens como "cartões" separados em colunas por status.
    * Clique e arraste os cartões para alterar seu progresso.

=== "Calendário"

    <figure markdown="span">
     ![Image title](images/calendario.png){ width="900" }
    </figure>

    * Itens exibidos em formato de calendário.
    * Filtre a exibição por itens [`realizados`]("com status concluído"), [`programados`]("com status programado") ou [`planejados`]("gerados por distribuição"). 


## Filtros

O botão `filtrar` está disponível para que o usuário filtre suas tarefas da forma mais adequada para seu uso:

<figure markdown="span">
 ![Image title](images/filter.png){ width="600" }
</figure>

Basta selecionar os valores de acordo:

[`Quando`]("valor a ser filtrado"), [`for`]("operador lógico"), e selecionar os valores existentes.

Por exemplo:

Quando "status do trabalho" for "igual" a "concluído"

Clique em `aplicar filtro`.  
Este exemplo trará todas as tarefas com status concluído.  

<figure markdown="span">
 ![Image title](images/filterapply.png){ width="900" }
</figure>

---

## Configurações de exibição

Vamos falar sobre como as tarefas são exibidas no menu `trabalho`.

Uma série de informações podem ser encontradas nas tarefas do menu trabalho, independente do modo de visualização escolhido.

### Badges

As `Badges` são os indicativos dos vínculos que aquelas tarefas possuem, seja com o `Território`,  com o `Produto`, `Tipo de trabalho` etc. 

Passe o mouse em cima das badges para que visualize do que elas se tratam:

<figure markdown="span">
 ![Image title](images/badges2.png){ width="900" }
</figure>

Esses detalhes podem ser configurados se são exibidos ou não pelo próprio usuário. 

Basta clicar no ícone abaixo:

<figure markdown="span">
 ![Image title](images/badges.png){ width="900" }
</figure>

Esta tela de configuração será exibida, e o usuário pode escolher o que exibir:

<figure markdown="span">
 ![Image title](images/badges3.png){ width="900" }
</figure>

---

### Detalhes

O botão `detalhes` está disponível caso o usuário queira visualizar detalhadamente do que se trata aquela tarefa sem abrí-la:

<figure markdown="span">
 ![Image title](images/details.png){ width="900" }
</figure>

Clicando no botão: 

<figure markdown="span">
 ![Image title](images/details2.png){ width="900" }
</figure>


## Registro de tarefas

Existem duas formas de registro de trabalho na plataforma, sendo por tarefas [planejadas]("geradas por um plano") ou [não planejadas]("geradas no menu trabalho"). 

Veja a seguir os dois casos:

### Não planejadas:

1. Acesse o menu trabalho.

2. Clique em "Adicionar".

3. Selecione o "Tipo de trabalho".

=== "Passo 1"

    <figure markdown="span">
     ![Image title](images/work.png){ width="900" }
    </figure>

=== "Passo 2"

    <figure markdown="span">
     ![Image title](images/work2.png){ width="900" }
    </figure>    

=== "Passo 3"

    <figure markdown="span">
     ![Image title](images/work3.png){ width="900" }
    </figure>   

* Agora é só preencher o `status` e a prioridade(opcional).

!!! note "Atenção"
    Após selecionar o tipo de trabalho, os campos de preenchimento da tarefa serão abertos. Verifique com a sua organização a forma correta de preenchê-los.

* Lembre-se de clicar em "Salvar" ou "Salvar e voltar" para registrar os dados da tarefa.

### Planejadas:

Caso sua organização trabalhe com tarefas planejadas, basta procurar a tarefa a ser realizada.

!!! tip "Dica"
    Utilize a barra de pesquisa da plataforma e os filtros para facilitar o processo de visualização das tarefas.

Para preencher a tarefa basta acessar o item clicando em cima, e ele sera aberto:
<figure markdown="span">
 ![Image title](images/planned.png){ width="900" }
</figure>    
Veja o exemplo: 

<figure markdown="span">
 ![Image title](images/planned2.png){ width="900" }
</figure>  

* Repare que o `tipo de trabalho` da tarefa planejada já vem preenchido. Basta preencher os campos de acordo com a orientação da sua organização.
* Não se esqueça de clicar em "Salvar" ou "Salvar e voltar" no rodapé da página para registrar os dados da tarefa.


## Recorrência

Quando uma tarefa pode se repetir diversas vezes, o usuário pode programar neste campo para que esta tarefa esteja sempre presente em sua lista de trabalho, desta forma, toda vez que ele aplicar o status `Concluído`, uma nova tarefa com os dados copiados dessa tarefa será criada no menu `Trabalho`, de acordo com a recorrência aplicada.

??? question "**Como aplicar a recorrência?**"
    
    1. Clique no switch de "aplicar recorrência".

    2. Selecione a periodicidade da recorrência, por exemplo "a cada 2 dias".

    3. Se a periodicidade for por semana, você poderá escolher o dia em que ela ocorre, selecione quando ela acaba.


    === "Passo 1"

        <figure markdown="span">
        ![Image title](images/repeat.png){ width="900" }
        </figure>

    === "Passo 2"

        <figure markdown="span">
        ![Image title](images/repeat1.png){ width="900" }
        </figure>

    === "Passo 3"

        <figure markdown="span">
        ![Image title](images/repeat2.png){ width="900" }
        </figure>

## Relatório geral de trabalho

O relatório geral de trabalho é o compilado das tarefas e suas informações filtradas no menu `Trabalho`. As informações são extraídas para um arquivo `.xlsx`, enquanto os anexos são extraídos para um `.zip`.

!!! warning "Importante:"
    O relatório é gerado a partir das informações exibidas no menu trabalho, ou seja, **se um filtro estiver aplicado, apenas as informações das tarefas filtradas serão geradas**.

Para gerar um relatório, clique na opção "Relatórios" no menu `Trabalho`: 

<figure markdown="span">
![Image title](images/general.png){ width="300" }
</figure>


Ao selecionar "Relatório geral de trabalho", você será direcionado para a guia de extração, clique na opção que deseja:

<figure markdown="span">
![Image title](images/general1.png){ width="900" }
</figure>

!!! warning "Atenção:"
    É preciso que a extração de relatórios esteja habilitada no [`Perfil de Acesso`](access_levels.md) do usuário.

---