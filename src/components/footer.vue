<template>
    <div class="footer_component">
      <div class="footer_wrap">
        <form action="#">
          <input placeholder="Name" type="text" class="input_line input_odd" />
          <input placeholder="Email" type="text" class="input_line" />
          <input placeholder="Budget" type="text" class="input_line input_odd" />
          <textarea placeholder="Describe youre project..."></textarea>
        </form>
  
        <button class="button_footer">Send Message</button>
        <img class="under_logo" src="../assets/image/IMAGE.png" alt="" />
  
        <span class="last_one"
          >Minimal Template made in Webflow. All rights reserved.</span
        >
      </div>
    </div>
  </template>
  
  <script setup></script>
  
  <style lang="scss" scoped>
  * {
    padding: 0;
    margin: 0;
  }
  
  .footer_component {
    background-color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 126px 0 70px;
  
    .footer_wrap {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 940px;
      flex-direction: column;
  
      button {
        margin: 25px 0 40px 0;
        width: 210px;
        height: 56px;
        background-color: transparent;
        color: white;
        border: 1.5px solid #7ec4bd;
        transition: all 0.2s linear;
        color: #8bcac3;
        text-align: center;
        font-family: Vollkorn;
        font-size: 17px;
        font-style: italic;
        font-weight: 400;
        line-height: 22px; /* 129.412% */
  
        &:hover {
          border-radius: 15px;
          font-weight: 700;
        }
      }
  
      .last_one {
        margin-top: 20px;
        color: rgba(255, 255, 255, 0.4);
        text-align: center;
        font-family: Vollkorn;
        font-size: 15px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px;
      }
    }
  
    .footer_wrap form {
      width: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
  
      input,
      textarea {
        background: rgba(255, 255, 255, 0.18);
        height: 57px;
        flex-shrink: 0;
        border: none;
        width: 60%;
        color: #fff;
        padding: 18px 31px;
      }
  
      .input_odd {
        background: rgba(153, 153, 153, 0.349);
      }
    }
  
    input::placeholder,
    textarea::placeholder {
      color: #fff;
      font-family: Vollkorn;
      font-size: 17px;
      font-style: italic;
      font-weight: 400;
      line-height: 22px;
    }
  
    textarea {
      resize: none;
      height: 127px !important;
    }
  }
  
  @media (min-width: 768px) and (max-width: 992px) {
    .footer_wrap {
      width: 85% !important;
    }
  }
  
  @media (min-width: 576px) and (max-width: 768px) {
    .footer_wrap {
      width: 85% !important;
    }
  
    .footer_wrap form {
      input,
      textarea {
        height: 30px;
        flex-shrink: 0;
        border: none;
        width: 60% !important;
        color: #fff;
        padding: 18px 31px;
      }
  
      .input_odd {
        background: rgba(153, 153, 153, 0.349);
      }
    }
  }
  
  @media (max-width: 576px) {
    .footer_wrap {
      width: 85% !important;
    }
  
    .footer_wrap form {
      input,
      textarea {
        font-size: 16px !important;
        height: 16px !important;
        flex-shrink: 0;
        border: none;
        width: 70% !important;
        color: #fff;
        padding: 18px 31px;
      }
      textarea {
        height: 80px !important;
  
        button {
          width: 100px;
        }
      }
  
      .input_odd {
        background: rgba(153, 153, 153, 0.349);
      }
    }
  
    .last_one {
      font-size: 12px !important;
    }
  
    .footer_component {
      padding: 80px 0 70px !important;
    }
  
    button {
      margin: 25px 0 40px 0;
      width: 150px !important;
      height: 35px;
      font-size: 16px !important;
    }
  
    input::placeholder,
    textarea::placeholder {
      color: #fff;
      font-family: Vollkorn;
      font-size: 13px !important;
      font-style: italic;
      font-weight: 400;
      line-height: 22px;
    }
  }
  </style>