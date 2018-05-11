<template>
    <div style="height:100%">
       <my-header></my-header>
        <div class="container index">
            <div class="col-xs-16 main">
                    主体部分
                <!--热门专题-->
                <div class="recommend-collection">
                    <nuxt-link to="/collection/story" class="collection">
                        <img src="../assets/img/collection-1.jpg" alt="">
                        <span name="story">故事</span>
                    </nuxt-link>
                    <nuxt-link to="/collection/life" class="collection">
                        <img src="../assets/img/collection-2.jpg" alt="">
                        <span name="life">生活</span>
                    </nuxt-link>
                    <nuxt-link to="/collection/social" class="collection">
                        <img src="../assets/img/collection-3.jpg" alt="">
                        <span name="social">社会</span>
                    </nuxt-link>
                    <nuxt-link to="/collection/read" class="collection">
                        <img src="../assets/img/collection-4.png" alt="">
                        <span name="read">读书</span>
                    </nuxt-link>
                    <nuxt-link to="/collection/movie" class="collection">
                        <img src="../assets/img/collection-5.jpg" alt="">
                        <span name="movie">简书电影</span>
                    </nuxt-link>
                    <nuxt-link to="collection/more" class="more-collection" >
                        更多专题
                        <i class="fa fa-angle-right"></i>
                    </nuxt-link>
                </div>
                <div class="split-line">
                    <!--文章列表-->
                    <div class="list-container">
                        <ul class="note-list">
                        <li class="have-img">
                            <nuxt-link to="/p/123">
                                <img class="wrap-img" src="../assets/img/note.png" alt="">
                            </nuxt-link>
                            <div class="content">
                                <div class="author">
                                    <nuxt-link to="/p/123" class="avatar">
                                        <img src="../assets/img/default-avatar.jpg" alt="">
                                    </nuxt-link>
                                    <div class="info">
                                        <nuxt-link to="/p/123">测试用户
                                        </nuxt-link>
                                        <span class="time">04.12  10:18</span>
                                    </div>
                                </div>
                                <nuxt-link class="title" to="/p/123">佛系程序员的月薪五万指南</nuxt-link>
                                <div class="abstract">摘要：大师：很简单，我这里有一份佛系月薪 5 万指南，我看你骨骼清奇、脑门光亮，一看就是将要大富大贵之人，这份指南可以助你快速实现小目标！ 程序员问大师…… 青年：大师，你看...</div>
                                <div class="meta">
                                    <nuxt-link to="/collection" class="collection-tag">社会与法</nuxt-link>
                                    <nuxt-link to="/p/123">
                                        <i class="fa fa-eye"></i>
                                            1500
                                    </nuxt-link>
                                   <nuxt-link to="/p/123">
                                       <i class="fa fa-comment"></i>
                                       100
                                   </nuxt-link>
                                    <span>
                                        <i fa fa-heart></i>
                                        10
                                    </span>
                                </div>
                            </div>
                        </li>
                            <li class="have-img">
                                <nuxt-link to="/p/123">
                                    <img class="wrap-img" src="../assets/img/note.png" alt="">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123"  class="avatar">
                                            <img src="../assets/img/default-avatar.jpg" alt="">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="/p/123">测试用户
                                            </nuxt-link>
                                            <span class="time">04.12  10:18</span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">佛系程序员的月薪五万指南</nuxt-link>
                                    <div class="abstract">摘要：大师：很简单，我这里有一份佛系月薪 5 万指南，我看你骨骼清奇、脑门光亮，一看就是将要大富大贵之人，这份指南可以助你快速实现小目标！ 程序员问大师…… 青年：大师，你看...</div>
                                    <div class="meta">
                                        <nuxt-link to="/collection" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                        <i fa fa-heart></i>
                                        10
                                    </span>
                                    </div>
                                </div>
                            </li>
                            <li class="have-img">
                                <nuxt-link to="/p/123">
                                    <img class="wrap-img" src="../assets/img/note.png" alt="">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123"  class="avatar">
                                            <img src="../assets/img/default-avatar.jpg" alt="">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="/p/123">测试用户
                                            </nuxt-link>
                                            <span class="time">04.12  10:18</span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">佛系程序员的月薪五万指南</nuxt-link>
                                    <div class="abstract">摘要：大师：很简单，我这里有一份佛系月薪 5 万指南，我看你骨骼清奇、脑门光亮，一看就是将要大富大贵之人，这份指南可以助你快速实现小目标！ 程序员问大师…… 青年：大师，你看...</div>
                                    <div class="meta">
                                        <nuxt-link to="/collection" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                        <i fa fa-heart></i>
                                        10
                                    </span>
                                    </div>
                                </div>
                            </li>
                            <li class="have-img">
                                <nuxt-link to="/p/123">
                                    <img class="wrap-img" src="../assets/img/note.png" alt="">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123"  class="avatar">
                                            <img src="../assets/img/default-avatar.jpg" alt="">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="/p/123">测试用户
                                            </nuxt-link>
                                            <span class="time">04.12  10:18</span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">佛系程序员的月薪五万指南</nuxt-link>
                                    <div class="abstract">摘要：大师：很简单，我这里有一份佛系月薪 5 万指南，我看你骨骼清奇、脑门光亮，一看就是将要大富大贵之人，这份指南可以助你快速实现小目标！ 程序员问大师…… 青年：大师，你看...</div>
                                    <div class="meta">
                                        <nuxt-link to="/collection" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                        <i fa fa-heart></i>
                                        10
                                    </span>
                                    </div>
                                </div>
                            </li>
                            <li class="have-img">
                                <nuxt-link to="/p/123">
                                    <img class="wrap-img" src="../assets/img/note.png" alt="">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123"  class="avatar">
                                            <img src="../assets/img/default-avatar.jpg" alt="">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="/p/123">测试用户
                                            </nuxt-link>
                                            <span class="time">04.12  10:18</span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">佛系程序员的月薪五万指南</nuxt-link>
                                    <div class="abstract">摘要：大师：很简单，我这里有一份佛系月薪 5 万指南，我看你骨骼清奇、脑门光亮，一看就是将要大富大贵之人，这份指南可以助你快速实现小目标！ 程序员问大师…… 青年：大师，你看...</div>
                                    <div class="meta">
                                        <nuxt-link to="/collection" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                        <i fa fa-heart></i>
                                        10
                                    </span>
                                    </div>
                                </div>
                            </li>
                        </ul>
                        <a href="#" class="load-more">阅读更多</a>
                    </div>

                </div>
            </div>

            <div class="col-xs-offset-1 col-xs-7 aside">
                侧边栏
              <div class="row">
                  <!--广告-->
                  <div class="board">
                      <nuxt-link to="/">
                          <img src="../assets/img/ad1.png" alt="">
                      </nuxt-link>
                      <nuxt-link to="/">
                          <img src="../assets/img/ad2.png" alt="">
                      </nuxt-link>
                      <nuxt-link to="/">
                          <img src="../assets/img/ad3.png" alt="">
                      </nuxt-link>
                      <nuxt-link to="/">
                          <img src="../assets/img/ad4.png" alt="">
                      </nuxt-link>
                  </div>
                  <!--推荐作者-->
                  <div class="recommend-author">
                      <div class="title">
                          <span>推荐作者</span>
                          <nuxt-link to="/" class="page-change">
                              <i class="fa fa-refresh changePage" @click="changePage()">换一批</i>
                          </nuxt-link>
                      </div>
                      <ul class="recommend-list">
                          <li>
                          <nuxt-link class="avatar" to="/123">
                              <img src="../assets/img/default-avatar.jpg" alt="">
                          </nuxt-link>
                          <a href="#">
                              <i class="fa fa-plus follow" @click="follow()">关注</i>
                          </a>
                          <nuxt-link to="/123" class="name">
                              简书用户
                          </nuxt-link>
                          <p>写了198k字 · 1.7k喜欢</p>
                      </li>
                          <li>
                              <nuxt-link class="avatar" to="/123">
                                  <img src="../assets/img/default-avatar.jpg" alt="">
                              </nuxt-link>
                              <a href="#">
                                  <i class="fa fa-plus follow" @click="follow()">关注</i>
                              </a>
                              <nuxt-link to="/123" class="name">
                                  简书用户
                              </nuxt-link>
                              <p>写了198k字 · 1.7k喜欢</p>
                          </li>
                      </ul>
                      <nuxt-link to="/123" class="find-more">
                          查看更多
                          <i class="fa fa-right"></i>
                      </nuxt-link>
                  </div>
              </div>
            </div>
        </div>
    </div>
