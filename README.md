Pular para o conteúdo
Menu de navegação

Produto

Soluções

Recursos

Código aberto

Empresa
Preços

Entrar
Inscrever-se
mulheresmascheti
/
criando-sua-aventura
Público
Código
Problemas
5
Solicitações de pull
15
Ações
Projetos
Segurança
Percepções
Comprometer-se
projeto final
 principal
@femascheti
femascheti de autoria em 13 de março 
0 pais
cometer 9c65463
 
Exibindo 6 arquivos alterados com 134 adições e 0 exclusões .
Filtrar arquivos alterados
 Arquivo binário adicionadoBIN +2,53MB 
img/scenario-step0.png
Carregando
 Arquivo binário adicionadoAM +213 KB 
img/cenario-passo11-cidade-perdida.png
Carregando
 Arquivo binário adicionadoSOU +348KB 
img/cenario-passo4-voltar-casa.png
Carregando
 90 alterações: 90 adições e 0 exclusões90 
índice.html
Número da linha do arquivo original	Número da linha de diferença	Mudança de linha diferencial
@@ -0,0 +1,90 @@
<!DOCTYPE html >
< html  lang =" pt-BR " >
< cabeça >
    < meta  charset =" UTF-8 " >
    < meta  name =" viewport " content =" width=largura-do-dispositivo, escala-inicial=1.0 " >
    < link  rel =" folha de estilo " href =" style.css " >
    < link  rel =" pré-conexão " href =" https://fonts.googleapis.com " >
    < link  rel =" preconnect " href =" https://fonts.gstatic.com " crossorigin >
    < link  href =" https://fonts.googleapis.com/css2?family=Bai+Jamjuree:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,200;1,300;1,400;1,500;1,600;1,700&display=swap " rel =" folha de estilo " >
    <title>Em busca da cidade perdida</title>
</ cabeça >
< corpo >
    < principal >
        <div class="passo ativo" id="passo-0">
            < img  src =" img/scenario-passo0.png " alt ="" >
            <p>Um dia desses, dentro de um livro da biblioteca da escola, eu descobri uma carta antiga sobre uma cidade perdida, escondida por riquezas e belezas naturais. Nessa carta, a autora deixa algumas pistas para encontrar essa cidade e eu decidi segui-las!</p>
            < button  class =" btn-proximo " data-proximo =" 1 " > Rio de Janeiro </ button >
            < button  class =" btn-proximo " data-proximo =" 2 " > Pernambuco </ button >
        </div>​​
        < div  class =" passo " id =" passo-1 " >
            <p>Você começa sua jornada no Rio de Janeiro, subindo o Pico da Tijuca ao amanhecer para encontrar a primeira pista.</p>
            < button  class =" btn-proximo " data-proximo =" 3 " > Procurar a pista no topo do pico </ button >
            < button  class =" btn-proximo " data-proximo =" 4 " > Desistir e voltar para casa </ button >
        </div>​​
        < div  class =" passo " id =" passo-2 " >
            <p>Em Pernambuco, você visita a histórica cidade de Olinda. Na carta, uma das pistas indica que para localizar a entrada para a cidade perdida você deve procurar a próxima pista em um dos pontos turísticos da cidade. Por qual você começa?</p>
            < button  class =" btn-proximo " data-proximo =" 5 " > Investigar as roupas antigas </ button >
            < button  class =" btn-proximo " data-proximo =" 6 " > Explorar as praias próximas </ button >
        </div>​​
        < div  class =" passo " id =" passo-3 " >
            <p>No topo do Pico da Tijuca, você encontra uma antiga inscrição apontando que a próxima pista está
                localizada no Amazonas.</p>
            < button  class =" btn-proximo " data-proximo =" 7 " > Seguir para o Amazonas </ button >
        </div>​​

        < div  class =" passo " id =" passo-4 " >
            < img  src =" img/cenario-passo4-voltar-casa.png " alt =" imagem voltando para casa e desitindo da aventura " >
            <p>Você decide que a aventura é grande demais e volta para casa, mas sempre se pergunta o que teria
                encontrado.</p>
        </div>​​

        < div  class =" passo " id =" passo-5 " >
            <p>Nas igrejas de Olinda, você descobre um mapa antigo escondido atrás de um altar, apontando que a próxima
                pista está no Amazonas.</p>
            < button  class =" btn-proximo " data-proximo =" 7 " > Viajar para o Amazonas </ button >
        </div>​​

        < div  class =" passo " id =" passo-6 " >
            <p>Explorando as praias, você encontra uma caverna escondida, mas ela leva a um beco sem saída.</p>
            < button  class =" btn-proximo " data-proximo =" 8 " > Volte e explore as igrejas </ button >
        </div>​​

        < div  class =" passo " id =" passo-7 " >
            <p>No Amazonas, a busca pela cidade perdida se intensifica. Você se depara com um rio bifurcado.</p>
            < button  class =" btn-proximo " data-proximo =" 9 " > Siga pelo rio à esquerda </ button >
            < button  class =" btn-proximo " data-proximo =" 10 " > Siga pelo rio à direita </ ​​button >
        </div>​​

        < div  class =" passo " id =" passo-8 " >
            <p>De volta às igrejas, você finalmente encontra o mapa antigo. Agora, para o Amazonas!</p>
            < button  class =" btn-proximo " data-proximo =" 7 " > Seguir para o Amazonas </ button >
        </div>​​

        < div  class =" passo " id =" passo-9 " >
            < p > O rio à esquerda leva você a uma cachoeira escondida com inscrições antigas que revelam a entrada da
                cidade perdida.</p>
            < button  class =" btn-proximo " data-proximo =" 11 " > Explorar a cidade perdida </ button >
        </div>​​

        < div  class =" passo " id =" passo-10 " >
            < p > O rio à direita termina em uma área pantanosa. Apesar de belas vistas, não há sinais da cidade perdida
                aqui. </ p >
            < button  class =" btn-proximo " data-proximo =" 12 " > Retorne e tente o outro rio </ button >
        </div>​​

        < div  class =" passo " id =" passo-11 " >
            < img  src =" img/cenario-passo11-cidade-perdida.png " alt =" encontrando uma cidade maravilhosa perdida no Amazonas " >
            <p>Dentro da cidade perdida, você descobre tesouros inimagináveis e decide se dedicar a estudar e preservar
                este lugar </ p >
        </div>​​

        < div  class =" passo " id =" passo-12 " >
            <p>Retornando e escolhendo o rio à esquerda, você finalmente encontra a cachoeira escondida e as inscrições
                que levam à cidade perdida.</p>
            < button  class =" btn-proximo " data-proximo =" 11 " > Explorar a cidade perdida </ button >
        </div>​​
    </ principal >
    < script  src =" script.js " > </ script >
