<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[您的姓名] - 学术主页</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
        }
        header {
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 1px solid #eee;
            padding-bottom: 20px;
        }
        h1 {
            margin-bottom: 5px;
            color: #2c3e50;
        }
        .position {
            font-style: italic;
            color: #7f8c8d;
        }
        .contact {
            margin-top: 10px;
        }
        section {
            margin-bottom: 30px;
        }
        h2 {
            border-bottom: 1px solid #eee;
            padding-bottom: 5px;
            color: #2c3e50;
        }
        .pub-item {
            margin-bottom: 15px;
        }
        .pub-title {
            font-weight: bold;
        }
        .pub-authors {
            font-style: italic;
        }
        .pub-venue {
            color: #2980b9;
        }
        a {
            color: #2980b9;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 15px;
            border: 3px solid #eee;
        }
    </style>
</head>
<body>
    <header>
        <img src="[您的照片路径]" alt="[您的姓名]" class="profile-img">
        <h1>[您的姓名]</h1>
        <div class="position">[您的职称/职位]</div>
        <div class="position">[您的机构/大学名称]</div>
        <div class="contact">
            邮箱: <a href="mailto:您的邮箱">您的邮箱</a> | 
            个人简历: <a href="[CV链接]">PDF</a> | 
            Google Scholar: <a href="[Google Scholar链接]">链接</a>
        </div>
    </header>

    <section id="about">
        <h2>关于我</h2>
        <p>[在这里简要介绍您的研究兴趣、背景和专业方向。可以包括您的教育背景、当前研究重点等。]</p>
    </section>

    <section id="research">
        <h2>研究方向</h2>
        <ul>
            <li>[研究方向1]</li>
            <li>[研究方向2]</li>
            <li>[研究方向3]</li>
        </ul>
    </section>

    <section id="publications">
        <h2>代表性论文</h2>
        <div class="pub-item">
            <div class="pub-title">[论文标题]</div>
            <div class="pub-authors">[作者列表]</div>
            <div class="pub-venue">[期刊/会议名称], [年份]</div>
            <div>[<a href="[PDF链接]">PDF</a>] [<a href="[代码链接]">代码</a>] [<a href="[项目页面]">项目页面</a>]</div>
        </div>
        <!-- 重复以上pub-item结构添加更多论文 -->
    </section>

    <section id="education">
        <h2>教育背景</h2>
        <ul>
            <li>[学位], [专业], [学校名称], [年份]</li>
            <li>[学位], [专业], [学校名称], [年份]</li>
        </ul>
    </section>

    <section id="teaching">
        <h2>教学工作</h2>
        <ul>
            <li>[课程名称], [学期], [角色]</li>
            <li>[课程名称], [学期], [角色]</li>
        </ul>
    </section>

    <section id="awards">
        <h2>荣誉与奖项</h2>
        <ul>
            <li>[奖项名称], [颁发机构], [年份]</li>
            <li>[奖项名称], [颁发机构], [年份]</li>
        </ul>
    </section>

    <footer>
        <p>© [年份] [您的姓名]. 最后更新: [日期]</p>
    </footer>
</body>
</html>
