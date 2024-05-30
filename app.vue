<template>
  <div>
    <!-- navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <div class="left-nav">
          <div class="navbar-brand nav-logo" href="#">
            <img class="logo" src="/image/logo-color.png" alt="">
            <div class="word-logo">
              <img class="na" src="/image/logo-na.png" alt="">
              <img class="yoo" src="/image/logo-yoo.png" alt="">
            </div>
          </div>

          <button type="button" class="btn btn-lacation" data-bs-toggle="modal" data-bs-target="#exampleModal">
            <img src="https://cdn-icons-png.flaticon.com/128/927/927667.png" style="width: 18px;">
            ขอนแก่น
            <img src="https://cdn-icons-png.flaticon.com/128/10695/10695955.png" style="width: 10px;">
          </button>

          <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel">
            <div class="modal-dialog modal-dialog-centered">
              <div class="modal-content">

                <div class="modal-header">
                  <h5 class="modal-title" id="exampleModalLabel">เลือกเพื่อเปลี่ยนจังหวัด</h5>
                  <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
                </div>

                <div class="modal-body">
                  1.ขอนแก่น <br>
                  2.อุบลราชธานี <br>
                  3.ประจวบคีรีขันธ์(หัวหิน) <br>
                  4.อุดรธานี <br>
                  5.ระยอง <br>
                  6.ชลยุรี <br>
                  7.สุรินทร์ <br>
                  8.บุรีรัมย์ <br>
                  9.พิษณุโลก <br>
                </div>

                <div class="modal-footer">
                  <button type="button" class="btn btn-in-modal" data-bs-dismiss="modal">ยกเลิก</button>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="right-nav">

          <a class="btn btn-announce order-1" href="#">ลงประกาศฟรี</a>

          <button class="navbar-toggler order-3" type="button" data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" href="#">ซื้อโครงการใหม่</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">ซื้อบ้านมือสอง</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">เช่า/หอพัก</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">รับสร้างบ้าน</a>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" data-bs-toggle="dropdown"
                  aria-expanded="false">
                  บริการอื่นๆ
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="#">บทความ</a></li>
                  <li><a class="dropdown-item" href="#">ค้นหาเจ้าของโครงการ</a></li>
                  <li><a class="dropdown-item" href="#">ค้นหาบริษัทรับสร้างบ้าน</a></li>
                  <li><a class="dropdown-item" href="#">ค้นหาตัวแทนอสังหาฯ</a></li>
                  <li><a class="dropdown-item" href="#">สมัครตัวแทนอสังหาฯ</a></li>
                </ul>
              </li>
            </ul>
          </div>
          <div class="avartar order-2">
            <div class="notification" style="position: relative;">
              <img src="/image/notification.png" style="width: 20px; height: 22px;">
              <span class="notification-badge"></span>
            </div>
            <img src="/image/avartar.png">
          </div>
        </div>
      </div>
    </nav>
    <!-- navbar -->
    <!-- banner -->
    <div>
      <div id="carouselSlide" class="carousel slide container-carousel">
        <div class="carousel-indicators">
          <button data-bs-target="#carouselSlide" data-bs-slide-to="0" class="active" aria-current="true"
            aria-label="Slide 1"></button>
          <button data-bs-target="#carouselSlide" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button data-bs-target="#carouselSlide" data-bs-slide-to="2" aria-label="Slide 3"></button>
          <button data-bs-target="#carouselSlide" data-bs-slide-to="3" aria-label="Slide 4"></button>
          <button data-bs-target="#carouselSlide" data-bs-slide-to="4" aria-label="Slide 5"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="/image/banner-test 1.png" class="d-block w-100">
          </div>
          <div class="carousel-item">
            <img src="/image/banner-test 1.png" class="d-block w-100">
          </div>
          <div class="carousel-item">
            <img src="/image/banner-test 1.png" class="d-block w-100">
          </div>
          <div class="carousel-item">
            <img src="/image/banner-test 1.png" class="d-block w-100">
          </div>
          <div class="carousel-item">
            <img src="/image/banner-test 1.png" class="d-block w-100">
          </div>
        </div>
        <button class="carousel-control-prev" data-bs-target="#carouselSlide" data-bs-slide="prev">
          <span class="carousel-control-prev-icon"></span>
        </button>
        <button class="carousel-control-next" data-bs-target="#carouselSlide" data-bs-slide="next">
          <span class="carousel-control-next-icon"></span>
        </button>
      </div>
    </div>
    <!-- banner -->
    <!-- search/service -->
    <div class="container">
      <div>

      </div>
      <div class="ss-title">
        <span class="text-black">ขอนแก่น</span>
        <span class="text-light-blue">น่า</span>
        <span class="text-green">อยู่</span>
      </div>
      <div class="ss-subtitle">
        <h3>หาที่อยู่ คิดถึงขอนแก่นน่าอยู่</h3>
      </div>

      <div class="card-container ">
        <div class="card" style="width: 18rem;">
          <div style="width: 80px; height: 80px; display: flex; justify-content: center; align-items: center;">
            <img src="/image/home-search.png" class="card-img-top" style="width: 40px; height: 40px;">
          </div>
          <div class="card-body">
            <h5 class="card-title">ซื้อโครงการใหม่</h5>
            <p class="card-text">เลือกดูโครงการใหม่และโครงการที่เปิดตัวใหม่ล่าสุด</p>
          </div>
        </div>

        <div class="card" style="width: 18rem;">
          <img src="/image/home-sale2.png" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">ซื้อบ้านมือสอง</h5>
            <p class="card-text">ประกาศขายที่พักอาศัยมือสอง ที่ดินอาคารพาณิชย์ราคาสุดคุ้ม</p>
          </div>
        </div>

        <div class="card" style="width: 18rem;">
          <img src="/image/home-building.png" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">เช่า/หอพัก</h5>
            <p class="card-text">ค้นหาหอพัก บ้าน คอนโดปล่อยเช่าอาคารสำนักงานทำเลดี</p>
          </div>
        </div>

        <div class="card" style="width: 18rem;">
          <img src="/image/hammer.png" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">รับสร้างบ้าน</h5>
            <p class="card-text">บริการออกแบบและก่อสร้างบ้านจากผู้รับเหมามืออาชีพ</p>
          </div>
        </div>
      </div>

      <div class="btn-tab">
        <button>
          <img src="/image/home1.png">
          ซื้อโครงการใหม่
        </button>
        <button>
          <img src="/image/home2.png">
          ซื้อบ้านมือสอง
        </button>
        <button>
          <img src="/image/building.png">
          ซื้อเช่า/หอพัก
        </button>
        <button>
          <img src="/image/paint-roller.png">
          รับสร้างบ้าน
        </button>
      </div>

      <div class="g-search">
        <form class="d-flex" role="search">
          <button class="b-location" style="margin-right: 10px;">
            <img src="https://cdn-icons-png.flaticon.com/128/927/927667.png"> ตำแหน่งค้นหา
            <p>ขอนแก่น</p>
          </button>
          <input class="form-control me-2" type="search" placeholder="ค้นหาตามโซน, ชื่อโครงการ..." aria-label="Search">
          <button class="b-search">
            <img src="/image/search.png">
            ค้นหา
          </button>
        </form>
      </div>

    </div>
    <!-- search/service -->
    <!-- zone -->
    <div class="g-zone">
      <div class="container">
        <div class="g-text">
          <h1>โซนยอดนิยม</h1>
          <p>แสดงที่อยู่อาศัยตามโซนยอดนิยมในขอนแก่น</p>
        </div>
        <button class="btn-zone">
          ดูทั้งหมด
          <img src="/image/arrow-right2.png">
        </button>
      </div>
    </div>
    <div class="conteainer">

      <div class="g-img">

        <button>
          <img src="/image/arrow-left2.png" alt="">
        </button>

        <div class="card text-bg-dark">
          <img src="/image/zone1.png" class="card-img">
          <div class="card-img-overlay">
            <h5 class="card-title">สามเหลี่ยม-กังสดาล-ม.ขอนแก่น</h5>
          </div>
          <p class="card-text">99 รายการ</p>
        </div>

        <div class="card text-bg-dark">
          <img src="/image/zone2.png" class="card-img">
          <div class="card-img-overlay">
            <h5 class="card-title">มะลิวัลย์-ร.8-สนามบิน</h5>
          </div>
          <p class="card-text">99 รายการ</p>
        </div>

        <div class="card text-bg-dark">
          <img src="/image/zone3.png" class="card-img">
          <div class="card-img-overlay">
            <h5 class="card-title">ม.ภาค-บ้านกอก-บึงหนองโคตร</h5>
          </div>
          <p class="card-text">99 รายการ</p>
        </div>

        <div class="card text-bg-dark">
          <img src="/image/zone4.png" class="card-img">
          <div class="card-img-overlay">
            <h5 class="card-title">ทุ่งสร้าง-ศรีจันทร์-ราชมงคล</h5>
          </div>
          <p class="card-text">99 รายการ</p>
        </div>

        <div class="card text-bg-dark">
          <img src="/image/zone5.png" class="card-img">
          <div class="card-img-overlay">
            <h5 class="card-title">กลางเมือง-เมืองเก่า-กุดกว้าง</h5>
          </div>
          <p class="card-text">99 รายการ</p>
        </div>

        <div class="card text-bg-dark">
          <img src="/image/zone6.png" class="card-img">
          <div class="card-img-overlay">
            <h5 class="card-title">โนนม่วง-มข.-เลี่ยงเมือง-โนนเรือง</h5>
          </div>
          <p class="card-text">99 รายการ</p>
        </div>

        <button>
          <img src="/image/arrow-right2.png" alt="">
        </button>

      </div>
    </div>
    <!-- zone -->
    <!-- Launch Soon -->
    <div class="launch-soon">
      <div class="container">
        <div class="g-text">
          <h1>โครงการใกล้เปิดตัวเร็วๆ นี้</h1>
          <p>ประกาศเปิดตัวโครงการและเฟสใหม่พร้อมให้จับจอง</p>
        </div>

        <div class="g-ls">
          <div>
            <img src="/image/LaunchSoon111.png">
          </div>
          <div>
            <img src="/image/LaunchSoon222.png">
          </div>
          <div>
            <img src="/image/LaunchSoon333.png">
          </div>
          <div>
            <img src="/image/LaunchSoon444.png">
          </div>
          <div>
            <img src="/image/LaunchSoon555.png">
          </div>
          <div>
            <img src="/image/LaunchSoon666.png">
          </div>
        </div>

        <button class="btn-zone">
          ดูทั้งหมด
          <img src="/image/arrow-right2.png">
        </button>

      </div>
    </div>
    <!-- Launch Soon -->
    <!-- Recommend -->
    <div class="g-recommend">
      <div class="container">
        <div class="g-text">
          <h1>โครงการแนะนำ</h1>
          <p>คัดสรรโครงการสุดคุ้มจากทั่วทุกโซนที่เราอยากแนะนำ</p>
        </div>
        <button class="btn-recommend">
          ดูทั้งหมด
          <img src="/image/arrow-right2.png">
        </button>
      </div>

      <div class="g-rec">
        <button>
          <img src="/image/arrow-left2.png" alt="">
        </button>
        <div>
          <img src="/image/Recommend1.png">
        </div>
        <div>
          <img src="/image/Recommend2.png">
        </div>
        <div>
          <img src="/image/Recommend3.png">
        </div>
        <div>
          <img src="/image/Recommend4.png">
        </div>
        <button>
          <img src="/image/arrow-right2.png" alt="">
        </button>
      </div>
    </div>
    <!-- Recommend -->
    <!-- Review -->
    <div class="container">
      <div class="g-review">
        <div class="review-text">
          <div class="g-text">
            <img src="/image/Reviewlogo.png">
            <h1>วิดีโอแนะนำโครงการ</h1>
            <p>น่าอยู่รีวิวจัดเต็มพาไปชมบ้านตัวอย่างและบ้านจริงจากทุกโครงการแบบทุกซอกทุกมุม รายละเอียดต่างๆ
              ที่น่าสนใจเราจัดมาให้ถึงที่</p>
            <button class="btn-review">
              ดูทั้งหมด
              <img src="/image/arrow-right2.png">
            </button>
          </div>
        </div>
        <div class="review-video">
          <iframe width="560" height="315" src="https://www.youtube.com/embed/wOByxbn025A?si=FDsbe7rxpu1ZJ_uK"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
      </div>

      <div style="display: flex; flex-direction: row;">
        <div>
          <img src="/image/Review1.png" style="max-width: 100%;">
        </div>
        <div>
          <img src="/image/Review2.png" style="max-width: 100%;">
        </div>
        <div>
          <img src="/image/Review3.png" style="max-width: 100%;">
        </div>
        <div>
          <img src="/image/Review4.png" style="max-width: 100%;">
        </div>
      </div>
    </div>
    <!-- Review -->
    <!-- 360 -->
    <div class="container">
      <div class="g-360">
        <div class="g-text">
          <img src="/image/360logo.png">
          <h1>ชมบ้านแบบ 360 องศา</h1>
          <p>ชมบรรยากาศบ้านได้ทุกมุมมองเสมือนจริงแบบ 360 องศา </p>
        </div>

        <div class="g-3602">
          <button>
            <img src="/image/arrow-left2.png" alt="">
          </button>
          <div>
            <img src="/image/3601.png">
          </div>
          <div>
            <img src="/image/3602.png">
          </div>
          <div>
            <img src="/image/3603.png">
          </div>
          <button>
            <img src="/image/arrow-right2.png" alt="">
          </button>
        </div>
        <div style="display: flex; justify-content: center;">
          <button class="btn-360">
            ดูทั้งหมด
            <img src="/image/arrow-right2.png">
          </button>
        </div>
      </div>
    </div>
    <!-- 360 -->
    <!-- Second Hand -->
    <div class="g-secondhand">
      <div class="container">
        <div class="g-text">
          <h1>ซื้อบ้านมือสอง</h1>
          <p>ประกาศขายที่พักอาศัยมือสอง ที่ดิน อาคารพาณิชย์ราคาสุดคุ้ม</p>
        </div>
        <button class="btn-secondhand">
          ดูทั้งหมด
          <img src="/image/arrow-right2.png">
        </button>
      </div>

      <div class="g-second">
        <button>
          <img src="/image/arrow-left2.png" alt="">
        </button>
        <div>
          <img src="/image/SecondHand1.png">
        </div>
        <div>
          <img src="/image/SecondHand2.png">
        </div>
        <div>
          <img src="/image/SecondHand3.png">
        </div>
        <div>
          <img src="/image/SecondHand4.png">
        </div>
        <button>
          <img src="/image/arrow-right2.png" alt="">
        </button>
      </div>
    </div>
    <!-- Second Hand -->
    <!-- Rental -->
    <div class="g-rental">
      <div class="container">
        <div class="g-text">
          <h1>ซื้อบ้านมือสอง</h1>
          <p>ประกาศขายที่พักอาศัยมือสอง ที่ดิน อาคารพาณิชย์ราคาสุดคุ้ม</p>
        </div>
        <button class="btn-rental">
          ดูทั้งหมด
          <img src="/image/arrow-right2.png">
        </button>
      </div>

      <div class="g-ren">
        <button>
          <img src="/image/arrow-left2.png" alt="">
        </button>
        <div>
          <img src="/image/Rental1.png">
        </div>
        <div>
          <img src="/image/Rental2.png">
        </div>
        <div>
          <img src="/image/Rental3.png">
        </div>
        <div>
          <img src="/image/Rental4.png">
        </div>
        <button>
          <img src="/image/arrow-right2.png" alt="">
        </button>
      </div>
    </div>
    <!-- Rental -->
    <!-- Builder -->
    <div class="container">
      <div class="g-builder">
        <div class="g-text">
          <h1>ประกาศรับสร้างบ้าน</h1>
          <p>บริการออกแบบและก่อสร้างบ้านจากบริษัทผู้รับเหมามืออาชีพ</p>
        </div>

        <div class="g-build">
          <button>
            <img src="/image/arrow-left2.png" alt="">
          </button>
          <div>
            <img src="/image/Builder1.png">
          </div>
          <div>
            <img src="/image/Builder2.png">
          </div>
          <div>
            <img src="/image/Builder3.png">
          </div>
          <div>
            <img src="/image/Builder4.png">
          </div>
          <button>
            <img src="/image/arrow-right2.png" alt="">
          </button>
        </div>
        <div style="display: flex; justify-content: center;">
          <button class="btn-builder">
            ดูทั้งหมด
            <img src="/image/arrow-right2.png">
          </button>
        </div>
      </div>
    </div>
    <!-- Builder -->
    <!-- Ads -->
    <div class="container">
      <div class="ads">
        <img src="/image/Ads-1.png" style="max-width: 50%; max-height: 50%;">
        <img src="/image/Ads-2.png" style="max-width: 50%; max-height: 50%;">
      </div>
    </div>
    <!-- Ads -->
    <!-- Blogs -->
    <div class="g-blogs">
      <div class="container">
        <div class="g-text">
          <img src="/image/Blogslogo.png">
          <h1>บทความข่าวสาร</h1>
          <div class="btn-tab">
            <button>อัปเดตล่าสุด</button>
            <button>รีวิวบ้าน</button>
            <button>สาระน่ารู้</button>
            <button>ไลฟ์สไตล์</button>
            <button>ข่าวสาร</button>
          </div>
        </div>
        <button class="btn-blogs">
          ดูทั้งหมด
          <img src="/image/arrow-right2.png">
        </button>
      </div>

      <div class="g-b">
        <div>
          <img src="/image/Blogs1.png">
        </div>
        <div>
          <img src="/image/Blogs2.png">
        </div>
        <div>
          <img src="/image/Blogs3.png">
        </div>
        <div>
          <img src="/image/Blogs4.png">
        </div>
      </div>
    </div>
    <!-- Blogs -->
    <!-- Other Video-->
    <div class="g-othervideo">
      <div class="container">
        <div class="g-text">
          <img src="/image/Blogslogo.png">
          <h1>วิดีโออื่นๆ</h1>
          <p>เกร็ดความรู้เกี่ยวกับบ้าน รีวิวต่างๆ และเนื้อหาอื่นๆ ที่น่าสนใจ</p>
        </div>
        <button class="btn-othervideo">
          ดูทั้งหมด
          <img src="/image/arrow-right2.png">
        </button>
      </div>

      <div class="g-other">
        <div>
          <img src="/image/Blogs1.png">
        </div>
        <div>
          <img src="/image/Blogs2.png">
        </div>
        <div>
          <img src="/image/Blogs3.png">
        </div>
        <div>
          <img src="/image/Blogs4.png">
        </div>
      </div>
    </div>
    <!-- Other Video-->
    <!-- Partnership -->
    <div class="partnership">
      <img src="/image/Partnership.png">
    </div>
    <!-- Partnership -->
    <!--  -->
  </div>
