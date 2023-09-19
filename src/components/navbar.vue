<template>
  <div class="navbar_wrapper">
    <div class="navbar_logo_side">
      <div class="navbar_logo_side_img">
        <img src="../assets/image/IMAGE.png" alt="logo" />
      </div>

      <div class="navbar_logo_side_name">
        <p>Minimal</p>
      </div>
    </div>

    <div class="navbar_nav_direction_side">
      <ul class="block-ul">
        <li><a href="#process">Process</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#team">Team</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>

      <div class="ul_hidden">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          height="1em"
          viewBox="0 0 448 512"
        >
          <path
            d="M0 96C0 78.3 14.3 64 32 64H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32H416c17.7 0 32 14.3 32 32z"
          />
        </svg>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.ul_hidden {
  display: none;
}
.navbar_wrapper {
  width: 940px;
  height: 106px;
  margin: 0 auto;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.navbar_logo_side {
  display: flex;
  flex-direction: row;
  align-items: center;
}
.navbar_logo_side_name {
  color: #333;
  margin-left: 18px;
  font-family: Oswald;
  font-size: 22px;
  font-style: normal;
  font-weight: 400;
  line-height: 38px;
  text-transform: uppercase;
}

.navbar_nav_direction_side {
  width: 324px;

  ul {
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    gap: 34px;

    li {
      border: 1px solid transparent;
      padding: 5px 9px;
      transition: all 0.3s ease-in;

      a {
        color: #404040;
        font-family: Montserrat;
        font-size: 12px;
        font-style: normal;
        font-weight: 400;
        line-height: 20px;
        text-transform: uppercase;
      }

      &:hover {
        background-color: #7ec4bd;
        border-radius: 5px;
        border: 1px solid #004a4a;
        a {
          color: black;
          font-weight: 700;
        }
      }
    }
  }
}

@media (min-width: 768px) and (max-width: 992px) {
  .navbar_wrapper {
    width: 85%;
    height: 80px;

    img {
      width: 75%;
    }
  }
  .navbar_logo_side_name {
    font-size: 18px;
    margin-left: 0;
  }

  .navbar_nav_direction_side {
    width: fit-content;

    ul {
      gap: 18px;

      li {
        a {
          font-size: 11px;
        }
      }
    }
  }
}

@media (min-width: 576px) and (max-width: 768px) {
  .ul_hidden {
    display: block;
    svg {
      font-size: 30px !important;
    }
  }

  .block-ul {
    display: none !important;
  }
  .navbar_wrapper {
    width: 85%;
    height: 80px;

    img {
      width: 75%;
    }
  }
  .navbar_logo_side_name {
    font-size: 25px;
    margin-left: 0;
  }

  .navbar_nav_direction_side {
    width: fit-content;

    ul {
      gap: 18px;

      li {
        a {
          font-size: 11px;
        }
      }
    }
  }
}

@media (max-width: 576px) {
  .ul_hidden {
    display: block;
    svg {
      font-size: 30px !important;
    }
  }

  .block-ul {
    display: none !important;
  }
  .navbar_wrapper {
    width: 85%;
    height: 80px;

    img {
      width: 75%;
    }
  }
  .navbar_logo_side_name {
    font-size: 20 px;
    margin-left: 0;
  }

  .navbar_nav_direction_side {
    width: fit-content;

    ul {
      gap: 18px;

      li {
        a {
          font-size: 11px;
        }
      }
    }
  }
}
</style>