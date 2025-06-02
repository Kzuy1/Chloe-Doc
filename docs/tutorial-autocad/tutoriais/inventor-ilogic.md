---
sidebar_position: 3
---

# ⚙️ Inventor ILogic

## 1 - Como adicionar códigos no ILogic?

**1.1**  - No canto superior Esquerdo, vá na aba **"Ferramentas"** e depois na aba **"Opções"**.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img01.png" alt="Imagem 1" />
    <figcaption>Imagem 1</figcaption>
</figure>

**1.2** - Com a aba **"Opções"** aberta, clique em **"Configuração do ILogic"**.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img02.png" alt="Imagem 2" />
    <figcaption>Imagem 2</figcaption>
</figure>

**1.3** - Com a aba **"Configuração avançada do ILogic"** aberta, vá no canto superior e clique no **Botão com Sinal (+) Azul**.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img03.png" alt="Imagem 3" />
    <figcaption>Imagem 3</figcaption>
</figure>

**1.4** - Com a aba **"Procurar Pasta"** aberta, copie o link abaixo:

```
L:\Drives compartilhados\EMB_ENGENHARIA_BIBLIOTECA\PADRÕES PROGRAMAS\AUTODESK\ILogic
```

Ao copiar, coloque no campo **"Pasta"** e clique no botão **"Ok"**.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img04.png" alt="Imagem 4" />
    <figcaption>Imagem 4</figcaption>
</figure>

**1.5** - Clique no Botão **"Ok"**.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img05.png" alt="Imagem 5" />
    <figcaption>Imagem 5</figcaption>
</figure>

**1.6** - Vá no cantor superior esquerdo, você vai ver um icone **"+"**. Clique nele e selecione a opção **"ILogic"**.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img06.png" alt="Imagem 6" />
    <figcaption>Imagem 6</figcaption>
</figure>

**1.7** - Irá aparecer uma aba chamada **"ILogic"**, após isso clique em **"Regras externas"**.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img07.png" alt="Imagem 7" />
    <figcaption>Imagem 7</figcaption>
</figure>

**1.8** - Clique expandir a opção **"Diretórios Padrões"**,  e novamente expanda a pasta **"ILogic"**.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img08.png" alt="Imagem 8" />
    <figcaption>Imagem 8</figcaption>
</figure>

**1.9** - Irá aparecer os **"Códigos"**, e para executar apenas clique com o **botão direito** na regra que deseja e clique na opção de **"Executar Regra"**.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img09.png" alt="Imagem 9" />
    <figcaption>Imagem 9</figcaption>
</figure>


---

## 2 - O que o faz o MoverParaExistente?

Ela moverá todas as peças e suas respectivas peças filhas conforme o parâmetro fornecido.

Exemplo:

No Plenum, a chapa espelho será deixada como existente, então ela será movida para outra layer.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img10.png" alt="Imagem 10" />
    <figcaption>Imagem 10</figcaption>
</figure>

**2.1** - Clique executar a regra. E o programa vai solicitar o código da peça.

> **PONTO IMPORTANTE.**  
> Passe exatamente o Código da Peça.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img11.png" alt="Imagem 11" />
    <figcaption>Imagem 11</figcaption>
</figure>

**2.2** - Ao final do processo, aparecerá uma mensagem escrito Finalizado!

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img12.png" alt="Imagem 12" />
    <figcaption>Imagem 12</figcaption>
</figure>

**2.3** - Caso apareça uma mensagem de erro, será necessário acessar a aba “Administrar”, opção “Camadas”, e adicionar as camadas “ESISTENTE” e “ESISTENTE-NASCOSTE”.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img13.png" alt="Imagem 13" />
    <figcaption>Imagem 13</figcaption>
</figure>

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img14.png" alt="Imagem 14" />
    <figcaption>Imagem 14</figcaption>
</figure>

---

## 3 - O que o faz o ArrumaLayerMaterial?

Passará por cada componente, atribuindo-os a uma camada específica correspondente ao seu respectivo material.

Exemplo:

O Plenum possui dois tipos de materiais distintos: AISI 304L e S32205. Os componentes feitos de AISI 304L serão movidos para a camada “AISI 304L”, enquanto aqueles feitos de S32205 serão alocados na camada “S32205”.

As linhas ocultas permanecerão na camada “NASCOSTE”, e os materiais que não tiverem uma camada definida permanecerão na camada “CONTORNI”.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img15.png" alt="Imagem 15" />
    <figcaption>Imagem 15</figcaption>