</template>

<script>
export default {
  mounted() {
    // ฟังก์ชันเพื่อย้าย div ของอวตาร์ไปยังเมนูแถบนำเมนูเมื่อขนาดหน้าจอเล็ก
    function moveAvatarToNavbar() {
      var avatarDiv = document.querySelector(".avartar");
      var navbarMenu = document.querySelector(".navbar-collapse");
      if (window.innerWidth <= 991) {
        navbarMenu.insertBefore(avatarDiv, navbarMenu.firstChild);
      }
    }

    // ฟังก์ชันเพื่อย้าย div ของอวตาร์กลับไปยังตำแหน่งเดิมเมื่อขนาดหน้าจอใหญ่
    function moveAvatarBack() {
      var avatarDiv = document.querySelector(".avartar");
      var rightNav = document.querySelector(".right-nav");
      if (window.innerWidth > 991) {
        rightNav.insertBefore(avatarDiv, rightNav.lastChild.nextSibling);
      }
    }

    // เรียกใช้ฟังก์ชันเมื่อหน้าเว็บโหลดและเมื่อหน้าต่างถูกปรับขนาด
    this.$nextTick(() => {
      moveAvatarToNavbar(); // เลื่อน div ของอวตาร์เมื่อหน้าเว็บโหลด
    });

    window.addEventListener("resize", function () {
      moveAvatarToNavbar(); // เลื่อน div ของอวตาร์เมื่อขนาดหน้าต่างถูกปรับขนาด
      moveAvatarBack(); // ย้าย div ของอวตาร์กลับเมื่อขนาดหน้าต่างถูกปรับขนาด
    });
  }
};
</script>

