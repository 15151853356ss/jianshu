<template>
  <div>
      <my-header></my-header>
      <div class="note">
          <div class="post">
              <!-- 文章正文 -->
              <div class="article">
                  <h1 class="title">别着急，慢慢来，一切都会好的</h1>
                  <div class="author">
                      <div class="avatar">
                          <img src="~/assets/img/default-avatar.jpg" alt="">
                      </div>
                      <div class="info">
                          <nuxt-link class="name" to="name">
                            不会
                          </nuxt-link>
                          <a href="#" class="btn btn-follow">
                              <i class="fa fa-plus"></i>
                              <span>关注</span>
                          </a>
                          <div class="meta">
                              <span class="publish-time">
                                 2018.03.28 06:56*
                              </span>
                              <span class="wordage">
                                  字数 1893
                              </span>
                              <span class="view-count">
                                  阅读 6741
                              </span>
                              <span class="comment-count">
                                  评论 123
                              </span>
                              <span class="like-count">
                                  喜欢 331
                              </span>
                          </div>
                      </div>
                  </div>
                  <div class="show-content">
                      <p>所以人生的路没有错与对，无论我们选择什么，都应该用尽全力去做的更好，而不是去抱怨。将来的你定然会感谢现在拼搏的你，感谢你给他多了一个选择的权力。所以，别着急，慢慢走，生活总会越来越好的。</p>
                  </div>                 
              </div>
              <!-- 底部文章分类信息 -->
              <div class="show-foot">
                    <nuxt-link class="notebook" to="/note/123">
                        <i class="fa fa-book"></i>
                        日记本
                    </nuxt-link>
                    <div class="copyright">
                        © 著作权归作者所有
                    </div>
              </div>
              <!-- 文章底部的作者信息 -->
              <div class="follow-detail">
                  <div class="info">
                      <div class="avatar">
                          <img src="~/assets/img/default-avatar.jpg" alt="">
                      </div>
                      <a href="#" class="btn-follow">
                          <i class="fa fa-plus"></i>
                          <span>关注</span>
                      </a>
                      <nuxt-link to="/u/123" class="title">
                        不会
                      </nuxt-link>
                      <i class="fa fa-venus"></i>
                      <p>
                          写了10.8万字 · 6.4万阅读 · 283人关注
                      </p>
                  </div>
              </div>
              <!-- 更多分享 -->
              <div class="meta-bottom">
                  <div class="like" :class="{'islike':islike}" @click="islike=!islike">
                      <div class="like-btn" >
                          <a href="javascript:void(0)">喜欢</a>
                      </div>
                      <div class="like-num">
                          <a href="#">50</a>
                      </div>
                  </div>
                  <div class="share">
                      <a href="#" class="share-btn">
                          <i class="fa fa-weixin weixin"></i>
                      </a>
                      <a href="#" class="share-btn">
                          <i class="fa fa-weibo weibo"></i>
                      </a>
                      <a href="#" class="share-btn">
                          <i class="fa fa-qq qq"></i>
                      </a>
                      <a href="#" class="share-btn more-share">
                          更多分享
                      </a>
                  </div>
              </div>
              <!-- 留言组件 -->
              <my-comment></my-comment>
              <!--  -->
          </div>
      </div>
  </div>
</template>

<script>
import myHeader from "~/components/myHeader";
import myComment from '~/components/myComment';
export default {
  head: {
    title: "简书文章详情页面-创作你的创作",
    meta: [
      { charset: "utf-8" },
      { name: "keywords", content: "文章详情页面" },
      { name: "description", content: "文章页面" }
    ]
  },
  data() {
    return {
        islike:false
    };
  },
  components: {
    myHeader,
    myComment
  },
  methods: {

  }
};
</script>
<style>

</style>
