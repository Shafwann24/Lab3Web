<h1>Pertanyaan dan Tugas</h1>
<h2>Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection. </h2>
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

<hr>
<h2>1. </h2>
