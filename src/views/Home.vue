<template>
  <div class="home">
    <section class="hero is-medium is-primary is-bold" style="background-repeat: no-repeat;background-position:center center; background-size: cover; background-image:linear-gradient(0deg, rgba(255,0,0,0.2), rgba(255,0,0,0.2)), url('https://www.thetimes.co.uk/imageserver/image/%2Fmethode%2Ftimes%2Fprod%2Fweb%2Fbin%2F1ac8bb0c-0bb8-11ea-96a6-b8ef146759ed.jpg?crop=5418%2C3048%2C41%2C378&resize=1180')">
  <div class="hero-body">
    <div v-if="!isMobile()" class="container">
      <h1 class="title" style="font-size:45px;">
        Welcome to Fruit Cake Kafé!
      </h1>
      <h2 class="subtitle" style="font-size:25px;font-weight:bold;">
        Amazing Homemade Fruit Cakes Delivered To You!
      </h2>
    </div>
    <div v-if="isMobile()" class="container">
      <h1 class="title" style="font-size:35px;">
        Welcome to Fruit Cake Kafé!
      </h1>
      <h2 class="subtitle" style="font-size:20px;font-weight:bold;">
        Amazing Homemade Fruit Cakes Delivered To You!
      </h2>
    </div>
  </div>
</section>

<section class="section" style="background-color:white;margin-top:0px;;text-align:right;">
    <div class="container">
      <div class="row">
        <div class="columns">

          <div class="column is-three-quarter" style="height:350px;background-position: center center;background-color:white;color:white;background-image:url(https://www.hellomagazine.com/imagenes/cuisine/2019120481516/mary-berry-homemade-christmas-cake-recipe/0-392-998/christmas-cake-slice-t.jpg);background-size: cover;background-repeat:no-repeat;">
                

          </div>
          <div class="column is-quarter">

            <h1 class="title" style="color:black;font-weight:bolder;font-size:35px;text-align:right;text-decoration:underline;">CAKE SIZES AVAILABLE</h1>
            <h2 style="font-weight:bold;color:black;font-size:18px;">Our Fruit Cakes Have Been Infused With Napoleon Brandy.<br/>Ingredients Include Salutanas, Raisins, Currants, Red Cherries & Egytian Dates.<br/><br/>Below Are The Sizes Currently Available For Delivery:
            </h2>
            <ol style="list-style-type: none;">
              <li>
                <h2 style="font-weight:bold;color:black;font-size:16px;">
                  1.65KG @ KSH8,250
                </h2>
              </li>
              <li>
                <h2 style="font-weight:bold;color:black;font-size:16px;">
                  1.7KG @ KSH8,500
                </h2>
              </li>
              <li>
              <h2 style="font-weight:bold;color:black;font-size:16px;">
                  1.75KG @ KSH8,750
                </h2>
              </li>
            </ol>
            
     </div>
        </div>

    </div>
    </div>
  </section>

  <section class="section" style="background-color:#F5F5DC;margin-top:0px;text-align:right;">
    <div class="container">
      <div class="row">
        <div class="columns">
           <div class="column is-three-quarter" style="height:350px;background-position: center center;color:white;background-image:url(https://i.postimg.cc/Zqg0LrNR/Whats-App-Image-2021-02-17-at-11-44-59.jpg);background-size: cover;background-repeat:no-repeat;">
                

          </div>
          
          <div class="column is-quarter">

            <h1 class="title" style="color:black;font-weight:bolder;font-size:35px;text-align:right;text-decoration:underline;">BRANDED FRUIT CAKES</h1>
            <h2 style="font-weight:bold;color:black;font-size:18px;">We Have A Special Option To Have Your Fruit Cake Branded By Us To Suite Whatever The Occasion.<br/><br/>We Do Branding For Birthday's, Office Parties, Weddings and Acccording To Your Specifications.
            </h2>
            
            
     </div>

    


        </div>

    </div>
    </div>
  </section>

  <section class="hero" style="background-color:black;">
  <div class="hero-body">
    <div class="container">
      <h1 class="title" style="margin-top:25px;color:white;font-weight:bolder;font-size:40px;text-align:center;">Order Information</h1>
            <h2 style="font-weight:bold;color:white;font-size:18px;">We Deliver Around Nairobi.<br/>To Place An Order Please Call JON QUAIL on +254722514997 or email jon.quail63@gmail.com.</h2>
    </div>
  </div>
  </section>

  <footer class="site-footer" style="color:white;">
      <div class="container">
        <div class="row">
          <div class="col-md-8 col-sm-6 col-xs-12">
            <p class="copyright-text">Website Designed & Managed by 
         <a href="#"><strong style="color:white;">Rony Quail</strong></a>.
            </p>
          </div>

         
        </div>
      </div>
