<template>
  <div class="homepage">
    <v-header :all="false"></v-header>
    <section class="main">
      <ul class="nav">
        <router-link tag="li" to="info">
          <svg
            t="1597933689079"
            class="icon"
            viewBox="0 0 1024 1024"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            p-id="1901"
          >
            <path
              d="M503.6032 304.5376m-194.56 0a194.56 194.56 0 1 0 389.12 0 194.56 194.56 0 1 0-389.12 0Z"
              p-id="1902"
            />
            <path
              d="M587.4688 519.2704H425.3696c-155.0848 0-281.2928 126.1568-281.2928 281.2928v57.4976c0 28.2112 22.9888 51.2 51.2 51.2h622.2336c28.2112 0 51.2-22.9888 51.2-51.2v-57.4976c0.0512-155.136-126.1568-281.2928-281.2416-281.2928z"
              p-id="1903"
            />
          </svg>
        </router-link>

        <router-link tag="li" to="collect">
          <svg
            t="1597933900471"
            class="icon"
            viewBox="0 0 1024 1024"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            p-id="3945"
          >
            <path
              d="M786.92352 1001.588736c-11.065344 0-23.977984-3.688448-35.047424-9.222144l-239.822848-119.914496-241.668096 119.914496c-23.98208 12.91264-55.345152 11.06944-77.479936-5.537792-22.13888-16.59904-35.053568-46.118912-29.519872-73.78944L213.1968 654.76608l-190.01344-177.1008c-20.291584-20.291584-27.670528-51.652608-20.291584-77.479936 9.224192-27.672576 31.361024-47.96416 60.878848-51.654656l263.806976-47.96416L445.642752 60.74368c12.914688-25.827328 38.742016-42.430464 66.412544-42.430464 27.670528 0 55.343104 16.603136 66.412544 42.430464l118.065152 239.822848 263.806976 46.12096c27.670528 3.688448 51.654656 23.98208 59.0336 51.652608 9.222144 27.672576 1.841152 57.188352-18.448384 77.481984l-190.015488 178.944 47.96416 258.271232c5.533696 29.515776-7.378944 57.1904-29.515776 73.78944-11.06944 9.22624-25.827328 14.761984-42.43456 14.761984z"
              p-id="3946"
            />
          </svg>
        </router-link>
        <router-link tag="li" to="record">
          <svg
            t="1597933763155"
            class="icon"
            viewBox="0 0 1024 1024"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            p-id="2048"
          >
            <path d="M315.904 350.6688h391.936v78.2336H315.904z" p-id="2049" />
            <path
              d="M647.168 111.872H211.2512c-28.2112 0-51.2 22.9888-51.2 51.2v693.9136c0 28.2112 22.9888 51.2 51.2 51.2H812.544c28.2112 0 51.2-22.9888 51.2-51.2V328.448c0-119.4496-97.1264-216.576-216.576-216.576z m111.9232 577.1776c0 25.3952-20.6848 46.08-46.08 46.08H310.784c-25.3952 0-46.08-20.6848-46.08-46.08V600.576c0-25.3952 20.6848-46.08 46.08-46.08h402.176c25.3952 0 46.08 20.6848 46.08 46.08v88.4736z m0-255.0272c0 25.3952-20.6848 46.08-46.08 46.08H310.784c-25.3952 0-46.08-20.6848-46.08-46.08V345.5488c0-25.3952 20.6848-46.08 46.08-46.08h402.176c25.3952 0 46.08 20.6848 46.08 46.08v88.4736z"
              p-id="2050"
            />
            <path d="M315.904 605.7472h391.936v78.2336H315.904z" p-id="2051" />
          </svg>
        </router-link>
        <router-link tag="li" to="comment">
          <svg
            t="1597933779986"
            class="icon"
            viewBox="0 0 1024 1024"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            p-id="2196"
          >
            <path
              d="M778.3424 232.0384C705.024 157.696 607.232 115.9168 502.9376 114.3808c-1.9968-0.0512-3.9424-0.0512-5.888-0.0512-212.736 0-389.4272 171.2128-395.1616 384.3072-2.3552 86.5792 22.8352 169.472 72.7552 239.7184 16.64 23.3984-0.2048 69.2224-13.7728 106.0352l-1.6384 4.4544c-4.8128 13.1584-3.072 27.1872 4.864 38.5536 8.2432 11.8272 22.0672 18.8928 36.9664 18.8928 47.4112 0 115.0464-0.4608 174.7456-0.8704 48.7936-0.3072 94.8736-0.6656 121.1392-0.6656 217.9072 0 395.2128-177.3056 395.2128-395.2128 0-104.4992-40.3968-203.0592-113.8176-277.504z m-199.8848 407.552H308.224c-14.1312 0-25.6-11.4688-25.6-25.6s11.4688-25.6 25.6-25.6h270.2848c14.1312 0 25.6 11.4688 25.6 25.6s-11.52 25.6-25.6512 25.6z m107.1616-175.9744H308.224c-14.1312 0-25.6-11.4688-25.6-25.6s11.4688-25.6 25.6-25.6h377.4464c14.1312 0 25.6 11.4688 25.6 25.6s-11.4688 25.6-25.6512 25.6z"
              p-id="2197"
            />
          </svg>
        </router-link>
        <router-link tag="li" to="like">
          <svg
            t="1597933853761"
            class="icon"
            viewBox="0 0 1024 1024"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            p-id="3220"
          >
            <path
              d="M927.3 413v12.3c-1.3 2.3-3.4 4.5-3.9 7.1-23.8 114.3-47.5 228.5-71.1 342.8-3.2 15.3-6.4 30.6-8.9 46-6.8 42-33.2 65.2-72.2 76.8H352c0.1-75.2 0.2-150.4 0.2-225.6 0-108.7 0.2-217.4-0.3-326.1-0.1-14.3 3.3-22.6 18.4-26.1 19-4.4 34.2-16 48.1-29.7 28.1-27.8 38.7-61.9 37.4-100.4-1.1-32.4 9.4-59.8 32.4-83.1 18.2-18.5 42-23.6 65.1-30.9h12.3c2.3 1.3 4.5 3.4 7 3.9 39.8 7.3 66.5 30.6 80.1 68 19.2 52.8 18.3 107.1 5.3 160.9-4.2 17.3 0.6 19.5 15.7 19.4 53.3-0.6 106.6-0.1 160-0.3 25.8-0.1 47.3 8.9 66.2 27 17.1 16.1 20.4 37.7 27.4 58zM105.4 392.4c6.6-6.9 4.8-16.8 9-24.7 13.3-25 32.8-39.6 61.8-39.8 27.4-0.1 54.8 1 82.1-0.4 16.4-0.9 18.9 5.6 18.8 20.1-0.4 174.6-0.3 349.1-0.2 523.7 0 8.9 0.7 17.7 1.1 26.6H171.2c-20.4-8.3-42.8-13.8-53.4-36.3-4.5-9.6-8.2-19.6-12.3-29.4-0.1-146.6-0.1-293.2-0.1-439.8z"
              p-id="3221"
            />
          </svg>
        </router-link>
      </ul>
      <router-view></router-view>
    </section>
  </div>
</template>
<script>
import Header from "@/components/Header.vue";
import { message } from "ant-design-vue";
export default {
  components: {
    "v-header": Header
  },
  created() {
    if (!this._utils.getLocalStorage("userInfo")) {
      message.warning("请登陆后再试！");
      this.$router.push("/sign/login");
    }
  }
};
</script>
<style lang="less" scoped>
.icon {
  fill: #fff;
  width: 50px;
  transform: translateY(5px);
  transition: all 200ms ease-in-out;
  &:hover {
    fill: @hover-color;
    width: 60px;
    transform: none;
  }
}
.main {
  width: 1058px;
  height: 800px;
  margin: 48px auto;
  position: relative;
  box-shadow: 2px 5px 20px rgba(@light-color, 0.5);
  .nav {
    color: #fff;
    box-shadow: 2px 5px 20px rgba(@light-color, 0.5);
    position: absolute;
    left: 50px;
    top: -24px;
    width: 130px;
    height: 848px;
    background-color: black;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    li {
      width: 60px;
      height: 60px;
      text-align: center;
    }
  }
}
</style>
