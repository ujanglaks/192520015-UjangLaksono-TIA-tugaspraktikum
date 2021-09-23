# 192520015-UjangLaksono-TIA-tugaspraktikum

<?php

$nama = "Ujang Laksono";
$nim = 192520015;
$alamat = "Krajan RT 02 / RW 01, Redin, Gebang, Purworejo";
$alamat_email = "ujanglaks@gmail.com";
$minat = "Jaringan";
$universitas = "Universitas Muhammadiyah Purworejo";

echo "<h2>Data Diri</h2>";
echo "<br>";
echo "Nama : ".$nama;
echo "<br>";
echo "NIM : ".$nim;
echo "<br>";
echo "Alamat : ".$alamat;
echo "<br>";
echo "Alamat Email : ".$alamat_email;
echo "<br>";
echo "Bidang Minat : ".$minat;
echo "<br>";
echo "Universitas : ".$universitas;
echo "<br>";

?>

<!DOCTYPE html>
<html>
    <head>
        <title>Index PHP</title>
        <style>
        body{
            background-color: #00FFFF;
            }
        *{
			box-sizing: border-box;
            box-shadow: 0 0.25rem 0.75rem rgba(0,0,0,.03);
			}
		.column{
			margin: 30px;
			}
		.row{
			margin: auto;
			width: 60%;
			}
		.foto img{
			display: block;
			width: 150px;
			height: 230;
            padding: 15px;
			margin-left: auto;
			margin-right: 30;
			padding-top: 1px;
			}
        .text{
            margin-left: auto;
			margin-right: auto;
            }
		html{
			font-family: arial,sans-serif;
			}
        </style>
    </head>

    <body>
        <div class="row">
        <div class="column">

            <?php
            $nama = "Ujang Laksono";
            $nim = 192520015;
            $alamat = "Krajan RT 02 / RW 01, Redin, Gebang, Purworejo";
            $alamat_email = "ujanglaks@gmail.com";
            $minat = "Jaringan";
            $universitas = "Universitas Muhammadiyah Purworejo";
            ?>

            <div class ="text"><table>
            <h2><center>Data Diri</h2>
            <tr><td rowspan="9">
                <div class="foto">
                <img src="profil.jpg"></div></td>
            </tr>
            <tr>
                <td><?php echo "Nama"; ?></td>
                <td><?php echo ":"; ?></td>
                <td><?php echo $nama ;?></td>
            </tr>
            <tr>
                <td><?php echo "NIM"; ?></td>
                <td><?php echo ":"; ?></td>
                <td><?php echo $nim ;?></td>
            </tr>
            <tr>
                <td><?php echo "Alamat"; ?></td>
                <td><?php echo ":"; ?></td>
                <td><?php echo $alamat ;?></td>
            </tr>
            <tr>
                <td><?php echo "Alamat Email"; ?></td>
                <td><?php echo ":"; ?></td>
                <td><?php echo $alamat_email ;?></td>
            </tr>
            <tr>
                <td><?php echo "Bidang Minat"; ?></td>
                <td><?php echo ":"; ?></td>
                <td><?php echo $minat ;?></td>
            </tr>
            <tr>
                <td><?php echo "Universitas"; ?></td>
                <td><?php echo ":"; ?></td>
                <td><?php echo $universitas ;?></td>
            </tr></table>
            </div>
        </div>
        </div>
    </body>
</html>
