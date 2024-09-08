# hutong17.github.io
- 👋 Hi, I’m 徐静雯.I come from school of Computer Science and Technology.
- 👀 I’m interested in listening music and leaning new things to improve myself,although my technology is poor right now.
- 🌱 I’m currently learning how to make my own blog and i will always try to do better.
- 👀 HOPE YOU COULD GIVE ME A OPPORTUNITY!

<!---
hutong17/hutong17 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <title>Present</title>
    <meta name="keywords" content=""/>
    <meta name="description" content=""/>
    <meta name="renderer" content="webkit">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <link rel="stylesheet" href="static/css/loading.css">
</head>
<body class="locked">
    <div class="self-avatar flex-center">
        <div class="loading-mask fixed-layer no-delay"></div>
        <div class="loading-wrapper">
            <svg class="loading-indicator no-delay" width="128" height="128">
                <g class="circle-rotating">
                    <g class="circle-step">
                        <circle cx="64" cy="64" r="56" class="circle-line"></circle>
                    </g>
                </g>
            </svg>
            <img alt="" src="static/img/avatar.jpg" class="avatar-img no-delay"/>
        </div>
        <div class="loading-text text-center">
            <p class="loading-pre">Loading...</p>
            <p class="avatar-name">Present</p>
            <p class="dokidoki-text"></p>
        </div>
    </div>
    <div class="background-layer fixed-layer"></div>
    <div class="background-filter fixed-layer"></div>
    <div class="content-layer flex-center">
        <div class="content-container">
            <div class="self-wrapper">
                <div class="self-content links-container flex-center text-center">
                    <a href="#" class="link-item">
                        <div class="link-icon"><i class="fa fa-home"></i></div>
                        <div>博客</div>
                    </a>
                    <a href="#" class="link-item">
                        <div class="link-icon"><i class="fa fa-play-circle"></i></div>
                        <div>Bilibili</div>
                    </a>
                    <a href="#" class="link-item">
                        <div class="link-icon"><i class="fa fa-qq"></i></div>
                        <div>QQ</div>
                    </a>
                    <a href="#" class="link-item">
                        <div class="link-icon"><i class="fa fa-telegram"></i></div>
                        <div>Telegram</div>
                    </a>
                    <a href="#" class="link-item">
                        <div class="link-icon"><i class="fa fa-steam"></i></div>
                        <div>Steam</div>
                    </a>
                    <a href="#" class="link-item">
                        <div class="link-icon"><i class="fa fa-github"></i></div>
                        <div>Github</div>
                    </a>
                </div>
                <div class="self-content article-container">
                    <div class="article-content"></div>
                    <div class="article-loading flex-center">
                        <svg style="visibility: hidden" class="loading-indicator" width="128" height="128">
                            <g class="circle-rotating">
                                <g class="circle-step">
                                    <circle cx="64" cy="64" r="56" class="circle-line"></circle>
                                </g>
                            </g>
                        </svg>
                        <span class="text-center">Loading...</span>
                    </div>
                </div>
                <div class="self-content">
                    <div class="info-container">
                        This is a simple homepage theme by XuHutong.
                    </div>

                </div>
            </div>
            <div class="self-switcher">
                <div class="switcher-btn text-center" id="switcher-btn-1">
                    <div class="btn-icon"><i class="fa fa-link"></i></div>
                    <div class="btn-text">链接</div>
                </div>
                <div class="switcher-btn text-center" id="switcher-btn-2">
                    <div class="btn-icon"><i class="fa fa-book"></i></div>
                    <div class="btn-text">文章</div>
                </div>
                <div class="switcher-btn text-center" id="switcher-btn-3">
                    <div class="btn-icon"><i class="fa fa-info-circle"></i></div>
                    <div class="btn-text">关于</div>
                </div>
                <div class="btn-select-indicator"></div>
            </div>
        </div>
    </div>
    <div class="footer-container text-center">© 2024 By <a href="#">Present</a></div>
</body>

<link rel="stylesheet" href="static/css/main.css">
<link rel="stylesheet" href="https://fastly.jsdelivr.net/gh/ClassicOldSong/typinyin.js@0.1.3/typinyin.css">
<link href="https://cdn.bootcss.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" type="text/css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Google+Sans" media="none" onload="this.media='all'">
<script src="https://fastly.jsdelivr.net/gh/ClassicOldSong/typinyin.js@master/typinyin.min.js"></script>
<script src="static/js/main.js"></script>
<script>
    (function () {
        var feedType = "json";
        var feedPath = "feed.php";
        var bgArr = [{
            "url": "static/img/background-1.jpg",
            "thumb": "static/img/background-1-thumb.jpg"
        }, {
            "url": "static/img/background-2.jpg",
            "thumb": "static/img/background-2-thumb.jpg"
        }];
        var senArr = [
            {
                ch: ["This is an example."],
                py: ["This is an example."],
            }, {
                ch: ["这是", "一个", "示例", "."],
                py: ["zhe'shi", "yi'ge", "shi'li", "."],
            }
        ];

        Init(feedType, feedPath, bgArr, senArr);
    })();
</script>
<style>

</style>
</html>
