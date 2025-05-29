---
sidebar_position: 1
---

# 🗂️ Configurando Layers

## Informações:
- Este tutorial é aplicável tanto ao AutoCAD quanto ao AutoCAD LT;
- Cada etapa incluirá uma imagem explicativa.

## Passo 01
Vá na aba **`Padrão`** no canto superior esquerdo. E na parte superior centro irá encontrar a opção **`Propriedades da Camada`**.

<figure>
    <img src="/img/autocad/configurando-layers/img_autocad_configurandolayer_img01.png" alt="Imagem 1" />
    <figcaption>Imagem 1</figcaption>
</figure>

## Passo 02
Ao abrir a aba **`Propriedades de Camada`**, localize o **`Gerenciador de Estados da Camada`** no canto superior direito da aba. Poderá acessá-lo clicando ou apertando **`ALT + S`**.

<figure>
    <img src="/img/autocad/configurando-layers/img_autocad_configurandolayer_img02.png" alt="Imagem 2" />
    <figcaption>Imagem 2</figcaption>
</figure>

## Passo 03
Uma nova aba intitulada **`Gerenciador de Estados da Camada`** será aberta, exibindo todos os estados das camadas do desenho. Caso exista um estado previamente criado, você pode selecioná-lo e excluí-lo clicando no botão **`Excluir`** localizado no canto direito da aba.

<figure>
    <img src="/img/autocad/configurando-layers/img_autocad_configurandolayer_img03.png" alt="Imagem 3" />
    <figcaption>Imagem 3</figcaption>
</figure>

## Passo 04
Clique no botão **`Importar`**, que está localizado na direita. Isso abrirá uma nova aba chamada **`Importar estado de modelo`**, onde você deverá inserir o link fornecido abaixo no campo **`Nome do arquivo`**, e ir no botão **`Abrir`**.

```
L:\Drives compartilhados\EMB_ENGENHARIA_BIBLIOTECA\PADRÕES PROGRAMAS\AUTOCAD\PADRÕES LAYERS
```

<figure>
    <img src="/img/autocad/configurando-layers/img_autocad_configurandolayer_img04.png" alt="Imagem 4" />
    <figcaption>Imagem 4</figcaption>
</figure>

## Passo 05
Ainda na aba **`Importar estado de modelo`**, no campo **`Arquivos do tipo`**, selecione a opção de **`(*.las)`**.

<figure>
    <img src="/img/autocad/configurando-layers/img_autocad_configurandolayer_img05.png" alt="Imagem 5" />
    <figcaption>Imagem 5</figcaption>
</figure>

## Passo 06
Selecione o arquivo **`PADRÃO-REDECAM`**, e clique no botão **`Abrir`**.

<figure>
    <img src="/img/autocad/configurando-layers/img_autocad_configurandolayer_img06.png" alt="Imagem 6" />
    <figcaption>Imagem 6</figcaption>
</figure>

## Passo 07
Nesse passo, duas situações podem ocorrer. Se aparecer a mensagem **`Não foi possível restaurar todos os tipos de linha`**, como mostrado na Imagem 07, será necessário ir para a seção de <a href="#erro-01">Erro 01</a>. Caso seja exibido o aviso **`Estado da camada - Importação com êxito`**, clique no botão **`Fechar a caixa de diálogo`**, como demonstrado na Imagem 08.

<figure>
    <img src="/img/autocad/configurando-layers/img_autocad_configurandolayer_img07.png" alt="Imagem 7" />
    <figcaption>Imagem 7</figcaption>
</figure>

<figure>
    <img src="/img/autocad/configurando-layers/img_autocad_configurandolayer_img08.png" alt="Imagem 8" />
    <figcaption>Imagem 8</figcaption>
</figure>

## Passo 08
Voltando a aba intitulada **`Gerenciador de Estados da Camada`**, selecione o estado de camada **`PADRÃO-REDECAM`**, e na parte de baixo em **`Opções de restauração`** deixe desmarcado a opção **`Desativar camadas não encontradas no estado da camada`**, e clique no botão **`Restaurar`** na parte inferior direita.

<figure>
    <img src="/img/autocad/configurando-layers/img_autocad_configurandolayer_img09.png" alt="Imagem 9" />
    <figcaption>Imagem 9</figcaption>
</figure>

## Passo 09
Ao fechar a aba do **`Gerenciador de Estados da Camada`**, podera ver as **`Propriedades de Camada`**, com suas devidas configurações, como a Imagem 10.

<figure>
    <img src="/img/autocad/configurando-layers/img_autocad_configurandolayer_img10.png" alt="Imagem 10" />
    <figcaption>Imagem 10</figcaption>
</figure>

## Erro 01
Abra o **`REDECAM AutoCAD Template`**, disponível no link abaixo, e copie o **`Bloco de Camada`** (Na Imagem 11, você pode ver a localização do bloco). Mova-o para dentro do desenho e, em seguida, reinicie o processo desde o início.

```
L:\Drives compartilhados\EMB_ENGENHARIA_BIBLIOTECA\PADRÕES CLIENTES\REDECAM\REDECAM AutoCAD Template R19.dwg
```

<figure>
    <img src="/img/autocad/configurando-layers/img_autocad_configurandolayer_img11.png" alt="Imagem 11" />
    <figcaption>Imagem 11</figcaption>
</figure>