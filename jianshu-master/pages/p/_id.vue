<template>
    <div>
    <my-header></my-header>
    <div class="note">
        <div class="post">
            <div class="article">
                <h1 class="title">
                    金箍棒为何13500斤？这是读懂西游的钥匙
                </h1>
                <div class="author">
                    <div class="avatar">
                        <img src="~/assets/img/default-avatar.jpg" alt="">
                    </div>
                    <div class="info">
                        <nuxt-link class="name" to="name">
                            占芳
                        </nuxt-link>
                        <a  class="btn btn-success follow">
                            <i class="fa fa-plus"></i>
                            <span>关注</span>
                        </a>
                        <div class="meta">
                            <span class="publish-time">
                                2018.04.21 13:52
                            </span>
                            <span class="wordage">
                                    字数 2831
                            </span>
                            <span class="view-count">阅读 19811</span>

                            <span class="likes-count">喜欢 386</span>
                        </div>
                    </div>
                </div>
                <div class="show-content">孙悟空的金箍棒可不是管喘气的！

                    对这件打得天兵天将满地找牙的大杀器，多数人的认识还相对肤浅。

                    有人在解读金箍棒的重量时，把这一万三千五百斤的大家伙，与喘气联系在了一起。

                    仅因为《黄帝内经·难经》中写过人的气息数：“人一日一夜，凡一万三千五百息，脉行五十度，周于身。”

                    单凭这一点，就将金箍棒这个太上老君亲手打造的神器，等同于凡人一昼夜的喘气次数？

                    这也太不将道教第一神当回事了吧！

                    金箍棒为何一万三千五百斤？解决了此问题，就差不多读懂了半部《西游记》！

                    01
                    对《西游记》的误读，由来已久。

                    尤其是孙大圣的金箍棒，许多人以为好不容易找到一个有历史感的数字，就找到金箍棒的秘密。

                    其实，完全错了！

                    若是按这个思路去找，这等有讲究的历史数字多了去了。

                    战国时的《周髀算经》，那可是古时候天子治天下的经典。阐明了盖天说和四分历法，大唐时就是国子监的教材。

                    这本书就说：“冬至南十三万五千里，日中立竿测影。此一者天道之数。”

                    这个数才牛逼呢，是天道之数。

                    我还可以说金箍棒是这个数字的缩小版呢！你说牛不牛逼？

                    </div>
                <div class="show-foot">
                    <nuxt-link class="notebook" to="#"></nuxt-link>
                </div>
                <div class="follow-detail">
                    <div class="info">
                        <div class="avatar">
                            <img src="~/assets/img/default-avatar.jpg" alt="">
                        </div>
                        <a class="btn btn-success follow">
                            <i class="fa fa-plus"></i>
                            <span>关注</span>
                        </a>
                        <a>有备而来的路人甲</a>
                        <i class="fa fa-mars mars"></i>
                        <p>写了 314280 字，被 90704 人关注，获得了 88891 个喜欢</p>
                    </div>
                    <div class="signature">
                        大萌，对世界上瘾的二逼青年。
                        旅行、摄影、公益、写作、民谣、吃货。
                        微信公众号：大萌呀（ID：dmzls123456）（这里可以找到大萌）
                        微博：大萌Love（撩大萌也请戳微博，也许不能及时回复，看见一定回复，请谅解）
                    </div>

                </div>
                <div class="meta-bottom">
                    <div class="like">
<div class="btn btn-like">
    <a>喜欢</a>
    <div class="modal-wrap">
        <a>454</a>
    </div>
</div>
                    </div>
                    <div class="share-group">
                        <nuxt-link to="/123" data-toggle="tooltip" data-origin-title="分享到微信" class="share-circle" >
                            <i class="fa fa-weixin" v-tooltip="'hello'"></i>
                        </nuxt-link>
                        <nuxt-link to="/123" data-toggle="tooltip" data-origin-title="分享到微博" class="share-circle">
                            <i class="fa fa-weibo"></i>
                        </nuxt-link>
                        <nuxt-link to="/123" data-toggle="tooltip" data-origin-title="下载长微博截图" class="share-circle">
                            <i class="fa fa-image"></i>
                        </nuxt-link>
                        <button v-tooltip="'hello'">hello</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    </div>
</template>
<script>
    import myHeader from '~/components/myHeader'
    export default {
        head :{
            title:"简书文章详情页-创作你的创作",
            meta:[
                {charset:'utf-8'},
                {name:'keyword',content:'文章详情页'},
                {name:'description',content:'文章页面'}
            ]
        },
        data (){
            return {

            }
        },
        components:{
            myHeader
        }
    }
</script>