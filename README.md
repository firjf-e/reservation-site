<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>예약 시스템</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>예약 시스템</h1>
    </header>

    <section>
        <h2>예약하기</h2>
        <form id="reservation-form">
            <label for="name">이름:</label>
            <input type="text" id="name" name="name" required><br><br>

            <label for="date">예약 날짜:</label>
            <input type="date" id="date" name="date" required><br><br>

            <label for="time">예약 시간:</label>
            <input type="time" id="time" name="time" required><br><br>

            <button type="submit">예약하기</button>
        </form>
        <p id="message"></p>
    </section>

    <script src="script.js"></script>
</body>
</html>