<style scoped>
* {
  font-size: 14px;
  font-family: Prompt;
}
/* _______________________Partnership_________________________ */
.partnership{
  display: flex;
  justify-content: center;
}

/* _______________________Other Video_________________________ */
.g-other button {
  background-color: #00AEEF;
  border-radius: 10px;
  height: 40px;
  width: 40px;
  border: none;
}

.g-other {
  display: flex;
  justify-content: center;
  align-items: center;
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
}

.g-other img {
  width: 100%;
  height: auto;
}

.btn-othervideo img {
  margin-left: 7px;
}

.btn-othervideo {
  background-color: #00AEEF;
  border-radius: 7px;
  height: 42px;
  width: 120;
  margin-left: 15px;
  padding: 0 15px;
  color: white;
  border: none;
}

.g-othervideo .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.g-othervideo {
  margin-top: 3em;
}

/* _______________________Blogs____________________________ */
.g-b button {
  background-color: #00AEEF;
  border-radius: 10px;
  height: 40px;
  width: 40px;
  border: none;
}

.g-b {
  display: flex;
  justify-content: center;
  align-items: center;
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
}

.g-b img {
  width: 100%;
  height: auto;
}

.btn-blogs img {
  margin-left: 7px;
}

.btn-blogs {
  background-color: #00AEEF;
  border-radius: 7px;
  height: 42px;
  width: 120;
  margin-left: 15px;
  padding: 0 15px;
  color: white;
  border: none;
}

