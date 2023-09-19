<template>
  <div class="info_component">
    <div class="info_component_wrapper">
      <h2>How we make brands thrive</h2>

      <hr />

      <div class="info_component_content_boxes">
        <div class="info_component_content_box">
          <div class="info_component_content_box_image_back">
            <img src="../assets/image/imgplus.png" alt="circle" />
          </div>

          <h3>SET a target</h3>

          <span
            >Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Suspendisse varius enim in eros elementum tristique.</span
          >
        </div>

        <div class="info_component_content_box">
          <div class="info_component_content_box_image_back">
            <img src="../assets/image/height.png" alt="circle" />
          </div>

          <h3>design a solution</h3>

          <span
            >Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut
            commodo diam libero vitae erat.</span
          >
        </div>

        <div class="info_component_content_box">
          <div class="info_component_content_box_image_back">
            <img src="../assets/image/diagramma.png" alt="circle" />
          </div>

          <h3>track the progress</h3>

          <span
            >Aenean faucibus nibh et justo cursus id rutrum lorem imperdiet.
            Nunc ut sem vitae risus tristique posuere.</span
          >
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

.info_component_wrapper {
  width: 940px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  padding: 70px 0;
  align-items: center;
  justify-content: center;

  hr {
    background: rgba(0, 0, 0, 0.09);
    border: none;
    width: 80px;
    height: 2px;
    flex-shrink: 0;
    margin: 28px 0 45px 0;
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

  .info_component_content_boxes {
    display: flex;
    width: 100%;
    justify-content: space-between;
    align-items: flex-start;
    .info_component_content_box {
      width: 30%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 8px;
      transition: box-shadow 0.5s ease;
      &:hover {
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
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
        margin: 38px 0 20px 0;
      }

      span {
        color: #333;
        text-align: center;
        font-family: Vollkorn;
        font-size: 15px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px; /* 146.667% */
      }
    }
  }
  .info_component_content_box_image_back {
    background-color: #f5f5f5;
    img {
      width: 100%;
      padding: 50px 87px;
    }
  }
}

@media (min-width: 768px) and (max-width: 992px) {
  .info_component_wrapper {
    width: 85%;
  }

  h2 {
    font-size: 20px;
  }

  .info_component_content_boxes {
    .info_component_content_box {
      h3 {
        font-size: 14px !important;
        margin: 20px 0 10px 0 !important;
      }

      span {
        font-size: 13px !important;
      }
    }
  }

  .info_component_content_box_image_back {
    img {
      width: 100%;
      padding: 25px 40px !important;
    }
  }
}

@media (min-width: 576px) and (max-width: 768px) {
  .info_component_wrapper {
    width: 85%;
  }

  h2 {
    font-size: 18px !important;
  }

  .info_component_content_boxes {
    flex-wrap: wrap;
    .info_component_content_box {
      margin-top: 20px;
      width: 45% !important ;
      padding: 0px !important;
      h3 {
        font-size: 15px !important;
        margin: 15px 0 8px 0 !important;
      }

      span {
        font-size: 12px !important;
      }
    }
  }

  .info_component_content_box_image_back {
    img {
      width: 100%;
      padding: 33px 70px !important;
    }
  }
}

@media (max-width: 576px) {
  .info_component_wrapper {
    width: 85%;
  }

  h2 {
    font-size: 18px !important;
  }

  .info_component_content_boxes {
    flex-wrap: wrap;
    .info_component_content_box {
      margin-top: 30px;
      width: 90% !important ;
      padding: 0px 0px 0px 10px !important;

      h3 {
        font-size: 15px !important;
        margin: 15px 0 8px 0 !important;
      }

      span {
        font-size: 12px !important;
      }
    }
  }

  .info_component_content_box_image_back {
    img {
      width: 100%;
      padding: 33px 70px !important;
    }
  }
}
</style>