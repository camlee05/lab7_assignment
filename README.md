<div class="content">
    <h1>BÁO CÁO KIỂM THỬ API</h1>
    <ol>
        <p><strong>Tên Dự Án:</strong> Test Collection of APIs</p>
        <p><strong>Ngày Kiểm Thử:</strong> 07/10/2026</p>
        <p><strong>Người Kiểm Thử:</strong> Lê Thị Cẩm Ly</p>
        <p><strong>1. Mục Tiêu Kiểm Thử:</strong> Sử dụng Postman để kiểm thử một API thực tế</p>
        <p><strong>2. Môi Trường Kiểm Thử:</strong> Postman.</p>
        <p><strong>3. Phương Pháp Kiểm Thử:</strong> Kiểm thử tự động và thủ công trên phần mềm Postman.</p>
        4.
         <strong>Kịch Bản Kiểm Thử Lần 1:</strong>
            <ul>
            <li><p>Tên Kịch Bản: Kiểm thử cơ bản của 1 URL</p></li>
            <li><p>Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman</p></li>
            <li><p>Phương Thức HTTP (GET/POST/PUT/DELETE): GET</p></li>
            <li><p>URL: http://127.0.0.1:8000/api/v1/admin/users</p></li>
            <li><p>Tham Số: users?size=2&is_xml=true</p></li>
            <li><p>Kết Quả Mong Đợi: Gửi yêu cầu thành công</p></li>
            <li><p>Kết Quả Thực Tế: Đã gửi yêu cầu thành công</p></li>
            <li><p>Trạng Thái: Thành công</p></li>
            <li><p>Kết quả sau khi kiểm thử:</p></li>
            <img width="1470" height="956" alt="Ảnh màn hình 2026-10-07 lúc 10 48 15" src="https://github.com/user-attachments/assets/ea668919-2154-447d-bd6a-91f1daef9bdf" />
            <li><p>Kết quả kiểm thử chi tiết:</p></li>
            </ul>
    
[{"id":7,"username":"camlee05","contact_info":"0123456789","hwid":"4c0cdd6a2b3545c75decb6decca1d89a5acb4db1bd272de4243befcca24958c1","role":"user","status":"pending","expired_at":null,"created_at":"2026-10-06T02:15:02.443149Z","days_remaining":null,"last_login_at":null,"last_login_ip":null,"is_online":false,"last_active_at":null,"last_hwid_reset_at":null},{"id":6,"username":"camlee04","contact_info":"0123456789","hwid":"4c0cdd6a2b3545c75decb6decca1d89a5acb4db1bd272de4243befcca24958c1","role":"user","status":"pending","expired_at":null,"created_at":"2026-10-06T02:06:46.798700Z","days_remaining":null,"last_login_at":null,"last_login_ip":null,"is_online":false,"last_active_at":null,"last_hwid_reset_at":null},{"id":5,"username":"camlee03","contact_info":"0123456789","hwid":"4c0cdd6a2b3545c75decb6decca1d89a5acb4db1bd272de4243befcca24958c1","role":"user","status":"pending","expired_at":null,"created_at":"2026-10-05T08:52:43.437938Z","days_remaining":null,"last_login_at":null,"last_login_ip":null,"is_online":false,"last_active_at":null,"last_hwid_reset_at":null},{"id":4,"username":"camlee02","contact_info":"0123456789","hwid":"4c0cdd6a2b3545c75decb6decca1d89a5acb4db1bd272de4243befcca24958c1","role":"user","status":"rejected","expired_at":null,"created_at":"2026-10-05T07:17:45.500287Z","days_remaining":null,"last_login_at":null,"last_login_ip":null,"is_online":false,"last_active_at":null,"last_hwid_reset_at":null},{"id":3,"username":"camlee01","contact_info":"0123456789","hwid":"4c0cdd6a2b3545c75decb6decca1d89a5acb4db1bd272de4243befcca24958c1","role":"user","status":"expired","expired_at":"2026-09-05T07:16:23.273607Z","created_at":"2026-10-05T07:16:07.690262Z","days_remaining":0,"last_login_at":"2026-10-05T07:16:43.032656Z","last_login_ip":"127.0.0.1","is_online":false,"last_active_at":"2026-10-05T07:17:19.384539Z","last_hwid_reset_at":null},{"id":2,"username":"camlee","contact_info":"0123456789","hwid":"4c0cdd6a2b3545c75decb6decca1d89a5acb4db1bd272de4243befcca24958c1","role":"user","status":"approved","expired_at":"2026-11-01T01:43:08.407009Z","created_at":"2026-10-02T01:41:12.139671Z","days_remaining":25,"last_login_at":"2026-10-05T13:35:57.652199Z","last_login_ip":"127.0.0.1","is_online":false,"last_active_at":"2026-10-05T13:35:57.652199Z","last_hwid_reset_at":null}]
<div>    
    <strong>Kịch Bản Kiểm Thử Lần 2:</strong>
            <ul>
            <li><p>Tên Kịch Bản: Kiểm thử cơ bản của một URL với một tham số</p></li>
            <li><p>Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman</p></li>
            <li><p>Phương Thức HTTP (GET/POST/PUT/DELETE): GET</p></li>
            <li><p>URL: https://random-data-api.com/api/v2/</p></li>
            <li><p>Tham Số: beerType=light</p></li>
            <li><p>Kết Quả Mong Đợi: Gửi yêu cầu thành công</p></li>
            <li><p>Kết Quả Thực Tế: Gửi yêu cầu thất bại</p></li>
            <li><p>Trạng Thái: Không thành công</p></li>
            <li><p>Kết quả sau khi kiểm thử:</p></li>
            <img width="468" alt="image" src="https://github.com/gtaAsian/New-Collection-of-APIs/assets/170786444/47657a68-c2ce-4826-80db-863977b71169">
            <li><p>Kết quả kiểm thử chi tiết:</p></li>
            </ul>


    <!DOCTYPE html>
    <html>
    
    <head>
    
        <title>The page you were looking for doesn't exist (404)</title>
        <meta name="viewport" content="width=device-width,initial-scale=1">
        <style>
            .rails-default-error-page {
                background-color: #EFEFEF;
                color: #2E2F30;
                text-align: center;
                font-family: arial, sans-serif;
                margin: 0;
            }
            
            .rails-default-error-page div.dialog {
                width: 95%;
                max-width: 33em;
                margin: 4em auto 0;
            }
    
            .rails-default-error-page div.dialog>div {
                border: 1px solid #CCC;
                border-right-color: #999;
                border-left-color: #999;
                border-bottom-color: #BBB;
                border-top: #B00100 solid 4px;
                border-top-left-radius: 9px;
                border-top-right-radius: 9px;
                background-color: white;
                padding: 7px 12% 0;
                box-shadow: 0 3px 8px rgba(50, 50, 50, 0.17);
            }
    
            .rails-default-error-page h1 {
                font-size: 100%;
                color: #730E15;
                line-height: 1.5em;
            }
    
            .rails-default-error-page div.dialog>p {
                margin: 0 0 1em;
                padding: 1em;
                background-color: #F7F7F7;
                border: 1px solid #CCC;
                border-right-color: #999;
                border-left-color: #999;
                border-bottom-color: #999;
                border-bottom-left-radius: 4px;
                border-bottom-right-radius: 4px;
                border-top-color: #DADADA;
                color: #666;
                box-shadow: 0 3px 8px rgba(50, 50, 50, 0.17);
            }
        </style>
    </head>
    <body class="rails-default-error-page">
        <!-- This file lives in public/404.html -->
        <div class="dialog">
            <div>
                <h1>The page you were looking for doesn't exist.</h1>
                <p>You may have mistyped the address or the page may have moved.</p>
            </div>
            <p>If you are the application owner check the logs for more information.</p>
        </div>
    </body>

    </html>