.g-blogs .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.g-blogs {
  margin-top: 3em;
}


/* __________________________Ads__________________________ */
.ads {
  margin-top: 3em;
  display: flex
}

/* _______________________Builder_____________________________ */
.g-build button {
  background-color: #00AEEF;
  border-radius: 10px;
  height: 40px;
  width: 40px;
  border: none;
}

.g-build {
  display: flex;
  justify-content: center;
  align-items: center;
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
}

.g-build img {
  width: 100%;
  height: auto;
}

.btn-builder img {
  margin-left: 7px;
}

.btn-builder {
  background-color: #00AEEF;
  border-radius: 7px;
  height: 42px;
  width: 120;
  margin-left: 15px;
  padding: 0 15px;
  color: white;
  border: none;
  justify-content: center;
  align-items: center;

}

.g-builder .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.g-builder {
  margin-top: 3em;
}

.g-builder .g-text {
  justify-content: center;
  text-align: center;
}

.g-builder .g-text h1 {
  color: #00AEEF;
}

.g-builder {
  margin-top: 3em;
}


/* ________________________Rental_________________________ */
.g-ren button {
  background-color: #00AEEF;
  border-radius: 10px;
  height: 40px;
  width: 40px;
  border: none;
}

.g-ren {
  display: flex;
  justify-content: center;
  align-items: center;
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
}

