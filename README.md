#LabaWeb3
1. Membuat ordered list
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTP-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat List</h1>
        <seletion id="order-list">
            <h2>Orderan List</h2>
            <ol>
                <li>Pemograman Web</li>
                <li>Sistem Informasi</li>
                <li>Basis Data 2</li>
            </ol>
        </seletion>
    </header>
</body>
</html>
![Screenshot (242)](https://github.com/user-attachments/assets/e3c85dde-6b06-44c2-9b79-6546e06f990f)

2. membuat unorderd list
   <section id="unorder-list">
            <h2>Unordered List</h2>
            <ul type="square">
                <li>Jaringan Komputer</li>
                <li>Struktur Data</li>
                <li>Algoritma &amp; Pemograman</li>
            </ul>
        </section>
![Screenshot (243) - Copy](https://github.com/user-attachments/assets/7e9cf799-f87c-4c9c-8a9e-4acd1f4ce40d)

3. membuat description list
   <section id="unorder-list">
            <h2>Description List</h2>
            <dl>
                <dt>Fakultas Teknik</dt>
                <dd>Teknik Industri</dd>
                <dd>Teknik Informatika</dd>
                <dd>Teknik Lingkungan</dd>
                <dt>Fakultas Ekonomi dan Bisnis</dt>
                <dd>Akuntansi</dd>
                <dd>Manajemen</dd>
                <dd>Bisnis Digital</dd>
            </dl>
  ![Screenshot (243)](https://github.com/user-attachments/assets/4c2cdc13-610b-4235-9490-bff11114e494)

  4. membuat table
     <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTP-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Table</h1>
    </header>
    <table border="1" cellpadding="4" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td>Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
</body>
</html>

![Screenshot (245)](https://github.com/user-attachments/assets/0b834513-0610-418e-a6c6-affd317b5a44)

5. menggabungkan sel data
<table border="1" cellpadding="6" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td rowspan="3">Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>

  ![Screenshot (246)](https://github.com/user-attachments/assets/a15c2862-8ade-449f-baf7-d69301136465)

    6. membuat form
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTP-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Form</h1>
    </header>
    <form action="proses.php" method="post">
        <fieldset>
            <legend>Data Pelanggan</legend>
            <p>
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama">
            </p>
            <p>
                <label for="alamat">Alamat</label>
                <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
            </p>
            <p>
                <label>Jenis Kelamin</label>
                <input id="jk_1" type="radio" name="kelamin" value="L" /><label for="jk_1 ">Laki-laki</label>
                <input id="jk_p" type="radio" name="kelamin" value="p" /><label for="jk_p">Perempuan</label>
            </p>
            <p><input type="submit" value="Login"></p>
        </fieldset>
    </form>
    
</body>
</html>

![Screenshot (247)](https://github.com/user-attachments/assets/608eb905-361a-406e-a7ed-539d728cf2ed)

7. menambahkan style pada form
form p > label {
    display: inline-block;
    width: 100px;
}

form input[type="text"], form textarea {
    border: 1px solid #197a43;
}

form input[type="submit"] {
    border: 1px solid #197a43;
    background-color: #197a43;
    color: #ffffff;
    font-weight: bold;
    padding: 5px 15px;
}
![Screenshot (248)](https://github.com/user-attachments/assets/759b1586-57af-4b7a-b671-30e3dc6c14f3)

   