</ corpo >
</ html >
 11 alterações: 11 adições e 0 exclusões11 
script.js
Número da linha do arquivo original	Número da linha de diferença	Mudança de linha diferencial
@@ -0,0 +1,11 @@
const  avanca  =  documento . querySelectorAll ( '.btn-proximo' ) ;

avanca . forEach ( botão  =>  {
    botão . addEventListener ( 'clique' ,  função ( ) {
        const atual = document.querySelector('.ativo');
        const  nextPass  =  'passo-'  +  this . getAttribute ( 'dados-próximo' ) ;

        atual.classList.remove('ativo');
        document.getElementById(proximoPasso).classList.add('ativo');
    } )
} )
 33 alterações: 33 adições e 0 exclusões33 
estilo.css
Número da linha do arquivo original	Número da linha de diferença	Mudança de linha diferencial
@@ -0,0 +1,33 @@
corpo {
    cor de fundo :  # 1D4221 ;
    cor : branco;
    família de fontes :  "Bai Jamjuree" , sem serifa;
    exibição : flexível;
    justificar-conteúdo : centro;
    alinhar-itens : centralizar;
    altura :  700 px ;
    margem :  0 ;
}

botão {
    cor de fundo :  # 64A712 ;
    cor : branco;
    família de fontes :  "Bai Jamjuree" , sem serifa;
}

. etapa {
    exibição : nenhuma;
}

.passo.ativo {
    exibir : bloco;
}

principal {
    alinhamento de texto : centralizar;
    largura máxima :  90 % ;
}

imagem {
    largura máxima :  90 % ;
}
1 comentário sobre commit9c65463
@Rafinha240507
Rafinha240507 comentou em9c65463 em 6 de agosto
1projeto final

Por favor, entre para comentar.
Rodapé
© 2024 GitHub, Inc.
Navegação de rodapé
Termos
Privacidade
Segurança
Status
Documentação
Contato
Gerenciar cookies
Não compartilhe minhas informações pessoais
projeto final · femascheti/criando-sua-aventura@9c65463 · GitHub