.g-ren img {
  width: 100%;
  height: auto;
}

.btn-rental img {
  margin-left: 7px;
}

.btn-rental {
  background-color: #00AEEF;
  border-radius: 7px;
  height: 42px;
  width: 120;
  margin-left: 15px;
  padding: 0 15px;
  color: white;
  border: none;
}

.g-rental .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.g-rental {
  margin-top: 3em;
}

/* ______________________Second Hand__________________________ */
.g-second button {
  background-color: #00AEEF;
  border-radius: 10px;
  height: 40px;
  width: 40px;
  border: none;
}

.g-second {
  display: flex;
  justify-content: center;
  align-items: center;
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
}

.g-second img {
  width: 100%;
  height: auto;
}

.btn-secondhand img {
  margin-left: 7px;
}

.btn-secondhand {
  background-color: #00AEEF;
  border-radius: 7px;
  height: 42px;
  width: 120;
  margin-left: 15px;
  padding: 0 15px;
  color: white;
  border: none;
}

.g-secondhand .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.g-secondhand {
  margin-top: 3em;
}

/* ____________________________360________________________ */

.g-3602 button {
  background-color: #00AEEF;
  border-radius: 10px;
  height: 40px;
  width: 40px;
  border: none;
}

.g-3602 {
  display: flex;
  justify-content: center;
  align-items: center;
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
}