</figure>

**3.1** - Ir na aba Administrar, Editor de Estilos, opção camadas e adicionar a camada do material desejado. 

**IMPORTANTE DIGITAR O NOME IGUAL**

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img16.png" alt="Imagem 16" />
    <figcaption>Imagem 16</figcaption>
</figure>

**3.2** - Execute o código e ao final ele mostrará os materiais que não forma mexidos, ou uma mensagem de erro.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img17.png" alt="Imagem 17" />
    <figcaption>Imagem 17</figcaption>
</figure>

---

## 4 - O que o faz o ArrumaNumeroEUnidadeDaPeca?

O script percorre cada componente, verificando se o número da peça está igual ao nome do arquivo. Além disso, atualiza o comprimento para milímetros e a massa para quilogramas.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img18.png" alt="Imagem 18" />
    <figcaption>Imagem 18</figcaption>
</figure>

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img19.png" alt="Imagem 19" />
    <figcaption>Imagem 19</figcaption>
</figure>

---

## 5 - Como utilizar o Estado de Modelo?

O recurso "Model State" possibilita o salvamento de diversos estados do modelo sem afetar a versão principal. Um exemplo prático disso é observado no Plenum, em que a chapa espelho é incluída no modelo, mas pode ser suprimida permitindo a extração da lista de material sem considerar a chapa espelho.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img20.png" alt="Imagem 20" />
    <figcaption>Imagem 20</figcaption>
</figure>

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img21.png" alt="Imagem 21" />
    <figcaption>Imagem 21</figcaption>
</figure>

**5.1** - Para criar um Estado de Modelo, crie com botão direito e clique em novo.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img22.png" alt="Imagem 22" />
    <figcaption>Imagem 22</figcaption>
</figure>

---

## 6 - O que faz o PlanificacaoExportacaoChapa?

Esse script automatiza a planificação e exportação de chapas em DXF, além de gerar uma lista de corte em um arquivo Excel.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img23.png" alt="Imagem 23" />
    <figcaption>Imagem 23</figcaption>
</figure>

**6.1** - Se você receber uma mensagem informando que o arquivo já existe, poderá optar por substituí-lo clicando em "Sim". Caso prefira não substituir, será solicitada uma confirmação para salvar o arquivo em um local diferente.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img24.png" alt="Imagem 24" />
    <figcaption>Imagem 24</figcaption>
</figure>

**6.2** - Se receber uma mensagem sobre furos com rosca, será necessário abrir o arquivo DXF mencionado para verificar e remover esses furos.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img25.png" alt="Imagem 25" />
    <figcaption>Imagem 25</figcaption>
</figure>

---

## 7 - O que faz o Nesting1D?

Este script automatiza a criação de estudos de corte e otimização para formas estruturais, como perfis, tubos e barras.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img26.png" alt="Imagem 26" />
    <figcaption>Imagem 26</figcaption>
</figure>

**7.1** - Caso apareça a mensagem **"Perfis cujo comprimento não foi possível determinar"**, esses itens serão considerados com comprimento de 0 mm e o cálculo deverá ser ajustado manualmente na planilha.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img27.png" alt="Imagem 27" />
    <figcaption>Imagem 27</figcaption>
</figure>

**7.2** - Será criada, na mesma pasta onde o modelo está salvo, uma pasta chamada NESTING1D. Nela, será possível encontrar um arquivo Excel que contém o estudo de corte e um arquivo de texto que exibe a mesma mensagem de erro descrita no <a href="#7---o-que-faz-o-nesting1d">item 7.1</a>.

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img28.png" alt="Imagem 28" />
    <figcaption>Imagem 28</figcaption>
</figure>

<figure>
    <img src="/img/autocad/tutoriais/inventor-ilogic/img_autocad_tutoriais_inventor-ilogic_img29.png" alt="Imagem 29" />
    <figcaption>Imagem 29</figcaption>
</figure>

## 7.3 - **OBSERVAÇÕES IMPORTANTES:**

*7.3.1*
Durante a execução do algoritmo para a realização do estudo, é considerado um acréscimo de 6 mm no comprimento das peças, representando a perda decorrente do corte realizado pela serra. Essa consideração é aplicada universalmente, exceto nos casos em que a peça possui exatamente 6000 mm de comprimento.

*7.3.2* – Peças em que é utilizada a ferramenta de revolução são consideradas com 0 mm de comprimento. Podem ser uma chapa ou um perfil.