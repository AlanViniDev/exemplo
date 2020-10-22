name = "Formulario"
type = "submit"

<!-- Chama a biblioteca jquery -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.form/4.3.0/jquery.form.min.js"></script>
<script src = "https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script src="jquery.2.1.3.min.js"></script>

<!--Ajax Create. -->
<script type = "text/javascript"> 
    $('form[name="Formulario"]').submit(function (event){
        event.preventDefault();
        $.ajax({
            url: "",
            type: "POST",
            data: $(this).serialize(),
            dataType: 'JSON',
            success: function (data){ 
            }
        });
    });
</script>

<!--Ajax Update. -->
<script type = "text/javascript"> 
    $('form[name="FormularioProdutos"]').submit(function (event){
        event.preventDefault();
        $.ajax({
            url: "",
            type: "POST",
            data: $(this).serialize(),
            dataType: 'JSON',
            success: function (data){ 
            }
        });
    });
</script>
