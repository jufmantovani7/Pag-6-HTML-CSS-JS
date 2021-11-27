# Pag-6-HTML-CSS-JS
Pagina 6
<!DOCTYPE html>
<html>
    <head>
        <meta charset=utf-8>
        <style>
            body {
            background-color: #000
            }
            </style>

        <style>
            body {
                color:#FFFFFF

            }
            </style>
            <center>
        <title>Loja Virtual Games Mania</title>
        <br><p><h1>Noticias</h1></p>
            </br>
          </center>
        <hr style="width:100%;height: 7px;px;background-color:blue">
        <center>
        <p><h1>Noticias do mundo de Tecnológia e Games virtuais</h1></p>
    </center>
        <br>
        <hr style="width:100%;height: 7px;px;background-color:blue">
        <p>Razer anuncia produtos para o PS5 - headsets Kaira e base carregadora</p>
         <img src="http://freedomuniversity.net/example/slide1m.jpg" width="20%"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://i.pinimg.com/originals/2c/1f/31/2c1f3178b6a8c66276d64cdaf3dbe1b1.jpg" width="20%"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="http://freedomuniversity.net/example/slide1m.jpg" width="20%"/>
         <center>
             &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <a href="https://www.tecmundo.com.br/voxel/229073-razer-anuncia-produtos-ps5-headsets-kaira-base-carregadora.htm"><button> clique aqui</button></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </center>
        </br>
        <script src="https://code.jquery.com/jquery-latest.min.js"></script>
    </head>
    <body>
      <form action="javascript:void(0);">
        <label>Você gostou do Site Games Mania</label>
        <input type="radio" name="sim" id="sim"><label>SIM</label>
        <input type="radio" name="não" id="não"><label>NÃO</label>
        <input type="submit" id="button">
      </form>
    </body>
  
    <script>
     $('#button').click(function(){
        if($('#sim').is(':checked')){
          alert("Você escolheu Sim, Obrigada por usar o nosso serviço");
        }else if($('#não').is(':checked')){
          alert('Você escolheu Não, sua resposta é fundamental para melhorarmos os nossos serviços. Obrigada por usar o nosso serviço.');
        }else{
          alert('Você não escolheu');
        }
      });
    </script>
        
    </body>
</html>