</footer>
      
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  methods: {
  isMobile() {
    if(/Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent)) {
     return true
    } else {
     return false
        }
      }
    }
}
</script>

<style>
#app{
  background-color: #000;
  
}
#myVideo {
  position: fixed;
  right: 0;
  bottom: 0;
  min-width: 100%;
  min-height: 100%;
}
/* Add some content at the bottom of the video/page */
.content {
  position: fixed;
  bottom: 0;
  color: #f1f1f1;
  width: 100%;
  padding: 40px;
}
/* Style the button used to pause/play the video */
#myBtn {
  min-width: 200px;
  height: 35px;
  font-size: 18px;
  font-weight: bolder;
  border-radius: 10px;
  border:none;
  background: whitesmoke;
  color: black;
  cursor: pointer;
}
#myBtn:hover {
  background: green;
  color: white;
}
.site-footer
{
  background-color:#26272b;
  padding:45px 0 20px;
  font-size:15px;
  line-height:24px;
  color:#737373;
}
.site-footer hr
{
  border-top-color:#bbb;
  opacity:0.5
}
.site-footer hr.small
{
  margin:20px 0
}
.site-footer h6
{
  color:#fff;
  font-size:16px;
  text-transform:uppercase;
  margin-top:5px;
  letter-spacing:2px
}
.site-footer a
{
  color:#737373;
}
.site-footer a:hover
{
  color:#3366cc;
  text-decoration:none;
}
.footer-links
{
  padding-left:0;
  list-style:none
}
.footer-links li
{
  display:block
}
.footer-links a
{
  color:#737373
}
.footer-links a:active,.footer-links a:focus,.footer-links a:hover
{
  color:#3366cc;
  text-decoration:none;
}
.footer-links.inline li
{
  display:inline-block
}
.site-footer .social-icons
{
  text-align:right
}
.site-footer .social-icons a
{
  width:40px;
  height:40px;
  line-height:40px;
  margin-left:6px;
  margin-right:0;
  border-radius:100%;
  background-color:#33353d
}
.copyright-text
{
  margin:0
}
@media (max-width:991px)
{
  .site-footer [class^=col-]
  {
    margin-bottom:30px
  }
}
@media (max-width:767px)
{
  .site-footer
  {
    padding-bottom:0
  }
  .site-footer .copyright-text,.site-footer .social-icons
  {
    text-align:center
  }
}
.social-icons
{
  padding-left:0;
  margin-bottom:0;
  list-style:none
}
.social-icons li
{
  display:inline-block;
  margin-bottom:4px
}
.social-icons li.title
{
  margin-right:15px;
  text-transform:uppercase;
  color:#96a2b2;
  font-weight:700;
  font-size:13px
}
.social-icons a{
  background-color:#eceeef;
  color:#818a91;
  font-size:16px;
  display:inline-block;
  line-height:44px;
  width:44px;
  height:44px;
  text-align:center;
  margin-right:8px;
  border-radius:100%;
  -webkit-transition:all .2s linear;
  -o-transition:all .2s linear;
  transition:all .2s linear
}
.social-icons a:active,.social-icons a:focus,.social-icons a:hover
{
  color:#fff;
  background-color:#29aafe
}
.social-icons.size-sm a
{
  line-height:34px;
  height:34px;
  width:34px;
  font-size:14px
}
.social-icons a.facebook:hover
{
  background-color:#3b5998
}
.social-icons a.twitter:hover
{
  background-color:#00aced
}
.social-icons a.linkedin:hover
{
  background-color:#007bb6
}
.social-icons a.dribbble:hover
{
  background-color:#ea4c89
}
@media (max-width:767px)
{
  .social-icons li.title
  {
    display:block;
    margin-right:0;
    font-weight:600
  }
}
</style>