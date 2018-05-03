<template>
  <div>
    <my-header></my-header>
    <div class="container index">
          <div class="row">
              <div class="aside">
                  <div class="row">
                      <div class="follow-title">
                          <v-popover>
                                <a href="#">
                                    全部关注
                                    <i class="fa fa-chevron-circle-down"></i>
                                </a>
                                <template slot="popover">
                                    <ul class="dropdown-menu arrow-top">
                                        <li><a href="#">全部关注</a></li>
                                        <li><a href="#">只看作者</a></li>
                                        <li><a href="#">只看专题</a></li>
                                        <li><a href="#">只看文集</a></li>
                                        <li><a href="#">只看推送更新</a></li>
                                    </ul>
                                </template>
                          </v-popover>
                          <nuxt-link to="" class="add-people">
                              <i class="fa fa-user-plus"></i>
                              添加关注
                          </nuxt-link>                      
                      </div>
                      <ul class="follow-list">
                          <li>
                              <nuxt-link to="/u/123" class="active">
                                  <div class="avatar">
                                      <img src="~/assets/img/jyq.png" alt="">
                                  </div>
                                  <div class="name">简友圈</div>
                              </nuxt-link>
                          </li>
                          <li>
                              <nuxt-link to="">
                                  <div class="avatar">
                                      <img src="~/assets/img/default-avatar.jpg" alt="">
                                  </div>
                                  <div class="name">简书用户</div>
                              </nuxt-link>
                          </li>
                          <li>
                              <nuxt-link to="">
                                  <div class="avatar">
                                      <img src="~/assets/img/default-avatar.jpg" alt="">
                                  </div>
                                  <div class="name">简书用户</div>
                              </nuxt-link>
                          </li>
                      </ul>
                  </div>
              </div>
              <div class="col-xs-16 main">
                  <!-- 文章列表 -->
                  <div class="list-container">
                        <ul class="note-list">
                            <li class="have-img">
                                <nuxt-link to="/p/123" class="wrap-img">
                                    <img src="~/assets/img/note.png">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123" class="avatar">
                                            <img src="~/assets/img/default-avatar.jpg">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="/u/123" class="nickname">测试用户</nuxt-link>
                                            <span class="time">
                                                04.12 10:18
                                            </span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">佛系程序员的月薪五万指南</nuxt-link>
                                    <div class="abstruct">
                                        摘要：大师：很简单，我这里有一份佛系月薪 5 万指南，我看你骨骼清奇、脑门光亮，一看就是将要大富大贵之人，这份指南可以助你快速实现小目标！ 程序员问大师…… 青年：大师，你看...
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                            <i class="fa fa-heart"></i>
                                            20
                                        </span>
                                    </div>
                                </div>
                            </li>
                            <li>
                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123" class="avatar">
                                            <img src="~/assets/img/default-avatar.jpg">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="/u/123" class="nickname">测试用户</nuxt-link>
                                            <span class="time">
                                                04.12 10:18
                                            </span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">佛系程序员的月薪五万指南</nuxt-link>
                                    <div class="abstruct">
                                        摘要：大师：很简单，我这里有一份佛系月薪 5 万指南，我看你骨骼清奇、脑门光亮，一看就是将要大富大贵之人，这份指南可以助你快速实现小目标！ 程序员问大师…… 青年：大师，你看...
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                            <i class="fa fa-heart"></i>
                                            20
                                        </span>
                                    </div>
                                </div>
                            </li>
                            <li class="have-img">
                                <nuxt-link to="/p/123" class="wrap-img">
                                    <img src="~/assets/img/note.png">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123" class="avatar">
                                            <img src="~/assets/img/default-avatar.jpg">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="/u/123" class="nickname">测试用户</nuxt-link>
                                            <span class="time">
                                                04.12 10:18
                                            </span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">佛系程序员的月薪五万指南</nuxt-link>
                                    <div class="abstruct">
                                        摘要：大师：很简单，我这里有一份佛系月薪 5 万指南，我看你骨骼清奇、脑门光亮，一看就是将要大富大贵之人，这份指南可以助你快速实现小目标！ 程序员问大师…… 青年：大师，你看...
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                            <i class="fa fa-heart"></i>
                                            20
                                        </span>
                                    </div>
                                </div>
                            </li>
                            <li>
                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123" class="avatar">
                                            <img src="~/assets/img/default-avatar.jpg">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="/u/123" class="nickname">测试用户</nuxt-link>
                                            <span class="time">
                                                04.12 10:18
                                            </span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">佛系程序员的月薪五万指南</nuxt-link>
                                    <div class="abstruct">
                                        摘要：大师：很简单，我这里有一份佛系月薪 5 万指南，我看你骨骼清奇、脑门光亮，一看就是将要大富大贵之人，这份指南可以助你快速实现小目标！ 程序员问大师…… 青年：大师，你看...
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                            <i class="fa fa-heart"></i>
                                            20
                                        </span>
                                    </div>
                                </div>
                            </li>
                        </ul>
                  </div>
                  <a href="#" class="load-more">阅读更多</a>
              </div>
              
          </div>
      </div>
  </div>
</template>
<script>
import myHeader from "../components/myHeader";
import Vue from "vue";
import VTooltip from "v-tooltip";
Vue.use(VTooltip);
export default {
  head: {
    title: "关注-简书",
    meta: [
      { charset: "utf-8" },
      { name: "keywords", content: "关注页面" },
      { name: "description", content: "关注页面" },
      { name: "author", content: "杨珊珊" }
    ]
  },
  components: {
    myHeader
  },
  data() {
    return {
      name: "关注"
    };
  }
};
</script>
<style scoped>
.aside {
  position: fixed;
  top: 0;
  bottom: 0;
  margin: 86px 0 0;
  overflow: auto;
  border-right: 1px solid #f0f0f0;
  width: 280px;
}
.aside .row{
    width: 100%;
    margin: 0;
}
.main {
  margin-left: 34%;
}
.follow-title {
  display: flex;
  justify-content: space-between;
  font-size: 14px;
}
.follow-title a {
  margin-left: 15px;
}
.add-people {
  margin: 0 10px 0 0;
  font-size: 13px;
}
.follow-list{
    width: 100%;
}
.follow-list li {
  width: 100%;
  line-height: 20px;
  font-size: 17px;
  color: #333;
  margin: 0;
  padding: 0;
}
.follow-list li a {
    width: 100%;
  padding: 10px 13px;
  display: block;
  background-color: transparent;
}
.follow-list li a.active {
  background-color: #f0f0f0;
}
.follow-list li a:hover {
  background-color: #f0f0f0 !important;
}
.follow-list li a div {
  display: inline-block;
}
.follow-list li a .avatar {
  width: 40px;
  height: 40px;
  vertical-align: middle;
  display: inline-block;
  margin-right: 4px;
}
.follow-list li a .avatar img {
  width: 100%;
  height: 100%;
}
.follow-list li a .name {
  font-size: 14px;
  vertical-align: middle;
  display: inline-block;
  overflow: hidden;
  white-space: nowrap;
}
.arrow-top {
  background: #fff;
  top: 23px;
  left: 20px;
  min-width: 130px;
  text-align: center;
  border-color: transparent;
  font-size: 14px;
  margin: 0;
}
.arrow-top a {
  padding: 10px 20px;
}
.arrow-top li > a {
  display: block;
  clear: both;
  font-weight: 400;
  line-height: 1.42857;
  color: #333;
}
.arrow-top li a:hover {
  background-color: #f5f5f5;
}
</style>
