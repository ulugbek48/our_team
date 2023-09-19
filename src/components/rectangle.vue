<template>
    <div class="review_component">
      <div class="review_wrapper">
        <img src="../assets/image/qoshtirnoq.png" alt="" />
  
        <div class="reviews_content_boxes">
          <div class="reviews_content_box">
            <h2>
              “I love these guys! They did a great job. I would recommend them to
              anyone.”
            </h2>
  
            <img
              class="reviews_content_box_img"
              src="../assets/image/person_5.png"
              alt=""
            />
  
            <p>Julius Von Uberstien</p>
          </div>
  
          <div class="vertical-line"></div>
  
          <div class="reviews_content_box box-left">
            <h2>“Elexis Corp. has grown immensely with the help of Minimal.”</h2>
  
            <img
              class="reviews_content_box_img"
              src="../assets/image/person_6.png"
              alt=""
            />
  
            <p>Rachel Stamos</p>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup></script>
  
  <style lang="scss" scoped>
  .review_component {
    width: 100%;
    padding: 70px 0;
    background: #f5f5f5;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .review_wrapper {
    width: 940px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  
  img {
    margin-bottom: 40px;
  }
  
  .reviews_content_boxes {
    position: relative;
    width: 100%;
    display: flex;
    justify-content: center;
  }
  .reviews_content_box {
    display: flex;
    flex-direction: column;
    text-align: center;
    justify-content: center;
    align-items: center;
    width: 40%;
    padding: 30px 54px 5px;
    h2 {
      color: #333;
      text-align: center;
      font-family: Vollkorn;
      font-size: 26px;
      font-style: normal;
      font-weight: 400;
      line-height: 33px; /* 126.923% */
    }
  
    p {
      color: #ababab;
      text-align: center;
      font-family: Montserrat;
      font-size: 14px;
      font-style: normal;
      font-weight: 400;
      line-height: 20px; /* 142.857% */
      text-transform: uppercase;
    }
  
    img {
      margin: 24px 0 10px 0;
    }
  }
  
  .vertical-line {
    border-left: 2px solid #ababab2a; /* Change color and thickness as needed */
    height: 200px;
    position: absolute;
    left: 50%;
    top: 10%;
  }
  
  @media (min-width: 768px) and (max-width: 992px) {
    .review_wrapper {
      width: 85%;
  
      img {
        margin-bottom: 30px !important;
      }
  
      .reviews_content_boxes {
        align-items: flex-start !important;
      }
  
      .reviews_content_box {
        width: 50%;
      }
  
      h2 {
        font-size: 20px;
      }
    }
  }
  
  @media (min-width: 576px) and (max-width: 768px) {
    .review_wrapper {
      width: 85%;
  
      img {
        margin-bottom: 30px !important;
      }
  
      .reviews_content_boxes {
        align-items: flex-start !important;
      }
  
      .reviews_content_box {
        width: 50%;
        padding: 10px 25px 5px;
      }
  
      h2 {
        font-size: 18px;
      }
    }
  }
  
  @media (max-width: 576px) {
    .review_wrapper {
      width: 85%;
  
      img {
        margin-bottom: 30px !important;
      }
  
      .reviews_content_boxes {
        align-items: flex-start !important;
      }
  
      .reviews_content_box {
        width: 50%;
        padding: 10px 10px 5px;
      }
  
      h2 {
        font-size: 16px;
      }
    }
  }
  </style>