.g-3602 img {
  width: 100%;
  height: auto;
}

.btn-360 img {
  margin-left: 7px;
}

.btn-360 {
  background-color: #00AEEF;
  border-radius: 7px;
  height: 42px;
  width: 120;
  margin-left: 15px;
  padding: 0 15px;
  color: white;
  border: none;
  justify-content: center;
  align-items: center;

}

.g-360 .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.g-360 {
  margin-top: 3em;
}

.g-360 .g-text {
  justify-content: center;
  text-align: center;
}

.g-360 {
  margin-top: 3em;
}


/* ___________________________Review__________________________ */
.review-text {
  display: flex;
  justify-content: center;
  /* จัดให้อยู่กึ่งกลางในแนวนอน */
  align-items: center;
  /* จัดให้อยู่กึ่งกลางในแนวตั้ง */
}

.btn-review {
  background-color: #00AEEF;
  border-radius: 7px;
  height: 42px;
  width: 120;
  padding: 0 15px;
  color: white;
  border: none;
}

.g-review {
  margin-top: 3em;
  display: flex;
}

.g-review .review-text h1 {
  font-size: 42px;
  font-weight: 700;
}

.g-review .review-text p {
  font-size: 18px;
  font-weight: 400;
}


/* ________________________Recommend_________________________ */
.g-rec button {
  background-color: #00AEEF;
  border-radius: 10px;
  height: 40px;
  width: 40px;
  border: none;
}

