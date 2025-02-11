<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ทฤษฎีบทพีทาโกรัส</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            flex-direction: column;
        }
        .container {
            background-color: #fff;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 800px;
            width: 100%;
            text-align: center;
            margin-bottom: 2rem;
        }
        h1 {
            color: #4CAF50;
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        h2 {
            color: #4CAF50;
            font-size: 2rem;
            margin-top: 2rem;
            margin-bottom: 1rem;
        }
        p {
            font-size: 1.1rem;
            line-height: 1.6;
            margin-bottom: 1.5rem;
            text-align: left;
        }
        .formula {
            font-size: 1.5rem;
            font-weight: bold;
            color: #4CAF50;
            margin: 1.5rem 0;
        }
        .example, .problem {
            background-color: #e8f5e9;
            padding: 1rem;
            border-radius: 5px;
            margin: 1.5rem 0;
            text-align: left;
        }
        .problem h3 {
            margin-top: 0;
            color: #4CAF50;
        }
        .input-group {
            margin: 1rem 0;
            text-align: left;
        }
        .input-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: bold;
        }
        .input-group input {
            padding: 0.5rem;
            border: 1px solid #ccc;
            border-radius: 5px;
            width: 100%;
            max-width: 200px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 0.75rem 1.5rem;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
            margin-top: 1rem;
        }
        button:hover {
            background-color: #45a049;
        }
        .result {
            margin-top: 1.5rem;
            font-size: 1.2rem;
            font-weight: bold;
            color: #4CAF50;
        }
        .links {
            margin-top: 1.5rem;
        }
        .links a {
            color: #4CAF50;
            text-decoration: none;
            margin: 0 0.5rem;
        }
        .links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>ทฤษฎีบทพีทาโกรัส</h1>
        <p>
            **ทฤษฎีบทพีทาโกรัส** เป็นทฤษฎีพื้นฐานในเรขาคณิตที่อธิบายความสัมพันธ์ระหว่างด้านทั้งสามของสามเหลี่ยมมุมฉาก 
        </p>
        <div class="formula">
            c² = a² + b²
        </div>
        <p>
            โดยที่:
            <ul>
                <li><strong>c</strong> = ความยาวของด้านตรงข้ามมุมฉาก</li>
                <li><strong>a</strong> และ <strong>b</strong> = ความยาวของด้านประกอบมุมฉาก</li>
            </ul>
        </p>

        <h2>ประวัติของพีทาโกรัส</h2>
        <p>
            พีทาโกรัสเป็นนักคณิตศาสตร์และนักปรัชญาชาวกรีกโบราณ เกิดประมาณ 570 ปีก่อนคริสตกาล ทฤษฎีบทพีทาโกรัสเป็นหนึ่งในผลงานที่มีชื่อเสียงที่สุดของเขา 
            ทฤษฎีนี้ไม่เพียงแต่ใช้ในเรขาคณิต แต่ยังเป็นพื้นฐานสำคัญในสาขาต่าง ๆ เช่น ฟิสิกส์ วิศวกรรม และดาราศาสตร์
        </p>

        <h2>วิธีคำนวณ</h2>
        <p>
            การคำนวณด้านของสามเหลี่ยมมุมฉากโดยใช้ทฤษฎีบทพีทาโกรัสมีขั้นตอนดังนี้:
            <ol>
                <li>ระบุด้านที่ต้องการหาค่า (ด้านตรงข้ามมุมฉากหรือด้านประกอบมุมฉาก)</li>
                <li>แทนค่าด้านที่ทราบลงในสูตร c² = a² + b²</li>
                <li>แก้สมการเพื่อหาค่าด้านที่ต้องการ</li>
            </ol>
        </p>

        <div class="example">
            <p><strong>ตัวอย่าง:</strong></p>
            <p>
                สมมติว่าสามเหลี่ยมมุมฉากมีด้านประกอบมุมฉากยาว 3 และ 4 หน่วย  ด้านตรงข้ามมุมฉากจะยาว:
                <br>
                c² = 3² + 4² = 9 + 16 = 25
                <br>
                c = √25 = 5 หน่วย
            </p>
        </div>

        <h2>โจทย์ปัญหา</h2>
        <div class="problem">
            <h3>โจทย์ที่ 1</h3>
            <p>
                สามเหลี่ยมมุมฉากมีด้านประกอบมุมฉากยาว 6 และ 8 หน่วย จงหาความยาวของด้านตรงข้ามมุมฉาก
            </p>
            <div class="input-group">
                <label for="a1">ด้าน a:</label>
                <input type="number" id="a1" placeholder="ป้อนความยาวด้าน a" value="6" readonly>
            </div>
            <div class="input-group">
                <label for="b1">ด้าน b:</label>
                <input type="number" id="b1" placeholder="ป้อนความยาวด้าน b" value="8" readonly>
            </div>
            <button onclick="solveProblem(1)">คำนวณ</button>
            <div class="result" id="result1"></div>
        </div>

        <div class="problem">
            <h3>โจทย์ที่ 2</h3>
            <p>
                สามเหลี่ยมมุมฉากมีด้านตรงข้ามมุมฉากยาว 19 หน่วย และด้านประกอบมุมฉากยาว95 หน่วย จงหาความยาวของด้านประกอบมุมฉากอีกด้าน
            </p>
            <div class="input-group">
                <label for="a2">ด้าน a:</label>
                <input type="number" id="a2" placeholder="ป้อนความยาวด้าน a" value="95" readonly>
            </div>
            <div class="input-group">
                <label for="c2">ด้าน c:</label>
                <input type="number" id="c2" placeholder="ป้อนความยาวด้าน c" value="19" readonly>
            </div>
            <button onclick="solveProblem(2)">คำนวณ</button>
            <div class="result" id="result2"></div>
        </div>

        <div class="links">
            <p><strong>เพิ่มเติม:</strong></p>
            <a href="https://th.wikipedia.org/wiki/%E0%B8%97%E0%B8%A4%E0%B8%A9%E0%B8%8E%E0%B8%B5%E0%B8%9A%E0%B8%97%E0%B8%9E%E0%B8%B5%E0%B8%97%E0%B8%B2%E0%B9%82%E0%B8%81%E0%B8%A3%E0%B8%B1%E0%B8%AA" target="_blank">วิกิพีเดีย</a>
            <a href="https://www.khanacademy.org/math/geometry/hs-geo-trig/hs-geo-pythagorean-theorem/a/pythagorean-theorem-review" target="_blank">Khan Academy</a>
        </div>
    </div>
    <div> สร้างโดยด.ช.ทัศนัย ทองโยงม.2/6เลขที่32
    <p>ผู้ช่วย Chat gptและDepkseek</p></div>



    <script>
        function solveProblem(problemNumber) {
            if (problemNumber === 1) {
                let a = 6;
                let b = 8;
                let c = Math.sqrt(a * a + b * b);
                alert("ด้านตรงข้ามมุมฉาก (c) มีค่าประมาณ: " + c.toFixed(2) + " หน่วย");
            } else if (problemNumber === 2) {
                let a = 19;
                let c = 95;
                let b = Math.sqrt(c * c - a * a);
                alert("ด้านประกอบมุมฉากอีกด้าน (b) มีค่าประมาณ: " + b.toFixed(2) + " หน่วย");
            }
        }
    </script>
</body>
</html>There was an error committing your changes: A file with the same name already exists. Please choose a different name and try again.
