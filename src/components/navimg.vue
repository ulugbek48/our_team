<template>
    <div class="navbar_body" id="process">
      <div class="navbar_body_top_section">
        <div class="navbar_body_top_section_img">
          <!-- <img src="../assets/backgroun-img.jpg" alt="asdf" /> -->
          <div class="navbar_body_top_section_img_content">
            <h1 class="navbar_body_top_section_img_first_text">
              Making brands stand out
            </h1>
            <h1 class="navbar_body_top_section_img_second_text">
              is our obsession
            </h1>
  
            <hr />
  
            <span>Let us help your brand stand out.</span>
          </div>
          <img src="../assets/image/x.png" alt="" />
        </div>
      </div>
      <div class="navbar_body_bottom_section">
        <div class="navbar_body_bottom_section_wrap">
          <div class="navbar_body_bottom_section_text">
            <p>
              Minimalist is a full-service digital creative agency located in
              Ontorio Canada. We focus on design, consulting, technology, and
              photography. We’ve been building unique digital products, platforms,
              and experiences for the past 6 years. Let us help your company grow.
            </p>
          </div>
  
          <button>Get in Touch</button>
        </div>
      </div>
    </div>
  </template>
  
  <script setup></script>
  
  <style lang="scss" scoped>
  * {
    padding: 0;
    margin: 0;
  }
  .navbar_body {
    width: 100%;
    margin: 0 auto;
    max-width: 1600px;
  }
  
  .navbar_body_top_section {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .navbar_body_top_section_img {
    width: 100%;
    height: auto;
    padding-top: 27.1%;
    background: url(../assets/image/imgnav.png), lightgray 50% / cover no-repeat;
    background-repeat: no-repeat;
    background-size: 100%;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-content: center;
    position: relative;
  
    img {
      position: absolute;
      bottom: -25px;
    }
  }
  
  .navbar_body_top_section_img_content {
    display: flex;
    position: absolute;
    flex-direction: column;
    gap: 25px;
    align-items: center;
    justify-content: center;
    top: 25%;
  
    h1 {
      color: #fff;
      text-align: center;
      font-family: Montserrat;
      font-size: 44px;
      font-style: normal;
      font-weight: 500;
      line-height: 55px; /* 125% */
      text-transform: uppercase;
    }
  
    hr {
      width: 80px;
      height: 2px;
      flex-shrink: 0;
      background: #fff;
      border: none;
    }
    span {
      color: rgba(255, 255, 255, 0.81);
      text-align: center;
      font-family: Vollkorn;
      font-size: 15px;
      font-style: normal;
      font-weight: 500;
      line-height: 20px;
      -webkit-text-fill-color: white;
      -webkit-text-stroke: rgba(255, 255, 255, 0.81);
    }
  }
  
  .navbar_body_bottom_section {
    background-color: #fefec9;
  }
  
  .navbar_body_bottom_section_wrap {
    width: 940px;
    padding: 60px 0;
    display: flex;
    margin: 0 auto;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 40px;
    background-color: #fefec9;
  
    p {
      color: #47474f;
      text-align: center;
      font-family: Vollkorn;
      font-size: 18px;
      font-style: normal;
      font-weight: 400;
      line-height: 25px; /* 138.889% */
    }
  
    button {
      width: 159px;
      height: 53px;
      flex-shrink: 0;
      color: #47474f;
      text-align: center;
      font-family: Vollkorn;
      font-size: 16px;
      font-style: normal;
      font-weight: 400;
      line-height: 20px;
      border-bottom: 2px solid black;
      background-color: transparent;
      transition: all 0.3s linear;
      &:hover {
        border-radius: 20px;
      }
    }
  }
  
  @media (max-width: 1250px) {
    .navbar_body_top_section_img_content {
      top: 20%;
      gap: 10px;
      h1 {
        color: #fff;
        text-align: center;
        font-size: 40px;
      }
    }
  }
  @media (min-width: 768px) and (max-width: 992px) {
    .navbar_body_top_section_img {
      padding-top: 38%;
      background-size: 140%;
  
      img {
        position: absolute;
        bottom: -25px;
      }
    }
    .navbar_body_top_section_img_content {
      top: 25%;
      gap: 30px !important;
      .navbar_body_top_section_img_second_text {
        margin-top: -25px;
      }
  
      h1 {
        font-size: 35px;
      }
    }
  
    .navbar_body_bottom_section_wrap {
      width: 85%;
      padding: 40px 0;
      gap: 30px;
  
      p {
        font-size: 15px;
      }
  
      button {
        width: 130px;
        height: 45px;
      }
    }
  }
  
  @media (min-width: 576px) and (max-width: 768px) {
    img {
      display: none;
    }
  
    .navbar_body_top_section_img {
      padding-top: 38%;
      background-size: 140%;
  
      img {
        position: absolute;
        bottom: -25px;
      }
    }
    .navbar_body_top_section_img_content {
      gap: 10px;
      top: 28%;
      .navbar_body_top_section_img_second_text {
        margin-top: -10px;
      }
  
      img {
        width: 50% !important;
      }
      span {
        font-size: 15px;
      }
  
      hr {
        width: 13%;
      }
  
      h1 {
        font-size: 28px;
      }
    }
  
    .navbar_body_bottom_section_wrap {
      width: 85%;
      padding: 40px 0;
      gap: 30px;
  
      p {
        font-size: 12px;
      }
  
      button {
        width: 100px;
        height: 33px;
        font-size: 12px;
      }
    }
  }
  
  @media (max-width: 576px) {
    img {
      display: none;
    }
  
    .navbar_body_top_section_img {
      padding-top: 46.3%;
      background-size: 170%;
  
      img {
        position: absolute;
        bottom: -25px;
      }
    }
    .navbar_body_top_section_img_content {
      gap: 5px;
      top: 20%;
      .navbar_body_top_section_img_second_text {
        margin-top: -20px;
        margin-bottom: -10px;
      }
  
      img {
        width: 50% !important;
      }
      span {
        font-size: 13px;
      }
  
      hr {
        width: 13%;
      }
  
      h1 {
        font-size: 20px;
      }
    }
  
    .navbar_body_bottom_section_wrap {
      width: 85%;
      padding: 40px 0;
      gap: 30px;
  
      p {
        font-size: 10px;
      }
  
      button {
        width: 100px;
        height: 33px;
        font-size: 12px;
      }
    }
  }
  </style>