---
sidebar_position: 3
---

# O que o faz o ArrumaLayerMaterial?

## Informações:

Passará por cada componente, atribuindo-os a uma camada específica correspondente ao seu respectivo material.

Exemplo:

O Plenum possui dois tipos de materiais distintos: AISI 304L e S32205. Os componentes feitos de AISI 304L serão movidos para a camada **``AISI 304L``**, enquanto aqueles feitos de S32205 serão alocados na camada **``S32205``**.

As linhas ocultas permanecerão na camada **``NASCOSTE``**, e os materiais que não tiverem uma camada definida permanecerão na camada **``CONTORNI``**.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img15.png" alt="Imagem 01" />
    <figcaption>Imagem 01</figcaption>
</figure>

## Passo 01
Ir na aba **``Administrar``**, **``Editor de Estilos``**, opção **``Camadas``** e adicionar a camada do material desejado. Observe na Imagem 02.

**IMPORTANTE DIGITAR O NOME IGUAL**

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img16.png" alt="Imagem 02" />
    <figcaption>Imagem 02</figcaption>
</figure>

## Passo 02
Execute o código e ao final ele mostrará os materiais que não foram mexidos, ou uma mensagem de erro, conforme mostra a Imagem 03.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img17.png" alt="Imagem 03" />
    <figcaption>Imagem 03</figcaption>
</figure>