<html>
    <head>
        <title> Fuzzy - Kelayakan Beasiswa </title>
        
        <meta name="viewport" content="user-scalable=no, initial-scale=1, maximum-scale=1, minimum-scale=1, width=device-width">
        <link href="lib/bootstrap/css/bootstrap.min.css" rel="stylesheet">

        <script src="lib/jquery/jquery.min.js" type="text/javascript"></script>
        <script src="lib/bootstrap/js/bootstrap.min.js" type="text/javascript"></script>
        <script src="script/fuzzy.js" type="text/javascript"></script>
    </head>
    <body>

        <div class="container" style="margin-top:30px; max-width:600px; position:relative;">
            
            <hr><h1> Tugas Praktikum Fuzzy <br> <small> Studi Kasus: Kelayakan Beasiswa </small> </h1>            
            <hr><h4> 201951071 | Firman Adi Nur Fatin </h4>
            <h5> Repositori GitHub: <a href="https://github.com/psychohaxer/fuzzy-beasiswa">psychohaxer/fuzzy-beasiswa</a></h5><hr>
            
            <div class="form-group">
                <label> IPK (0-4) </label>
                <input class="form-control" type="text" value="3" id="inIPK">
            </div>
            
            <div class="form-group">
                <label> Gaji (juta) </label>
                <input class="form-control" type="text" value="10" id="inGaji">
            </div>
            
            <button class="btn btn-primary btn-block btn-lg" id="btnProses"> Proses </button>
            
            <div id="divOut"> </div>
            
            <img src="img/mamdani.jpg" style="width:100%; border:1px solid #eef;"> <hr>
            <img src="img/sugeno.jpg" style="width:100%; border:1px solid #fcf8e3;"> <hr>
            
            <div class="alert alert-success">
                <strong> REFERENSI: </strong> <a href="pdf/fuzzy - contoh kasus beasiswa.pdf" target="_blank"> Download PDF </a>
            </div>
            
        </div>
   
    </body>
</html> 
