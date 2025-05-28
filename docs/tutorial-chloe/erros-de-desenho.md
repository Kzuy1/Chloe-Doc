---
sidebar_position: 3
---

# 🚨 Erros de Desenho
### Todos os Erros que a Chloe pode encontrar.

## Error ED01
O nome arquivo não está separado corretamente.

Os códigos de desenho são separados  por traços (-) e sublinhados (_), conforme demonstrado na Imagem 01.

<figure>
    <img src="/img/chloe/erros-de-desenho/img_chloe_erros-de-desenho_img01.png" alt="Imagem 1" />
    <figcaption>Imagem 1</figcaption>
</figure>

### Solução
Renomeie o arquivo seguindo a segmentação correta.

## Error ED02
Bloco de Legenda está com código errado.

Na Imagem 02, o Bloco de Legenda apresenta um código diferente do que está no Nome do Arquivo. Os códigos mostrados são 1FN2_FN-08-01, mas o correto é 1FN3_FN-A7-01.

<figure>
    <img src="/img/chloe/erros-de-desenho/img_chloe_erros-de-desenho_img02.png" alt="Imagem 2" />
    <figcaption>Imagem 2</figcaption>
</figure>

### Solução
Utilize o Lisp AtualizarCodigoLegenda para atualizar os códigos do Bloco de Legenda.

## Error ED03
Bloco de Legenda está com escala errado.

O Bloco de Legenda apresenta uma discrepância entre a escala exibida e a escala do atributo do bloco, conforme demonstrado na Imagem 03.

<figure>
    <img src="/img/chloe/erros-de-desenho/img_chloe_erros-de-desenho_img03.png" alt="Imagem 3" />
    <figcaption>Imagem 3</figcaption>
</figure>

### Solução
Ajuste a escala para a escala indicada nos atributos de escala do Bloco.

## Error ED04
Bloco de Legenda está com DRAW, CHECKED ou APPROVED errado.

O Bloco de Legenda geralmente fica com : 

> **DRAW:** EMB  
> **CHECKED:** VOL  
> **APPROVED:** Sem nada ou em Branco

<figure>
    <img src="/img/chloe/erros-de-desenho/img_chloe_erros-de-desenho_img04.png" alt="Imagem 4" />
    <figcaption>Imagem 4</figcaption>
</figure>

### Solução
Coloque os atributos indicados acima.

## Error ED06
LTScale está diferente da metade da Escala do Desenho.

Ocorre quando a configuração de LTScale (escala de tipo de linha) não está de acordo com a escala do desenho.

O que é LTScale é como ele funciona?

### Solução
Ajustar o valor do LTScale para ser a metade da escala do desenho, conforme demonstrado na Imagem 05.

<figure>
    <img src="/img/chloe/erros-de-desenho/img_chloe_erros-de-desenho_img04.png" alt="Imagem 4" />
    <figcaption>Imagem 5</figcaption>
</figure>