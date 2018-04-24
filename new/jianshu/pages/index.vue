<template>
    <div style="height:100%">
        <my-header></my-header>
        <div class="container index">
            <div class="row">
                <div class="col-xs-16 main">
                    <!--热门专题-->
                    <div class="recommend-collection">
                        <nuxt-link class="collection" to="/collection/123">
                            <img src="~/assets/img/c_1.jpg">
                            <span name="name">故事</span>
                        </nuxt-link>
                        <nuxt-link class="collection" to="/collection/123">
                            <img src="~/assets/img/c_1.jpg">
                            <span name="name">摄影</span>
                        </nuxt-link>
                        <nuxt-link class="collection" to="/collection/123">
                            <img src="~/assets/img/c_2.jpg">
                            <span name="name">人文社科</span>
                        </nuxt-link>
                        <nuxt-link class="collection" to="/collection/123">
                            <img src="~/assets/img/c_2.jpg">
                            <span name="name">历史</span>
                        </nuxt-link>
                        <nuxt-link class="collection" to="/collection/123">
                            <img src="~/assets/img/c_3.jpg">
                            <span name="name">读书</span>
                        </nuxt-link>
                        <nuxt-link class="more-collection" to="/collection/123">
                            更多热门专题
                            <i class="fa fa-angle-right"></i>
                        </nuxt-link>
                    </div>
                    <div class="split-line"></div>
                    <div class="list-container">
                      <ul class="note-list">
                        <li class="have-img">
                          <nuxt-link to="/p/123">
                          <img class="wrap-img" src="~/assets/img/5.jpg">
                          </nuxt-link>
                          <div class="content">
                            <div class="author">
                              <nuxt-link to="/p/123" class="avatar">
                              <img src="~/assets/img/default-avatar.jpg" >
                              </nuxt-link>
                              <div class="info">
                                <nuxt-link to="/u/123" class="nickname">测试用户</nuxt-link>
                              <span class="time">
                                04.12  10:18
                              </span>
                              </div>
                            </div>
                            <nuxt-link class="title" to="/p/123">大学四年该如何度过？这10条经验教训请你收下</nuxt-link>
                            <div class="abstruct">
                         我经常说，很多道理不需要我们撞得头破血流才幡然醒悟。成功有很多种方式，但是失败的原因却惊人的相似。
                         四年了，即将踏入社会，成功的经验不多，失败的教训倒是积攒了不少。
                         趁新学期开始，写写这四年里吃的一些亏，踩过的一些坑，一共10条经验教训，
        
                            </div>
                            <div class="meta">
                              <nuxt-link to="/c/123" class="collection-tag">社会与法</nuxt-link>
                              <nuxt-link to="/p/123">
                              <i class="fa fa-eye"></i>
                              1500  
                              </nuxt-link>
                              <span>
                                <i class="fa fa-comment"></i>
                                20
                              </span>
                              <span>
                                <i class="fa fa-heart"></i>
                                10
                              </span>
                            </div>
                          </div>
                        </li>
                        
                      </ul>
                      
                    </div>
                    <a href="#" class="load-more">阅读更多</a>
                </div>
                <div class="col-xs-offset-1 col-xs-7 aside">
                    <div class="row">
                      <div class="board">
                 <nuxt-link to="/">
                   <img src="~assets/img/a.png" alt="">
                 </nuxt-link>
                     <nuxt-link to="/">
                   <img src="~assets/img/b.png" alt="">
                 </nuxt-link>
                     <nuxt-link to="/">
                   <img src="~assets/img/c.png" alt="">
                 </nuxt-link>
                     <nuxt-link to="/">
                   <img src="~assets/img/d.png" alt="">
                 </nuxt-link>
                    </div>
                    <div class="recommended-author">
                      <div class="title">
                        <span>推荐作者</span>
                        <nuxt-link to="/" class="page-change">
                        <i class="fa fa-refresh">换一批</i>
                        </nuxt-link>
                      </div>
                      <ul class="recommended-list">
                        <li>
                          <nuxt-link class="avatar" to="/u/123">
                          <img src="~assets/img/default-avatar.jpg" alt="">
                          </nuxt-link>
                          <a href="#" class="follow"><i class="fa fa-plus"></i>关注</a>
                          <nuxt-link to="/u/123" class="name">
                          简书用户
                          </nuxt-link>
                          <p>写了1958k字·1.9k喜欢</p>
                        </li>
                         <li>
                          <nuxt-link class="avatar" to="/u/123">
                          <img src="~assets/img/default-avatar.jpg" alt="">
                          </nuxt-link>
                          <a href="#" class="follow"><i class="fa fa-plus"></i>关注</a>
                          <nuxt-link to="/u/123" class="name">
                          简书用户
                          </nuxt-link>
                          <p>写了1958k字·1.9k喜欢</p>
                        </li>
                         <li>
                          <nuxt-link class="avatar" to="/u/123">
                          <img src="~assets/img/default-avatar.jpg" alt="">
                          </nuxt-link>
                          <a href="#" class="follow"><i class="fa fa-plus"></i>关注</a>
                          <nuxt-link to="/u/123" class="name">
                          简书用户
                          </nuxt-link>
                          <p>写了1958k字·1.9k喜欢</p>
                        </li>
                         <li>
                          <nuxt-link class="avatar" to="/u/123">
                          <img src="~assets/img/default-avatar.jpg" alt="">
                          </nuxt-link>
                          <a href="#" class="follow"><i class="fa fa-plus"></i>关注</a>
                          <nuxt-link to="/u/123" class="name">
                          简书用户
                          </nuxt-link>
                          <p>写了1958k字·1.9k喜欢</p>
                        </li>
                         <li>
                          <nuxt-link class="avatar" to="/u/123">
                          <img src="~assets/img/default-avatar.jpg" alt="">
                          </nuxt-link>
                          <a href="#" class="follow"><i class="fa fa-plus"></i>关注</a>
                          <nuxt-link to="/u/123" class="name">
                          简书用户
                          </nuxt-link>
                          <p>写了1958k字·1.9k喜欢</p>
                        </li>
                        </ul>

                        <nuxt-link to="/" class="find-more">
                           查看更多
                           <i class="fa fa-angle-right"></i>
                        </nuxt-link> 
                    </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import myHeader from "../components/myHeader";
export default {
  head: {
    title: "简书-创作你的创作",
    meta: [
      { charset: "utf-8" },
      { name: "keywords", content: "简书首页" },
      { name: "description", content: "简书首页" },
      { name: "author", content: "李志远" }
    ]
  },
  components: {
    myHeader
  },
  data() {
    return {
      name: "首页"
    };
  }
};
</script>