.g-rec {
  display: flex;
  justify-content: center;
  align-items: center;
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
}

.g-rec img {
  width: 100%;
  height: auto;
}

.btn-recommend img {
  margin-left: 7px;
}

.btn-recommend {
  background-color: #00AEEF;
  border-radius: 7px;
  height: 42px;
  width: 120;
  margin-left: 15px;
  padding: 0 15px;
  color: white;
  border: none;
}

.g-recommend .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.g-recommend {
  margin-top: 3em;
}

/* ____________________Launch Soon_________________________ */
.launch-soon .container img {
  max-width: 100%;
  height: auto;
}

.g-ls {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5px;
  justify-items: center;
}

.launch-soon .container {
  text-align: center;
}

.launch-soon .container div p {
  font-size: 18px;
  font-weight: 400;
}

.launch-soon .container div h1 {
  font-size: 32px;
  font-weight: 600;
  color: #00AEEF;
}

.launch-soon {
  margin-top: 3em;
  display: flex;
}


/* ___________________________zone___________________________ */
.g-img .card p {
  margin-left: 10px;
}

.g-img .card img {
  filter: brightness(50%);
}


.g-img .card h5 {
  font-size: 18px;
  font-weight: 500;
}

.g-img button {
  background-color: #00AEEF;
  border-radius: 10px;
  height: 40px;
  width: 40px;
  border: none;
}

.g-img .card {
  margin: 10px;
}

.g-img {
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 14px;
  border: none;
}

.btn-zone img {
  margin-left: 7px;
}

.btn-zone {
  background-color: #00AEEF;
  border-radius: 7px;
  height: 42px;
  width: 120;
  margin-left: 15px;
  padding: 0 15px;
  color: white;
  border: none;
}

.g-text h1 {
  font-size: 32px;
  font-weight: 600;
}

.g-text p {
  font-size: 18px;
  font-weight: 400;
}

.g-zone .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.g-zone {
  margin-top: 3em;
}


/* _____________________search/service_______________________ */
.g-search input {
  box-shadow: 5px 5px 50px rgba(0, 174, 239, 0.2);
}

.g-search .b-search {
  display: flex;
  align-items: center;
  border-radius: 10px;
  border: none;
  background-color: #00AEEF;
  color: white;
  font-size: 18px;
  padding: 10px 15px;
  box-shadow: 5px 5px 50px rgba(0, 174, 239, 0.2);
}

.g-search .b-location {
  text-align: start;
  justify-content: center;
  border-right: 2px solid rgb(230, 230, 230);
  border-left: 2px solid white;
  border-top: 2px solid white;
  border-bottom: 2px solid white;
  background-color: white;
  border-radius: 10px;
  width: 160px;
  height: 47px;
  box-shadow: 5px 5px 50px rgba(0, 174, 239, 0.2);
}

.g-search .b-location img {
  margin: 0;
}

.g-search .b-location p {
  font-size: 18px;
}

.g-search button img {
  margin: 0 5px;
  width: 15px;
  height: 15px;
}

.g-search {
  padding-bottom: 10px;
}

.btn-tab {
  display: flex;
  justify-content: center;
}

.btn-tab button {
  margin: 10px;
  padding: 10px;
  border: white;
  background-color: white;
  box-shadow: 5px 5px 50px rgba(0, 174, 239, 0.2);
}

.btn-tab button:hover {
  border-bottom: 2px solid #00AEEF;
  color: #00AEEF;
  background-color: white;
}

.card-container {
  display: flex;
  justify-content: center;
}

.card-container img {
  width: 80px;
  height: 80px;
}

.card-container .card {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin: 10px;
  border-radius: 14px;
  border: none;
  box-shadow: 5px 5px 40px rgba(0, 174, 239, 0.2);
}

.card-container .card .card-body .card-title {
  font-size: 22px;
}

.ss-title {
  font-size: 40px;
  font-weight: 500;
  text-align: center;
  margin-top: 0.5em;
}

