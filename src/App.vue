<template>
  <div id="app" class="app">
    <page :currentPage="currentPage">
      <h1 class="text-center">欢迎</h1>
      <section class="animate" ref="section1">

      </section>
    </page>
    <page :currentPage="currentPage">
      <section class="animate move-left">
        <div class="container">
          <div class="row">
            <div class="col-md-5">
              <img src="./assets/avatar.png" class="img-fluid" alt="photo" style="display:block;margin: 0 auto">
            </div>
            <div class="col-md-7"><h1 class="text-center">陈 川</h1>
              <table class="table">
                <tbody>
                <tr>
                  <th scope="row">性别</th>
                  <td>女</td>
                </tr>
                <tr>
                  <th scope="row">出生</th>
                  <td>1998/1</td>
                </tr>
                <tr>
                  <th scope="row">学历</th>
                  <td>大专</td>
                </tr>
                <tr>
                  <th scope="row">手机</th>
                  <td>173.......</td>
                </tr>
                <tr>
                  <th scope="row">邮箱</th>
                  <td>？？？？？@qq.com</td>
                </tr><tr>
                  <th scope="row">Github</th>
                  <td>
                    <a href="https://github.com/chenchuan123">
                      <img src="./assets/GitHub.png" alt=""  width="50px" height="50px">@BurNing1993</a>
                  </td>
                </tr>

                </tbody>
              </table>
            </div>
          </div>
        </div>
      </section>
    </page>
    <!-- <page :currentPage="currentPage">
      <h1 class="text-center">工作经历</h1>
      <section class="animate move-left">
        <h4>成都谢尔科技有限公司</h4>
        <h5>2016/03 - 2018/01</h5>
        <h5>Java开发工程师</h5>
        <p>
          工作描述：JAVA后台开发工程师，在公司主要是从事JAVA WEB开发，前端页面编写和后台接口开发。
        </p>
      </section>
    </page> -->
    <!-- <page :currentPage="currentPage">
      <h1 class="text-center">项目经验</h1>
      <section class="animate move-left">
        <div class="container">
          <div class="row">
            <div class="col-md-6">
              <h5>eSimple项目管理系统</h5>
              <h6>2017/4至今</h6>
              <p>
                项目简介：本系统是对公司的项目的总览和管理系统，
                主要分为项目总览展示和项目管理模块，目的是方便统一查看项目进度，方便项目展示，
                使项目管理更加便捷，系统。项目前端采用JQueryEasyUI，后端采用SSM框架。
              </p>
            </div>
            <div class="col-md-6">
              <h5>餐饮后台管理项目</h5>
              <h6>2016/12至今</h6>
              <p>
                项目简介：本系统是为餐饮工作人员制作的一款后台管理系统，目的是简化用户操作，提高工作效率。
              </p>
            </div>
          </div>
        </div>
      </section>
    </page> -->
    <page :currentPage="currentPage">
      <h1 class="text-center">教育经历</h1>
      <section class="animate move-left">
        2016/09 -- 2019/07 四川华新现代职业学院 汽车检测 统招 大专
        <br>
        2017/05 大学英语四级
        <br>
        英语： 读写能力 良好| 听说能力 一般


      </section>
    </page>
    <page :currentPage="currentPage">
      <h1 class="text-center">专业技能</h1>
      <section class="animate move-left">
        <div>
        <table class="table table-hover">
          <tbody>
          <tr>
            <td rowspan="5">后端</td>
            <td>SpringBoot</td>
            <td>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="25" aria-valuemin="0"
                     aria-valuemax="100">80%
                </div>
              </div>
            </td>
          </tr>
          <tr>
            <td>JAVA</td>
            <td>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="25" aria-valuemin="0"
                     aria-valuemax="100">80%
                </div>
              </div>
            </td>
          </tr>
          <tr>
            <td>Spring</td>
            <td>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="25" aria-valuemin="0"
                     aria-valuemax="100">80%
                </div>
              </div>
            </td>
          </tr>
          <tr>
            <td>mybatis</td>
            <td>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 70%;" aria-valuenow="25" aria-valuemin="0"
                     aria-valuemax="100">70%
                </div>
              </div>
            </td>
          </tr>
          <tr>
            <td>MySQL</td>
            <td>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 70%;" aria-valuenow="25" aria-valuemin="0"
                     aria-valuemax="100">70%
                </div>
              </div>
            </td>
          </tr>
          <tr>
            <td rowspan="3">前端</td>
            <td>VUE</td>
            <td>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="25" aria-valuemin="0"
                     aria-valuemax="100">80%
                </div>
              </div>
            </td>
          </tr>
          <tr>
            <td>JQuery</td>
            <td>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 70%;" aria-valuenow="25" aria-valuemin="0"
                     aria-valuemax="100">70%
                </div>
              </div>
            </td>
          </tr>
          <tr>
            <td>Angular</td>
            <td>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 60%;" aria-valuenow="25" aria-valuemin="0"
                     aria-valuemax="100">60%
                </div>
              </div>
            </td>
          </tr>
          <!-- <tr>
            <td rowspan="2">其他</td>
            <td>IntelliJ IDEA</td>
            <td>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 70%;" aria-valuenow="25" aria-valuemin="0"
                     aria-valuemax="100">70%
                </div>
              </div>
            </td>
          </tr>
          <tr>
            <td>微信小程序</td>
            <td>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 60%;" aria-valuenow="25" aria-valuemin="0"
                     aria-valuemax="100">60%
                </div>
              </div>
            </td>
          </tr> -->
          </tbody>
        </table>
        </div>
      </section>
    </page>
    <page :currentPage="currentPage">
      <section class="animate move-left">
        <h1 class="text-center">谢谢</h1>
      </section>
    </page>
    <page-controller :pageNum="pageNum" :currentPage="currentPage" @changePage="changePage"
                     :option="controllerOption"></page-controller>
  </div>
