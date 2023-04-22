# INPUT-TAG-MASKING
input tag masking
Add CDN links
=================
   <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.inputmask/3.3.4/jquery.inputmask.bundle.min.js"></script>


jquery Funcstion
==================
    <script>
        $(document).ready(function()
        {
          $('#zip').inputmask("999-999");
          $('#pin').inputmask("AAA-999");
          $('#adhaar').inputmask("9999-999-9999-9999");
        });
    </script>


Masking Patterns:
==================
 $('selector').inputmask("999-999")

 $('selector').inputmask("AAA-999")

 $('selector').inputmask("aaa-999")

 $('selector').inputmask("+(99)-99999999")

 $('selector').inputmask("+(999)-999-99999")

 $('selector').inputmask("+(AAA)-999-99999")

 $('selector').inputmask("9999-9999-9999-9999")
