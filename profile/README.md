## YOLOv5を利用した駐輪場管理システム  
このプロジェクトは物体検出アルゴリズム[YOLOv5](https://github.com/ultralytics/yolov5)を用いて駐輪場の業務支援を行うことを目的としたWebシステムである。  
## システム構成・使用技術  
### システム基盤：[bicycle-system](https://github.com/projectd-team14/bicycle_system)    
・フロントエンド：Nuxt.js(Vue.js, Node.js, TypeScript, Sass)  
・バックエンド：Laravel(PHP)  
・データベース：MySQL  
・インフラ：Amozon EC2, Amozon RDS, Amozon S3, AWS Lambda, EventBrige  
・その他:Docker
### YOLOv5専用サーバー：[yolov5-server](https://github.com/projectd-team14/yolov5-server)  
・バックエンド：FastAPI(Python)  
・物体検出アルゴリズム：YOLOv5(Python)  
・インフラ：Amozon EC2  
・その他:Docker  
![インフラ構成（図）](https://user-images.githubusercontent.com/71867595/200099190-e0a21fad-bfaf-481d-b8e7-183f1678bbee.png)  