</template>
<script>
    import myHeader from  '../components/myHeader'
    export default {
        head:{
            title:'简书-创作你的创作',
            meta:[
                {charset:'utf-8'},
                {name:'keywords',content:'简书首页'},
                {name:'description',content:'简书首页'},
                {name:'author',content:'李志远'}
            ]
        },
        components:{
            myHeader
        },
        data () {
            return {
                name:'首页'
            }
        },
        methods:{
            follow:function () {
                console.log("get follow");
                    var follower=document.querySelector(".follow");

                    follower.innerText=="关注"?follower.innerText="已关注":follower.innerText="关注";
                    follower.className=="fa fa-plus follow"?follower.className="fa fa-check follow":follower.className="fa fa-plus follow";
                    follower.innerText=="关注"?follower.style.color="#42c02e":follower.style.color="#969696";
                    console.log(follower);
                    console.log(this);
                    if( follower.innerText!=="关注"){

                    follower.onmouseover=function () {
                        this.innerText="取消关注";
                        this.className="fa fa-times follow";
                    }
                        follower.onmouseleave=function () {
                            this.innerText="已关注";
                            this.className="fa fa-check follow";
                        }
                }
            },
            changePage:function () {
                console.log("get changePage");
                var cycle=document.querySelector(".changePage")
                console.log(cycle);
                cycle.css({
                    transform:rotate('360'+deg)
                })
            }
        }
    }
</script>
<style>

</style>