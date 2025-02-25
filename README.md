# hopital-website
MedBookingBTL
/* Reset CSS */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

/* Header */
header {
    background: #007bff;
    color: white;
    padding: 20px;
    text-align: center;
    font-size: 24px;
    font-weight: bold;
}

/* Navigation */
nav {
    display: flex;
    justify-content: center;
    background: #0056b3;
    padding: 10px;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 10px 20px;
    font-size: 18px;
}

nav a:hover {
    background: #003d82;
    border-radius: 5px;
}

/* Container */
.container {
    width: 80%;
    margin: 20px auto;
    padding: 20px;
    background: white;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

/* Section */
.section {
    margin-bottom: 20px;
}

.section h2 {
    color: #007bff;
    margin-bottom: 10px;
}

/* Button */
.btn {
    display: inline-block;
    background: #007bff;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s;
}

.btn:hover {
    background: #0056b3;
}

/* Footer */
footer {
    text-align: center;
    background: #007bff;
    color: white;
    padding: 10px;
    margin-top: 20px;
}

<!DOCTYPE html>
<html>
<head lang="vn">
<meta charset="UTF-8">
<meta name="viewpoint" content="width-device-width , initial-scale=1.0">
<title>MebBookingBTL - Đặt lịch khám bệnh </title> <!--tieu de hien thi tren tab trinh duyet -->
<meta name="description" content="Đặt lịch khám online nhanh chóng tại các bệnh viện gần bạn. Tích hợp Google Maps, cung cấp thông tin bệnh viện chi tiết: chuyên khoa, bác sĩ, giờ làm việc.">
<meta name="keywords" content="bênh viện,đặt lịch ,tra cứu thông tin bệnh viện, bác sĩ , Bắc Từ Liêm">
<!-- Favicon (icon nhỏ trên tab trình duyệt -->
<link rel="icon" href="image/x-icon">
<link rel="stylesheet" href="main.css">
<img src="https://scontent.fhan14-2.fna.fbcdn.net/v/t1.15752-9/481331187_1018467373436689_7000248724772191540_n.jpg?stp=dst-jpg_s640x640_tt6&_nc_cat=100&ccb=1-7&_nc_sid=0024fc&_nc_eui2=AeEjYM2Q2m-8zL4srMNhAUtlEcNTY1FkGNkRw1NjUWQY2TQIg13_lGZjlDQMDcHJXAe8yFIKkGW1mW_Chj-BVT2T&_nc_ohc=xMX38QoiUhEQ7kNvgEUoUK_&_nc_oc=Adhcn7mhvmgdH2gQY66hknjCN_xhg3kv5ZMXZvMY9n15-BrUuHLQBzRbS_6O_wpeWzE&_nc_zt=23&_nc_ht=scontent.fhan14-2.fna&oh=03_Q7cD1gEiDSc3x13jweSWkWKDAO_-KYevXqWaE5mcvvjS1jbYRQ&oe=67E22326 " width="1520px"  height="512px" >
</p>
<style>
    .grid-container{
        display :grid;
        grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr ;
        background-color: rgb(202, 224, 247) ;
        padding: 10px;
    gap: 10px;
    }
    .gird-container > div {
      background-color: #f1f1f1;
      color: #f6f1f1;
      padding: 10px ;
      font-size: 30px;
      text-align: center;
    }
   
</style>
</head>
<body>
 <h2><b>TRUNG TÂM ĐẶT LỊCH KHÁM TẠI BTL</b></h2>
 <div class="grid-container">
    <div><b>TRANG CHỦ</b></div>
    <div><b>GIỚI THIỆU</b></div>
    <div><b>TÌM KIẾM BỆNH VIỆN</b></div>
    <div><b>HUỚNG DẪN KHÁCH HÀNG</b></div>
    <div><b>THÔNG TIN BỆNH VIỆN </b></div>
    <div><b> DỊCH VỤ Y TẾ </b></div>
 </div>
 </div>
 <p> BENH VIEN DA KHOA TRUNG UONG QUANH KHU VUC BAC TU LIEM</p>
</body>
</html>

