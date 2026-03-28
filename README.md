Al : GPT =>
CÂU LỆNH : giữ nguyên đoạn code này thêm vào (css) tạo ra giao diện đúng như trên

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>MacBook Neo</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f5f5f7;
        }

        /* Vùng 1 */
        div:nth-child(1) {
            background-color: #fff;
            padding: 10px;
            font-size: 14px;
        }

        select, button {
            padding: 6px 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        button {
            background-color: #0071e3;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #005bb5;
        }

        /* Vùng 2 - menu */
        div:nth-child(2) {
            background-color: #000;
            padding: 12px;
        }

        div:nth-child(2) a {
            color: white;
            text-decoration: none;
            font-size: 14px;
        }

        div:nth-child(2) a:hover {
            text-decoration: underline;
        }

        /* Vùng 3 - tiêu đề */
        div:nth-child(3) {
            padding: 40px 0 10px;
        }

        h1 {
            font-size: 40px;
            margin: 0;
        }

        div:nth-child(3) p {
            font-size: 18px;
            color: #555;
        }

        /* Vùng 4 - nút */
        div:nth-child(4) {
            margin-top: 10px;
        }

        div:nth-child(4) button {
            margin: 5px;
            padding: 10px 20px;
            font-size: 16px;
        }

        /* Vùng 5 - hình */
        div:nth-child(5) img {
            margin-top: 20px;
            border-radius: 15px;
        }
    </style>

</head>

<body>

<!-- VÙNG 1: Chọn quốc gia -->
<div align="center">
    <p>
        Chọn quốc gia hoặc khu vực:
        <select>
            <option>Việt Nam</option>
        </select>
        <button>Tiếp tục</button>
    </p>
</div>

<!-- VÙNG 2: Menu ngang -->
<div align="center">
    <p>
        <a href="#">Store</a> &nbsp;&nbsp;
        <a href="#">Mac</a> &nbsp;&nbsp;
        <a href="#">iPad</a> &nbsp;&nbsp;
        <a href="#">iPhone</a> &nbsp;&nbsp;
        <a href="#">Watch</a> &nbsp;&nbsp;
        <a href="#">AirPods</a> &nbsp;&nbsp;
        <a href="#">Support</a>
    </p>
</div>

<!-- VÙNG 3: Tiêu đề -->
<div align="center">
    <h1>MacBook Neo</h1>
    <p>Amazing Mac. Surprising price.</p>
</div>

<!-- VÙNG 4: Nút -->
<div align="center">
    <button>Learn more</button>
    <button>Buy</button>
</div>

<!-- VÙNG 5: Hình -->
<div align="center">
    <br>
    <img src="https://via.placeholder.com/500x300">
</div>

</body>
</html>
