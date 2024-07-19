<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giới thiệu bản thân</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Giới thiệu bản thân</h1>
        <div id="personal-info">
            <h2>Tên: <span id="name"></span></h2>
            <h2>Trạng thái hiện tại: <span id="status"></span></h2>
            <h2>Đam mê: <span id="passion"></span></h2>
        </div>
        <h2>Những bài LeetCode đã làm được:</h2>
        <ul id="leetcode-list"></ul>
        <h2>Dự án đang thực hiện:</h2>
        <ul id="current-projects"></ul>
        <h2>Dự án đã hoàn thành:</h2>
        <ul id="completed-projects"></ul>
        <h2>Thống kê GitHub Streak:</h2>
        <div id="github-stats">
            <img src="http://github-readme-streak-stats.herokuapp.com?user=your-github-username&theme=dark&background=000000" alt="GitHub Streak Stats">
            <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hocj2me" /> <img align="center" src="https://github-readme-stats.vercel.app/api?username=hocj2me&show_icons=true" />
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
