<template>
    <div class="pre_footer_component" id="contact">
      <img
        class="pre_footer_component_img"
        src="../assets/image/fon.png"
        alt=""
      />
      <div class="pre_footer_wrapper">
        <h2 class="pre_footer_title">LET’s Get in touch</h2>
        <div class="hr"></div>
        <hr />
        <div class="pre_footer_content_boxes">
          <div class="pre_footer_content_box">
            <img src="../assets/image/location.png" alt="" />
            <h3>MEET US IN PERSON</h3>
            <span>8776 Juniper Street</span>
            <span>Unit #204</span>
            <span>Merriweather, Ontario</span>
            <span>Canada</span>
          </div>
  
          <div class="pre_footer_content_box">
            <img src="../assets/image/big_email.png" alt="" />
            <h3>Email us</h3>
            <span>contact@minimal.com</span>
            <span class="seperator_email">Contact form</span>
            <span>Merriweather, Ontario</span>
            <span>Scroll down</span>
          </div>
  
          <div class="pre_footer_content_box">
            <img src="../assets/image/like.png" alt="" />
            <h3>Let’s get social</h3>
            <div class="pre_footer_content_box_social">
              <img src="../assets/image/facebook.png" alt="" />
              <span>Instagram</span>
            </div>
            <div class="pre_footer_content_box_social">
              <img src="../assets/image/in.png" alt="" />
              <span>Twitter</span>
            </div>
            <div class="pre_footer_content_box_social">
              <img src="../assets/image/twiter.png" alt="" />
              linkdin
            </div>
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
  
  .pre_footer_component_img {
    width: 100%;
  }
  .pre_footer_component {
    position: relative;
    width: 100%;
    max-width: 1600px;
    margin: 0 auto;
    margin-bottom: -10px;
  }
  .pre_footer_wrapper {
    background-color: rgba(0, 0, 0, 0.372);
    top: 10px;
    position: absolute;
    bottom: 50%;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 940px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  
    hr {
      width: 80px;
      height: 2px;
      flex-shrink: 0;
      background: rgba(0, 0, 0, 0.09);
      border: none;
      margin: 28px 0 42px 0;
    }
  
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
  }
  
  .pre_footer_content_boxes {
    display: flex;
    width: 100%;
    justify-content: space-between;
    align-items: flex-start;
    .pre_footer_content_box {
      display: flex;
      flex-direction: column;
      width: 33%;
      justify-content: center;
      align-items: center;
      gap: 3px;
  
      h3 {
        color: #333;
        text-align: center;
        font-family: Montserrat;
        font-size: 16px;
        font-style: normal;
        font-weight: 500;
        line-height: 20px; /* 125% */
        text-transform: uppercase;
        margin: 26px 0 20px 0;
      }
  
      span {
        color: #212121;
        text-align: center;
        font-family: Vollkorn;
        font-size: 17px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px; /* 129.412% */
      }
    }
  }
  
  .pre_footer_content_box_social {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 9px;
  }
  
  .seperator_email {
    margin-bottom: 15px;
  }
  
  @media (min-width: 768px) and (max-width: 992px) {
    .pre_footer_component_img {
      width: 100%;
      height: 400px;
    }
    .pre_footer_wrapper {
      width: 85%;
      img {
        width: 18%;
      }
  
      h2 {
        font-size: 20px !important;
      }
  
      hr {
        margin: 14px 0 15px 0;
      }
  
      h3 {
        font-size: 14px !important;
        margin: 13px 0 10px 0 !important;
      }
  
      span {
        font-size: 14px Im !important;
      }
    }
  }
  
  @media (min-width: 576px) and (max-width: 768px) {
    .pre_footer_component_img {
      width: 100%;
      height: 350px !important;
    }
    .pre_footer_wrapper {
      width: 85%;
      img {
        width: 18%;
      }
  
      h2 {
        font-size: 18px !important;
      }
  
      hr {
        margin: 14px 0 15px 0;
      }
  
      h3 {
        font-size: 12px !important;
        margin: 13px 0 10px 0 !important;
      }
  
      span {
        font-size: 12px !important;
      }
    }
  }
  
  @media (max-width: 576px) {
    .pre_footer_component_img {
      width: 100%;
      height: 350px !important;
    }
    .pre_footer_wrapper {
      width: 85%;
      img {
        width: 18%;
      }
  
      h2 {
        font-size: 18px !important;
      }
  
      hr {
        margin: 14px 0 15px 0;
      }
  
      h3 {
        font-size: 10px !important;
        margin: 13px 0 10px 0 !important;
      }
  
      span {
        font-size: 10px !important;
      }
    }
    .pre_footer_content_box {
      div {
        img {
          width: 30%;
        }
      }
    }
  }
  </style>