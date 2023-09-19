<template>
    <div class="team_component" id="team">
      <div class="team_wrapper">
        <h2 class="team_wrapper_header">Our Team</h2>
  
        <hr />
  
        <div class="team_content_boxes">
          <div class="team_content_box">
            <img src="../assets/image/person.png" alt="person" />
  
            <h2>Ron Swanson</h2>
  
            <p>Founder</p>
  
            <div class="social">
              <img src="../assets/image/twiter.png" alt="" />
              <img src="../assets/image/in.png" alt="" />
              <img src="../assets/image/email.png" alt="" />
            </div>
          </div>
  
          <div class="team_content_box">
            <img src="../assets/image/person_2.png" alt="person" />
  
            <h2>Julia Depish</h2>
  
            <p>Marketing</p>
  
            <div class="social">
                <img src="../assets/image/twiter.png" alt="" />
                <img src="../assets/image/in.png" alt="" />
                <img src="../assets/image/email.png" alt="" />
            </div>
          </div>
  
          <div class="team_content_box">
            <img src="../assets/image/person_3.png" alt="person" />
  
            <h2>Danny Devry</h2>
  
            <p>Designer</p>
  
            <div class="social">
              <img src="../assets/image/instagram.png" alt="" />
              <img src="../assets/image/twiter.png" alt="" />
              <img src="../assets/image/be.png" alt="" />
              <img src="../assets/image/ball.png" alt="" />
              <img src="../assets/image/email.png" alt="" />
            </div>
          </div>
  
          <div class="team_content_box">
            <img src="../assets/image/person_4.png" alt="person" />
  
            <h2>Lisa Smith</h2>
  
            <p>Developer</p>
  
            <div class="social">
                <img src="../assets/image/twiter.png" alt="" />

                <img src="../assets/image/in.png" alt="" />
                
                <img src="../assets/image/email.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup></script>
  
  <style lang="scss" scoped>
  .team_component {
    width: 100%;
    padding: 70px 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .team_wrapper {
    width: 940px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  
    .team_content_boxes {
      display: flex;
      width: 100%;
      justify-content: space-between;
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
  
    hr {
      width: 80px;
      height: 2px;
      flex-shrink: 0;
      background: rgba(0, 0, 0, 0.09);
      border: none;
      margin: 28px 0 43px;
    }
  }
  
  .team_content_box {
    transition: all 0.5 linear;
  
    display: flex;
    width: 23.5%;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  
    h2 {
      margin: 20px 0 6px 0;
    }
  
    .social {
      margin-top: 17px;
      display: flex;
      gap: 13px;
    }
    transition: all 0.5 linear;
  
    img {
      width: 100%;
      transition: all 0.2s linear;
      &:hover {
        box-shadow: 0 0.3px 10px rgba(0, 0, 0, 0.525);
      }
    }
  }
  
  @media (min-width: 768px) and (max-width: 992px) {
    .team_wrapper {
      width: 85%;
  
      h2 {
        font-size: 17px;
      }
    }
  }
  
  @media (min-width: 576px) and (max-width: 768px) {
    .team_wrapper {
      width: 85%;
    }
  
    h2 {
      font-size: 17px !important;
    }
  
    p {
      font-size: 14px !important;
    }
  
    .team_content_boxes {
      flex-wrap: wrap !important;
      .team_content_box {
        width: 47%;
        margin-top: 25px;
      }
    }
  }
  
  @media (max-width: 576px) {
    .team_wrapper {
      width: 85%;
    }
  
    p {
      font-size: 12px !important;
    }
  
    .team_content_boxes {
      flex-wrap: wrap !important;
      .team_content_box {
        width: 47%;
        margin-top: 25px;
  
        h2 {
          font-size: 17px !important;
        }
      }
    }
  }
  </style>