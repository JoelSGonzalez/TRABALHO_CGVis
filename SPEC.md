# Especificação da Implementação

> [!CAUTION]
> - Você <ins>**não pode utilizar ferramentas de IA para escrever esta
>   especificação**</ins>

> [!WARNING]
> - Após a entrega da primeira versão completa, esta especificação não
>   poderá ser alterada. A implementação final deverá corresponder ao que
>   estiver descrito neste arquivo.

## Integrantes da dupla

- **Aluno 1 - Nome**: <mark>`Joel Soares González`</mark>
- **Aluno 1 - Cartão UFRGS**: <mark>`00550073`</mark>

- **Aluno 2 - Nome**: <mark>`Nickolas Xisto Machado`</mark>
- **Aluno 2 - Cartão UFRGS**: <mark>`00341038`</mark>

## Detalhes do que será implementado

- **Título do trabalho**: <mark>`INFNAF`</mark>
- **Parágrafo curto descrevendo o que será implementado**: <mark>`A aplicação será um jogo de terror ambientado na secretaria do Diretório Acadêmico da Computação, a "lojinha do DACOMP". Neste jogo, o jogador é um bolsista resposável por atender clientes à noite e realizar pequenas tarefas relacionadas. O bolsista deve tentar atender o máximo possível de clientes para se manter na bolsa. Entretanto, além de clientes normais, haverão monstros tentando entrar que devem ser evitados. Alguns podem se disfarçar como clientes e você deve negar seus pedidos, caso não o faça, irão lhe assustar e após três falhas, matá-lo. Um tentará entrar pelas janelas que estão abertas pra sair o cheiro do banheiro que fica em cima. Quando ver algo estranho em uma das janelas, o jogador deverá fechá-la até que a anomalia desapareça. Se a anomalia permanecer por determinado tempo, o monstro entra e o jogo acaba. Um outro monstro tentará entrar pela porta lentamente. O bolsista deve ficar atento à câmera de segurança em frente para vê-lo se aproximar e então fechar a porta e apagar as luzes.`</mark>

## Especificação visual

### Vídeo - Link

> [!IMPORTANT]
> - Coloque aqui um link para um vídeo que mostre a aplicação gráfica
>   de referência que você vai implementar. **Sua implementação deverá
>   ser o mais parecido possível com o que é mostrado no vídeo (mais
>   detalhes abaixo).**
> - **Você não pode escolher como referência: (1) algum trabalho realizado
>   por outros alunos desta disciplina, em semestres anteriores. (2) Minecraft.**
> - Por exemplo, você pode colocar um vídeo de um jogo que você gosta,
>   e seu trabalho final será uma re-implementação do jogo.
> - O vídeo pode ser um link para YouTube, Google Drive, ou arquivo mp4 dentro
>   do próprio repositório. Mas, garanta que qualquer um tenha
>   permissão de acesso ao vídeo através deste link.

<mark>`[Gameplay de referência](https://www.youtube.com/watch?v=awLLNEvZ-1c)`</mark>

### Vídeo - Timestamp

> [!IMPORTANT]
> - Coloque aqui um **intervalo de ~30 segundos** do vídeo acima, que
>   será a base de comparação para avaliar se o seu trabalho final
>   conseguiu ou não reproduzir a referência.

- **Timestamp inicial**: <mark>`30s`</mark>
- **Timestamp final**: <mark>`70s`</mark>

### Imagens

> [!IMPORTANT]
> - Coloque aqui **três imagens** capturadas do vídeo acima, que você
>   irá usar como ilustração para as explicações que vêm abaixo.
> - As imagens devem estar armazenadas neste repositório, no diretório
>   `images/spec/`, com os nomes `image1`, `image2` e `image3`.
> - Cada imagem deve usar o formato `.jpg` ou `.png`. Ajuste a extensão
>   nos vínculos abaixo para que corresponda ao arquivo armazenado.
> - Escolha imagens que correspondam a momentos do intervalo indicado
>   acima ou que sejam relevantes para a comparação com a implementação.

#### Imagem 1

- **Descrição**: <mark>`<preencher>`</mark>

![Imagem 1](images/spec/image1.jpg)

#### Imagem 2

- **Descrição**: <mark>`<preencher>`</mark>

![Imagem 2](images/spec/image2.jpg)

#### Imagem 3

- **Descrição**: <mark>`<preencher>`</mark>

![Imagem 3](images/spec/image3.jpg)

## Especificação textual

Para cada um dos requisitos abaixo (detalhados no [Enunciado do Trabalho final - Moodle](https://moodle.ufrgs.br/mod/assign/view.php?id=6302370)), escreva um parágrafo **curto** explicando como este requisito será atendido, apontando itens específicos do vídeo/imagens que você incluiu acima que atendem estes requisitos.

### Malhas poligonais complexas
<mark>`O jogo terá um espaço 3D com diversos objetos variados e.g. produtos, estantes, cadeiras`</mark>

### Transformações geométricas controladas pelo usuário
<mark>`O usuário poderá se mover e interagir com objetos dentro do cenário, os movendo e/ou rotacionando.`</mark>

### Diferentes tipos de câmeras
<mark>`A modalidade principal será uma câmera em primeira pessoa, sendo possível alterar para uma câmera externa fixada.`</mark>

### Instâncias de objetos
<mark>`Os produtos dentro da aplicação devem possuir mais de uma instância em posições diferentes.`</mark>

### Testes de intersecção
<mark>`O personagem controlado pode se mover pelo espaço virtual e serão implementadas colisões com elementos do cenário como paredes, mesas, etc.`</mark>

### Modelos de Iluminação em todos os objetos
<mark>`<preencher>`</mark>

### Mapeamento de texturas em todos os objetos
<mark>`<preencher>`</mark>

### Movimentação com curva Bézier cúbica
<mark>`A curva de Bézier será implementada na movimentação dos personagens não jogáveis. Seu caminho através da cena será definido por uma curva.`</mark>

### Animações baseadas no tempo ($\Delta t$)
<mark>`<preencher>`</mark>

### Funcionalidade extra obrigatória

> [!IMPORTANT]
> - Descreva a funcionalidade extra relacionada à Computação Gráfica
>   que será implementada.
> - Esta funcionalidade também deverá ser documentada no arquivo
>   `README.md` da entrega final.

<mark>`<preencher>`</mark>

## Limitações esperadas

> [!IMPORTANT]
> - Coloque aqui uma lista de detalhes visuais ou de interação que
>   aparecem no vídeo e/ou imagens acima, mas que você **não pretende
>   implementar** ou que você **irá implementar parcialmente**.
> - Para cada item, **explique por que** não será implementado ou por
>   que será implementado parcialmente.

<mark>`<preencher>`</mark>
