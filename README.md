------------------------------
Feita a correção, faltava o button, para nãoo repetir

    $('.lista-veiculos button') 

 outra forma seria:

    $('.lista-veiculos button').click(function() {
    const destino = $('#contato');
    const nomeVeiculo = $(this).siblings('h3').text();

    $('#veiculo-interesse').val(nomeVeiculo);
    
    $('html').animate({
      scrollTop: destino.offset().top
    }, 1000)

    })
-------------------------------------
bug ao clicar em "Tenho interesse"


![image](https://github.com/gabatist4/jQuery-EBAC-Motors/assets/121689888/a13a1f65-ab6f-46e1-9a76-0f89f8839ad5)
-----------------------------------------
