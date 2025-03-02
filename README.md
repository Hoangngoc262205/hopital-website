# hopital-website
MedBookingBTL

<!DOCTYPE html>
<html>
<head lang="vn">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no, viewport-fit=cover, shrink-to-fit=no" />
<title>MebBookingBTL - Đặt lịch khám bệnh </title> <!--tieu de hien thi tren tab trinh duyet -->
<meta name="description" content="Đặt lịch khám online nhanh chóng tại các bệnh viện gần bạn. Tích hợp Google Maps, cung cấp thông tin bệnh viện chi tiết: chuyên khoa, bác sĩ, giờ làm việc.">
<meta name="keywords" content="bênh viện,đặt lịch ,tra cứu thông tin bệnh viện, bác sĩ , Bắc Từ Liêm">
<!-- Favicon (icon nhỏ trên tab trình duyệt -->
<link rel="icon" href="image/x-icon">
<link rel="stylesheet" href="main.css">
<img src="https://scontent.fhan14-5.fna.fbcdn.net/v/t1.15752-9/481280470_1791921428255884_5777087804141641067_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=9f807c&_nc_eui2=AeGt4GRz9dlYORj5DywET7PPy8i6GAK2YzvLyLoYArZjO7w5em3MeP_SGsB4DBAo1CeVyf_CSSWup7MiVALogDE5&_nc_ohc=BkOI6DeVZGwQ7kNvgGNxw2F&_nc_oc=Adj85pVcNFmwvl1t9RFvykWB8eTRPHeXbO7_8MvJm19z2E3vPqx9n9BLfKEdk06Wko8&_nc_zt=23&_nc_ht=scontent.fhan14-5.fna&oh=03_Q7cD1gFYPdhm2kPq_AFPLX9f56nVdWHW82k1msrD_oti4ATOoA&oe=67E62AF0" style ="width: 100%; height: auto; display: block;" >
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

  <!-- Header -->
  <header>
      MedBookingBTL - HỆ THỐNG ĐẶT LỊCH KHÁM BỆNH VIỆN
  </header>

  <!-- Navigation -->
  <nav>
    <ul class ="nav-links"><a href="changchu.html" target="_parent"> <b>TRANG CHỦ</b></a>
        <div class="dropdown">
            <span><a href="#"><b> GIỚI THIỆU </b></a></span>
            <div class="dropdown-content">
                <ul class="dropdown">
                    <li><a href="#"><b>LỊCH SỬ HÌNH THÀNH </b></a></li>
                    <li><a href="#"><b>CHUYÊN KHOA Y TẾ </b></a></li>
                     <li><a href="#"><b>CƠ SỞ VẬT CHẤT VÀ TRANG THIẾT BỊ </b></a></li>
                </ul>
            </div>
        </div>
        <div class="dropdown">
            <span><a href="#"><b> DỊCH VỤ Y TẾ </b></a></span>
             <div class="dropdown-content">
                <ul class="dropdown">
                    <li><a href="#"><b>KHÁM SỨC KHỎE DOANH NGHIỆP</b></a></li>
                    <li><a href="#"><b>DỊCH VỤ BẢO HIỂM </b></a></li>
                    <li><a href="#"><b>GÓI KHÁM SỨC KHỎE </b></a></li>
                    <li><a href="#"><b>THAI SẢN VÀ PHỤ KHOA </b></a></li>
                    <li><a href="#"><b>TRUNG TÂM TƯ VẤN VÀ TIÊM CHỦNG VẮC XIN </b></a></li>
                    <li><a href="#"><b>GÓI KHÁM PHỤC HỒI CHỨC NĂNG </b></a></li>
                    <li><a href="#"><b>KHÁM BẢO HIỂM </b></a></li>
                </ul>
             </div>
        </div>
       
          <div class="dropdown">
              <span><a href="#"><b>HƯỚNG DẪN KHÁCH HÀNG</b></a></span>
              <div class="dropdown-content">
                   <ul class="dropdown">
                       <li><a href="#"><b>ĐẶT LỆNH KHÁM BỆNH TẠI CƠ SỞ</b></a></li>
                       <li><a href="#"> <b>ĐẶT LỊCH KHÁM GẦN BẠN</b> </a></li>
                       <li><a href="#"><b>TRA CỨU KẾT QUẢ</b> </a></li> 
                       <li><a href="#"> <b>BẢNG GIÁ DỊCH VỤ CHUNG</b> </a></li>
                       <li><a href="#"> <b>GIỜ LÀM VIỆC</b> </a> </li>
                       <li> <a href="#" > <b>QUY TRÌNH KHÁM CHỮA BỆNH</b></a></li>
       
                   </ul>
               </div>
           </div>
        <a href="#"><b>LIÊN HỆ</b></a></ul>
      
  </nav>

  <!-- Main Container -->
  <div class="container">

      <!-- Giới thiệu -->
      <section class="section">
          <h2> GIỚI THIỆU </h2>
          <p>MedBookingBTL giúp bạn tìm kiếm bệnh viện phù hợp và đặt lịch khám nhanh chóng. Hệ thống giúp tiết kiệm thời gian, giảm tải áp lực cho bệnh viện và nâng cao trải nghiệm khám chữa bệnh.</p>
      </section>

      <!-- Chức năng chính -->
      <section class="section">
          <h2> CHỨC NĂNG CHÍNH </h2>
          <ul>
              <li>🔍 Tìm kiếm bệnh viện theo chuyên khoa và vị trí.</li>
              <li>📅 Đặt lịch khám trực tuyến.</li>
              <li>📍 Hướng dẫn đường đi với Google Maps.</li>
              <li>📩 Nhận thông báo nhắc lịch hẹn.</li>
          </ul>
      </section>

      <!-- Nút đặt lịch -->
      <section class="section">
          <a href="#" class="btn"><b>Đặt lịch ngay</b></a>
      </section>
  </div>
    

  <!-- Footer -->
  <footer>
      &copy; 2025 MedBookingBTL. Mọi quyền được bảo lưu.
  </footer>

</body>

</html>