</template>

<script>
  import Page from './components/Page.vue';
  import PageController from './components/PageController.vue';

  // 页面进出动画
  function afterEnterAnimate($child) {
    $child.$el.querySelector('.animate').classList.remove('move-left', 'move-right');
  }

  function beforeLeaveAnimate($child) {
    let moveType = Math.random() > 0.5 ? 'move-left' : 'move-right';
    $child.$el.querySelector('.animate').classList.add(moveType);
  }

  export default {
    name: 'app',
    data() {
      return {
        currentPage: 1,
        options: [{
          // the color of background
          background: '#000',
          // the color of text
          color: '#fff',
          // is content center
          isCenter: true,
          // the function before page show
          afterEnter: afterEnterAnimate,
          // the function after page show
          beforeLeave: beforeLeaveAnimate
        }, {
          background: '#000',
          color: '#fff',
          isCenter: true,
          afterEnter: afterEnterAnimate,
          beforeLeave: beforeLeaveAnimate
        }, {
          background: '#000',
          color: '#fff',
          isCenter: true,
          afterEnter: afterEnterAnimate,
          beforeLeave: beforeLeaveAnimate
        }, {
          background: '#000',
          color: '#fff',
          isCenter: true,
          afterEnter: afterEnterAnimate,
          beforeLeave: beforeLeaveAnimate
        }, {
          background: '#000',
          color: '#fff',
          isCenter: true,
          afterEnter: afterEnterAnimate,
          beforeLeave: beforeLeaveAnimate
        }],
        controllerOption: {
          arrowsType: false,
          navbar: true,
          highlight: true,
          loop: false
        }
      }
    },
    computed: {
      // 总page数
      pageNum() {
        return this.options.length;
      }
    },
    methods: {
      changePage(index) {
        // beforeLeave Hook
        let beforeIndex = this.currentPage - 1;
        let leaveFunction = this.options[beforeIndex].beforeLeave;
        typeof leaveFunction === 'function' && leaveFunction.call(this, this.$children[beforeIndex]);
        // change page
        this.currentPage = index;
        // afterEnter Hook
        let nextIndex = index - 1;
        let enterFunction = this.options[nextIndex].afterEnter;
        this.$nextTick(function () {
          typeof enterFunction === 'function' && enterFunction.call(this, this.$children[nextIndex]);
        })
      }
    },
    components: {
      Page, PageController
    },
    mounted() {
      this.$children.forEach((child, index) => {
        // 动态设置各个page内的options
        if (child.option === null) {
          let childOption = this.options[index];
          this.$set(childOption, 'index', index + 1);
          child.option = childOption;
        }
      });
    }
  }
</script>

<style>
  html,
  body {
    margin: 0;
    padding: 0;
    height: 100%;
    width: 100%;
    overflow: hidden;
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #fff;
  }

  .app {
    height: 100%;
    width: 100%;
  }

  /* 下面的是与fullPage无关的样式 */

  .animate {
    transition: all 1s ease-out 0s;
  }

  .move-left {
    transform: translateX(-1000%);
  }

  .move-right {
    transform: translateX(1000%);
  }

  @media screen and (max-width: 768px) {
    html,
    body {
      font-size: 12px;
    }
  }

  a {
    text-decoration: none;
    color: inherit;
  }

  a:hover {
    text-decoration: underline;
  }

  .person-img {
    width: 223px;
    height: 185px;
    float: left;
    background-color: #fff;
    box-shadow: 3px 3px 10px #999;
  }

  .person-img img {
    height: 100%;
    width: 100%;
  }

  .person-basic-info {
    overflow: hidden;
    float: right;
    margin-left: 40px;
  }

  .info-line {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
  }

  .text-center {
    text-align: center;
  }

  .text-bold {
    font-weight: bold;
  }

  .demo-intro {
    text-indent: 2em;
  }

  dt {
    font-weight: bold;
    font-size: 16px;
  }

  ul {
    padding-left: 1em;
  }

  .avatar {
    margin: 10px auto;
    display: block;
    box-shadow: 1px 1px 5px #666;
  }

  .author-info {
    text-align: center;
  }
</style>
