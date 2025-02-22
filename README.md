项目框架：

book_notes/                  # 根目录
├── __init__.py              # 使book_notes成为一个包
├── notes.py                 # Flask 主应用文件，包含路由和应用逻辑
├── data/                    # 存储笔记数据的文件夹
│   └── notes_db.json        # 存储笔记数据的 JSON 文件
├── templates/               # 存放 HTML 模板文件的文件夹
│   ├── home_page.html       # 首页模板
│   ├── index.html           # 笔记列表页模板
│   ├── create_note.html     # 添加笔记页面模板
│   └── note_detail.html     # 笔记详情页面模板
├── static/                  # 存放静态文件（如 CSS、JS、图片等）的文件夹
│   ├── css/
│   │   ├── notes.css        # 笔记列表页样式
│   │   ├── create_note.css  # 添加笔记页面样式
│   │   └── note_index.css   # 新增的笔记首页样式
│   ├── js/
│   └── img/
│       └── note.jpg         # 示例图片
├── .venv/                   # 虚拟环境目录
├── Procfile                 # Heroku 部署配置文件
├── requirements.txt         # 项目依赖文件
├── start.sh                 # 启动脚本（用于部署时启动应用）暂不添加
├── README.md                # 项目说明文件