.ss-subtitle h3 {
  font-size: 22px;
  font-weight: 400;
  text-align: center;
}

.text-black {
  color: #000000;
  font-size: 40px;
  font-weight: 500;
}

.text-light-blue {
  color: #00AEEF;
  font-size: 40px;
  font-weight: 500;
}

.text-green {
  color: #1BB967;
  font-size: 40px;
  font-weight: 500;
}

/* _____________________banner_______________________ */

.carousel-indicators {
  display: flex;
  text-align: center;
  background: white;
  border-radius: 10px;
  align-items: center;
  justify-content: center;
  width: auto;
  height: auto;
  max-width: 120px;
  max-height: 32px;
  margin: auto;
  margin-bottom: 10px;
}

.carousel-indicators button {
  width: 0.5rem;
  height: 0.5rem;
  border-radius: 50%;
  border: none;
  margin: 5px 5px;
  background-color: rgba(0, 174, 239, 0.2);
}

.carousel-indicators button.active {
  background-color: rgb(0, 174, 239);
}

.container-carousel {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.carousel-control-prev {

  background-image: url('/image/arrow-left.png');
  background-size: cover;
  width: 5%;
  max-width: 40px;
  max-height: 40px;
  height: 15%;
  margin-left: 2%;
  border-radius: 7px;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
}

.carousel-control-prev-icon {
  display: none;
}

.carousel-control-next {
  background-image: url('/image/arrow-right.png');
  background-size: cover;
  width: 5%;
  height: 15%;
  max-width: 40px;
  max-height: 40px;
  margin-right: 2%;
  border-radius: 7px;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
}

.carousel-control-next-icon {
  display: none;
}



/* _____________________navbar_____________________ */
@media (max-width: 992px) {
  .navbar-collapse {
    padding: 30px 40px;
    position: fixed;
    z-index: 100;
    top: 0;
    left: -100%;
    width: 50%;
    height: 100%;
    background-color: #fff;
    transition: left 0.3s ease;
  }

  .navbar-collapse.show {
    left: 0;
  }

  .nav-link {
    margin: 10px 20px;
    text-align: left;
    font-size: 14px;
    border-top: 1px solid #ccc;
  }

  .avartar {
    padding: 10px 10px 30px 10px;
    justify-content: center;
  }
}

.dropdown-toggle::after {
  content: '';
  display: inline-block;
  width: 16px;
  height: 16px;
  color: white;
  margin-bottom: 5px;
  margin-left: 0;
  vertical-align: middle;
  background-image: url('https://cdn-icons-png.flaticon.com/128/10695/10695955.png');
  background-size: cover;
  background-repeat: no-repeat;
}

.navbar-toggler-icon {
  width: 18px;
  margin-left: -2px;
}

.navbar-toggler:focus {
  box-shadow: none;
}

.navbar-toggler {
  width: 38px;
}

.notification-badge {
  position: absolute;
  top: 0;
  right: 6px;
  width: 10px;
  height: 10px;
  background-color: #00AEEF;
  border-radius: 50%;
}

.notification {
  justify-content: center;
  align-self: center;
}

.avartar {
  margin: 0 1em;
  display: flex;
}

.avartar img {
  margin: 0 0.5em;
}

.right-nav {
  display: flex;
}

.btn-announce {
  background: #1BB967;
  color: white;
  margin: 0 0.5em;
}

.btn-in-modal {
  width: 100%;
  border-color: rgb(74, 213, 255);
  border-width: 2px;
  color: rgb(74, 213, 255);
}

.btn-in-modal:active {
  width: 100%;
  border-color: rgb(74, 213, 255);
  border-width: 2px;
  color: rgb(74, 213, 255);
}

.btn-lacation {
  display: inline;
  border-radius: 10px;
  height: 40px;
  margin-left: 0;
  border-width: 2px;
  border-color: rgb(150, 150, 150);
  box-decoration-break: none;
}

.left-nav {
  display: flex;
  justify-content: center;
  align-items: center;
}

.nav-logo {
  display: flex;
}

.logo {
  width: 22px;
  height: 30px;
  top: 28px;
  left: 60px;
  margin: 0.5em;
}

.na {
  width: 28px;
  height: 16px;
  top: 33px;
  left: 84px;
}

.yoo {
  width: 39.5px;
  height: 16px;
  top: 28px;
  left: 111.5px;
}

.word-logo {
  margin-top: 0.5rem;
}
</style>