# -Escrevendo-as-Classes-de-Um-Jogo

classe  modeloHeroi  {
    construtor ( nome ,  idade ,  tipoHeroi )  {
        esse . nome  =  nome ;
        esse . idade  =  idade ;
        esse . tipoHeroi  =  tipoHeroi ;

let  tiposHerois  =  [ "mago" ,  "guereiro" ,  "monge" ,  "ninja" ]
let  nomesHerois  =  [ "Sansa" ,  "Daenarys" ,  "Elektra" ,  "Dolores" ,  "Yennefer" ]

for  ( const  tipos  de  tiposHerois )  {
    for  ( const  nomes  de  nomesHerois )  {
        let  heroi  =  novo  modeloHeroi ( nomes ,  30 ,  tipos )
        herói . atacar ( heroi . definirAtaque ( ) )

    }

    definirAtaque ( )  {
        vamos  atacar ;
        if  ( this . tipoHeroi  ==  "mago" )  {
            ataque  =  "magia"
        }  else  if  ( this . tipoHeroi  ==  "guereiro" )  {
            ataque  =  "espada"
        }  else  if  ( this . tipoHeroi  ==  "monge" )  {
            ataque  =  "artes marciais"
        }  else  if  ( this . tipoHeroi  ==  "ninja" )  {
            ataque  =  "shuriken"
        }

        retornar  ataque ;
    }

    atacar ( atacar )  {
        console . log ( `O ${ this . tipoHeroi } atacou usando ${ ataque } ` )
    }
}