<div>
    <strong>Kịch Bản Kiểm Thử Lần 1:</strong>
            <ul>
            <li><p>Tên Kịch Bản: Kiểm thử cơ bản của 1 URL với một tham số truyền vào</p></li>
            <li><p>Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman</p></li>
            <li><p>Phương Thức HTTP (GET/POST/PUT/DELETE): GET</p></li>
            <li><p>URL: https://random-data-api.com/api/v2/</p></li>
            <li><p>Tham Số: beerType=light</p></li>
            <li><p>Kết Quả Mong Đợi: Gửi yêu cầu thành công</p></li>
            <li><p>Kết Quả Thực Tế: Đã gửi yêu cầu thành công</p></li>
            <li><p>Trạng Thái: Thành công</p></li>
            <li><p>Kết quả sau khi kiểm thử:</p></li>
            <img width="468" alt="image" src="https://github.com/gtaAsian/New-Collection-of-APIs/assets/170786444/4704b95c-115c-4e24-aa8a-2aeee5339fba">
            <li><p>Kết quả kiểm thử chi tiết:</p></li>
            </ul>
</div>

        {
            "id": 4908,
            "uid": "16d508f9-8757-491d-b8c9-4b980932f637",
            "brand": "Leffe",
            "name": "Sapporo Premium",
            "style": "Strong Ale",
            "hop": "Newport",
            "yeast": "1098 - British Ale",
            "malts": "Roasted barley",
            "ibu": "82 IBU",
            "alcohol": "2.1%",
            "blg": "12.8°Blg"
        }
        
<p><strong>5. Kết Quả Kiểm Thử:</strong> Tóm tắt kết quả kiểm thử, bao gồm số lượng kịch bản kiểm thử đã chạy, số lượng thành công, số lượng thất bại, và tỷ lệ thành công.</p>
<ul>
<li><p>Số lượng kịch bản đã kiểm thử: 3</p></li>
<li><p>Số lần thành công: 2</p></li>
<li><p>Số lần thất bại: 1</p></li>
<li><p>Tỉ lệ thành công: 75%</p></li>
</ul>
<p><strong>6. Phát Hiện Lỗi:</strong>  Chi tiết về lỗi, bao gồm:</p>
<ul>
<li><p>ID Lỗi: 404 Not Found</p></li>
<li><p>Mô Tả Lỗi: Trang bạn đang tìm kiếm không tồn tại (404)</p></li>
<li><p>Mức Độ Ảnh Hưởng: Không</p></li>
<li><p>Ghi Chú/Đề Xuất: Sai URL và tham số</p></li>
</ul>
