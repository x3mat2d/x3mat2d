<!DOCTYPE html>
<html lang="en">
<head>
    <title>VALIDASI PEMERIKSAAN LABKES KALTIM</title>
    <meta charset="UTF-8">
    <meta name=description content="">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Bootstrap CSS -->
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
    <style>
        th, td {
            font-size: 9pt;
            padding: 5px;
        }

        table.table-bordered{
            border:1px solid black;
            margin-top:20px;
        }
        table.table-bordered > thead > tr > th{
            border:1px solid black;
        }
        table.table-bordered > tbody > tr > td{
            border:1px solid black;
        }

        .fonts{
            font-family: Tahoma, sans-serif;
        }

        @media  print and (width: 11cm) and (height: 22cm) {
            @page  {
                margin: :0.5cm;
            }
        }
        @page  {
            size: F4 portrait;
            margin: 5%;
        }

        tr:nth-child(even) {
            background-color: #dddddd;
        }

        @media  print {
            tfoot {
                display:table-row-group;
                bottom: 0;
                height: 50px;
                width: 100%;
                position: sticky;

            }
        }

        .btn-circle {
            width: 30px;
            height: 30px;
            text-align: center;
            padding: 6px 0;
            font-size: 12px;
            line-height: 1.428571429;
            border-radius: 15px;
        }
        .btn-circle.btn-lg {
            width: 50px;
            height: 50px;
            padding: 10px 16px;
            font-size: 18px;
            line-height: 1.33;
            border-radius: 25px;
        }
        .btn-circle.btn-xl {
            width: 80px;
            height: 80px;
            padding: 10px 16px;
            font-size: 50px;
            line-height: 1.33;
            border-radius: 50px;
        }
    </style>
</head>
<body>
<div class="container">
    <div class="row">

            <div class="col-md-2">
            </div>
            <div class="col-md-8 fonts">
                <img class="center" style="display: block;" width="100%" src="https://sil.labkeskaltim.com/upload/logo/kop2.jpeg" alt="kop"><br/>
                                                    <center>
                        <button type="button" class="btn btn-success btn-circle btn-xl" style="text-align: center"><i class="glyphicon glyphicon-ok"></i></button><br/>
                        <strong style="color: green">TERVERIFIKASI</strong>
                    </center>
                    <hr style="border: 1px solid black;">
                    <strong>DATA PASIEN</strong><br/>
                    <table style="margin-bottom: 20px">
                        <tr>
                            <th>NIK</th>
                            <td>:</td>
                            <td>6472040902790004</td>
                        </tr><tr>
                            <th>NAMA</th>
                            <td>:</td>
                            <td>MUDIYAT NOOR</td>
                        </tr>
                    </table>
                    <hr>
                    <strong>DATA PEMERIKSAAN</strong><br/>
                    <table>
                        <tr>
                            <th>TANGGAL</th>
                            <td>:</td>
                            <td>10/08/2021
                            </td>
                        </tr>
                        <tr>
                            <th>KODE FPPS</th>
                            <td>:</td>
                            <td>26404</td>
                        </tr>
                        <tr>
                            <th>HASIL</th>
                            <td>:</td>
                            <td>
                                NEGATIF
                            </td>
                        </tr>
                    </table><br/>
                                Nomor yang bisa dihubungi jika ada kendala dengan hasil pemeriksaan : <strong>+62 812-5463-263</strong>

            </div>
            <div class="col-md-2">
            </div>

    </div>
</div>
<script>
    // window.print();
</script>
</body>
</html>

