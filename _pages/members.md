---
layout: archive
title: ""
permalink: /members/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Members</title>
    <style>
        .members-container {
            font-family: Arial, sans-serif;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f7;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .members-container h1 {
            color: #0d3b83;
            text-align: center;
            margin-bottom: 20px;
        }
        .members-container h1:after {
            content: "";
            display: block;
            width: 50px;
            height: 3px;
            background-color: #0d3b83;
            margin: 10px auto;
        }
        .members-container .intro {
            max-width: 800px;
            margin: 0 auto 40px;
            color: #333;
            line-height: 1.6;
            text-align: center;
        }
        .members-container .members-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px; 
            margin-top: 30px;
        }
        .members-container .member-card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .members-container .member-card:hover {
            transform: translateY(-5px) scale(1.02);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }
        .members-container .member-image {
            width: 100%;
            height: 300px; 
            object-fit: cover;
        }
        .members-container .member-info {
            padding: 20px; 
        }
        .members-container .member-name {
            color: #0d3b83;
            margin: 0 0 10px; 
            font-size: 18px;
        }
        .members-container .member-title {
            color: #555;
            margin: 0;
            font-size: 16px; 
        }
        .members-container .recommendation {
            color: #e63946;
            font-size: 16px;
            margin-top: 15px; 
        }
    </style>
</head>
<body>
    <div class="members-container">
        <h1>Members</h1>
        <p class="intro">I am very fortunate to work with many amazing students and researchers. We welcome talented folks with a pharmacy, economics, or epidemiology background to join us. Also, feel free to contact me if you are interested to learn more about our research!
        </p>
        <div class="members-grid">
            <div class="member-card">
                <img src="../images/members/Zhaohui Bai.jpeg" alt="Zhaohui Bai" class="member-image">
                <div class="member-info">
                    <h3 class="member-name">Zhaohui Bai</h3>
                    <p class="member-title">Postdoc</p>
                </div>
            </div>
            <div class="member-card">
                <img src="../images/members/Tao Huang.png" alt="Tao Huang" class="member-image">
                <div class="member-info">
                    <h3 class="member-name">Tao Huang</h3>
                    <p class="member-title">PhD Candidate</p>
                </div>
            </div>
            <div class="member-card">
                <img src="..\images\members\Dongze Ji.jpeg" alt="Dongze Ji" class="member-image">
                <div class="member-info">
                    <h3 class="member-name">Dongze Ji</h3>
                    <p class="member-title">PhD Candidate</p>
                </div>
            </div>
            <div class="member-card">
                <img src="..\images\members\Ruowei Xiao.jpeg" alt="Ruowei Xiao" class="member-image">
                <div class="member-info">
                    <h3 class="member-name">Ruowei Xiao</h3>
                    <p class="member-title">PhD Candidate</p>
                </div>
            </div>
            <div class="member-card">
                <img src="..\images\members\Yongjie Lai.jpeg" alt="Yongjie Lai" class="member-image">
                <div class="member-info">
                    <h3 class="member-name">Yongjie Lai</h3>
                    <p class="member-title">Master Student</p>
                </div>
            </div>
            <div class="member-card">
                <img src="..\images\members\Yue Zhang.jpeg" alt="Yue Zhang" class="member-image">
                <div class="member-info">
                    <h3 class="member-name">Yue Zhang</h3>
                    <p class="member-title">Master Student</p>
                </div>
            </div>
            <div class="member-card">
                <img src="..\images\members\Kunchi Xie.jpg" alt="Kunchi Xie" class="member-image">
                <div class="member-info">
                    <h3 class="member-name">Kunchi Xie</h3>
                    <p class="member-title">Master Student</p>
                </div>
            </div>
            <div class="member-card">
                <img src="..\images\members\Xiaoyu Wu.jpg" alt="Xiaoyu Wu" class="member-image">
                <div class="member-info">
                    <h3 class="member-name">Xiaoyu Wu</h3>
                    <p class="member-title">Master Student</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>