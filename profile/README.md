## YOLOv5を利用した駐輪場管理システム  
物体検出アルゴリズム[YOLOv5](https://github.com/ultralytics/yolov5)を用いて駐輪場の業務支援を行うことを目的としたWebシステム。  
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
### 管理者用サーバー：[admin-server](https://github.com/projectd-team14/admin-server)  
・バックエンド：Laravel(PHP)  
・インフラ：Amozon EC2  
・その他:Docker  
### 設計資料等：[design](https://github.com/projectd-team14/design)  
・DB設計（テーブル定義、ER図）  
・フローチャート（簡易版）  
・画面設計、イメージ等
![インフラ構成](https://user-images.githubusercontent.com/71867595/210197275-1b7fc511-de77-4708-8176-65a20f5f08bd.png)
