<template>
    <div class="main_section" id="projects">
      <div class="main_wrapper">
        <h2>Recent projects</h2>
  
        <hr />
  
        <div class="main_content_boxes">
          <div class="main_content_box">
            <img src="../assets/image/wood.png" alt="" />
  
            <h3 class="main_content_box_img_name">woods</h3>
  
            <p class="main_content_box_description">Photography</p>
          </div>
  
          <div class="main_content_box">
            <img src="../assets/image/less.png" alt="" />
  
            <h3 class="main_content_box_img_name">Path</h3>
  
            <p class="main_content_box_description">Website • Photography</p>
          </div>
  
          <div class="main_content_box">
            <img src="../assets/image/darkness.png" alt="" />
  
            <h3 class="main_content_box_img_name">darkness</h3>
  
            <p class="main_content_box_description">Website</p>
          </div>
  
          <div class="main_content_box">
            <img src="../assets/image/moun.png" alt="" />
  
            <h3 class="main_content_box_img_name">waves</h3>
  
            <p class="main_content_box_description">Photography</p>
          </div>
  
          <div class="main_content_box">
            <img src="../assets/image/rain.png" alt="" />
  
            <h3 class="main_content_box_img_name">Drops</h3>
  
            <p class="main_content_box_description">Website</p>
          </div>
  
          <div class="main_content_box">
            <img src="../assets/image/ocean.png" alt="" />
  
            <h3 class="main_content_box_img_name">Ocean</h3>
  
            <p class="main_content_box_description">Website</p>
          </div>
  
          <div class="main_content_box">
            <img src="../assets/image/town.png" alt="" />
  
            <h3 class="main_content_box_img_name">town</h3>
  
            <p class="main_content_box_description">Website</p>
          </div>
  
          <div class="main_content_box">
            <img src="../assets/image/mountain.png" alt="" />
  
            <h3 class="main_content_box_img_name">mountain</h3>
  
            <p class="main_content_box_description">Website</p>
          </div>
  
          <div class="main_content_box">
            <img src="../assets/image/mountain.png" alt="" />
  
            <h3 class="main_content_box_img_name">camera</h3>
  
            <p class="main_content_box_description">Website</p>
          </div>
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
  
  .main_section {
    margin: 0 auto;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f5f5f5;
  }
  
  .main_wrapper {
    width: 940px;
    margin: 70px auto;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    border: 1px solid #0000;
    h2 {
      color: #333;
      text-align: center;
      font-family: Montserrat;
      font-size: 23px;
      font-style: normal;
      font-weight: 400;
      line-height: 36px; /* 156.522% */
      text-transform: uppercase;
    }
  
    hr {
      width: 80px;
      margin: 30px 0 42px 0;
      height: 2px;
      flex-shrink: 0;
      background: rgba(0, 0, 0, 0.09);
      border: none;
    }
  
    .main_content_boxes {
      width: 100%;
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      justify-content: space-between;
  
      .main_content_box {
        transition: all 0.2s linear;
  
        background-color: #fff;
        box-sizing: content-box;
        width: 32%;
        box-shadow: 0 0.1px 5px rgba(0, 0, 0, 0.1);
        padding: 0 0 20px;
        margin-top: 20px;
  
        img {
          width: 100%;
        }
  
        h3 {
          color: #333;
          text-align: center;
          font-family: Montserrat;
          font-size: 16px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px; /* 125% */
          text-transform: uppercase;
          margin: 19px 0 4px 0;
        }
  
        p {
          color: #333;
          text-align: center;
          font-family: Vollkorn;
          font-size: 14px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px; /* 142.857% */
        }
  
        &:hover {
          box-shadow: 0 5px 10px rgba(0, 0, 0, 0.525);
        }
      }
    }
  }
  
  @media (min-width: 768px) and (max-width: 992px) {
    .main_wrapper {
      width: 85%;
    }
  
    .main_content_box {
      padding: 0 0 10px !important;
  
      h3 {
        margin: 8px 0 4px 0 !important;
        font-size: 14px !important;
      }
      p {
        font-size: 12px;
      }
    }
  }
  
  @media (min-width: 576px) and (max-width: 768px) {
    .main_wrapper {
      width: 85%;
    }
  
    h2 {
      font-size: 21px !important;
    }
    .main_content_box {
      width: 47% !important;
      h3 {
        margin: 8px 0 4px 0 !important;
        font-size: 16px !important;
      }
      p {
        font-size: 12px !important;
      }
    }
  }
  
  @media (max-width: 576px) {
    .main_wrapper {
      width: 85%;
    }
  
    h2 {
      font-size: 21px !important;
    }
  
    .main_content_box {
      width: 48% !important;
      h3 {
        margin: 8px 0 4px 0 !important;
        font-size: 16px !important;
      }
      p {
        font-size: 12px !important;
      }
    }
  }
  </style>