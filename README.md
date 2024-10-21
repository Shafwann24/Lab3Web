<h1>Pertanyaan dan Tugas</h1>
1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
<hr
    
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Membuat Form dengan Dropdown Menu dan Listbox</title>
    </head>
    <body>
        <h1>Form Tipe Wanita Idaman</h1>
        <form action="proses.php" method="post">
            <fieldset>
                <legend>Tipe Wanita Anda</legend>
                <p>
                    <label for="usia">Pilih Batas Usia:</label>
                    <select id="usia" name="usia">
                        <option value="19">19</option>
                        <option value="20">20</option>
                        <option value="21">21</option>
                        <option value="22">22</option>
                        <option value="23">23</option>
                        <option value="24">24</option>
                        <option value="25">25</option>
                        <option value="26">26</option>
                        <option value="27">27</option>
                        <option value="28">28</option>
                        <option value="29">29</option>
                        <option value="30">30</option>
                    </select>
                </p>
                <p>
                    <label for="negara">Pilih Asal Negara :</label>
                    <select id="negara" name="negara[]" multiple size="4">
                        <option value="indonesia">indonesia</option>
                        <option value="jepang">jepang</option>
                        <option value="korea">korea</option>
                        <option value="china">china</option>
                        <option value="rusia">rusia</option>
                        <option value="arab">arab</option>
                        <option value="thailand">thailand</option>
                    </select>
                </p>
                <p><input type="submit" value="Submit"></p>
            </fieldset>
        </form>
        <style>
            input[type="submit"] {
                background-color: #4CAF50;
                border: none;
                color: white;
                padding: 12px 24px;
                text-align: center;
                text-decoration: none;
                display: inline-block;
                font-size: 16px;
                margin: 4px 2px;
                cursor: pointer;
                border-radius: 8px;
                transition: background-color 0.3s ease;
            }
            input[type="submit"]:hover {
                background-color: #45a049;
            }
        </style>
    
    </body>
    </html>

![image](https://github.com/user-attachments/assets/34d294cf-d9a2-4f8c-818c-ca672eef8ca2)
<br>

     <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>HTML Lanjutan</title>
    </head>
    <body>
        <header>
            <h1>Membuat List</h1>

<h2>Membuat Ordered List</h2>

    <section id="order-list"> 
        <h2>Ordered List</h2> 
        <ol> 
            <li>Pemrograman Web</li> 
            <li>Sistem Informasi</li> 
            <li>Basis Data 2</li> 
        </ol> 
    </section>

![image](https://github.com/user-attachments/assets/b14ebac2-7b5d-47ec-ac1a-883d039a4ecf)
<br>

 <h2>Unodered List</h2>
 
          <section id="unorder-list">
            <h2>Unordered List</h2>
            <ul style="list-style-type: square;">
                <li>Jaringan Komputer</li>
                <li>Struktur Data</li>
                <li>Algoritma &amp; Pemrograman</li>
            </ul>
        </section>


![image](https://github.com/user-attachments/assets/498a8399-0670-44d4-bb00-5714d74ec151)
<br>

<h2>Membuat Description List<h2>
    
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
    </section> 

![image](https://github.com/user-attachments/assets/1381e3d2-5a3f-4f43-b2a3-69851d0f66ef)
<br>

<h2>Membuat Tabel</h2>

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

<h2>Menggabungkan Sel Data</h2>

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
<br>




