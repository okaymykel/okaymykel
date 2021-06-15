<template>
  <div class="container-fluid m-0 p-0">
     <div id="home-page" class=" full-height p-4">
         <div class="container pt-3">
            <div class="row pb-5">
                <div class="col-lg-6 pt-4 my-auto">
                    <div class="text-center mb-3 d-block d-lg-none">
                        <h1 class="display-3">{{title}}</h1>
                        <h3> Find the world</h3>
                    </div> 
                    <img id="iphone-img" src="../assets/travel.png" class="image-fluid">
                </div>
                <div class="col-lg-6 my-auto pt-4 ">
                    <div class="text-center mb-3 d-none d-lg-block" >
                        <h1 class="display-3">{{title}}</h1>
                        <h3> Find the world</h3>
                    </div>
                    <div class="border p-3 p-md-5 bg-white rounded shadow">
                        <h2>Coming soon</h2>
                        <form>
                            <div class="form-group">
                                <label for="emailSignup">Reset your account now, we'll contact you when it's live</label>
                                <input id="emailSignup" 
                                    placeholder="Enter Email"
                                    class="form-control"
                                > <br>
                                <small id="emailHelp" class="form-text text-muted"> We'll never share your email address</small><br>
                                <button type="submit" class="btn btn-success mt-3">Join Waiting List </button>
                            </div>
                        </form>
                    </div>
                    <div id="available" class="p-2">
                        <h4 class="text-center mb-2 mt-3 text-light">
                            Available on
                        </h4>
                        <div class="row">
                            <div class="col my-auto">
                                <img src="../assets/apple.jpg" class="float-right img-fluid apple_store_img ">
                            </div>
                            <div class="col my-auto">
                                <img src="../assets/google.jpg" class="float-left img-fluid apple_store_img">
                            </div>
                        </div>


                    </div>
                </div>
            </div>

         </div>
     </div> 
     <div id="about" class="bg-light p-3 p-md-5">
       <div class="row">
            <div class="col-lg">
                <img src="../assets/phone.png" height="120" class="m-4" >
                <h5 class="ml-md-4 mr-md-4">
                    Lorem ipsum dolor, sit amet consectetur, <br>
                    Error voluptates, recusandae, quos ducimus,<br> 
                    voluptatem ratione aspernatur pariatur debitis eveniet neque velit quae!
                </h5>
            </div>
            <div class="col-lg">
                <img src="../assets/piggybank.jpg" height="120" class="m-4" >
                <h5 class="ml-md-4 mr-md-4">
                    Lorem ipsum dolor, sit amet consectetur, <br>
                    Error voluptates, recusandae, quos ducimus,<br> 
                    voluptatem ratione aspernatur pariatur debitis eveniet neque velit quae!
                </h5>
            </div>
            <div class="col-lg">
                <img src="../assets/passport.jpg" height="120" class="m-4" >
                <h5 class="ml-md-4 mr-md-4">
                    Lorem ipsum dolor, sit amet consectetur, <br>
                    Error voluptates, recusandae, quos ducimus,<br> 
                    voluptatem ratione aspernatur pariatur debitis eveniet neque velit quae!
                </h5>
            </div>
        </div>  
        </div> 
        <div id="contact" class="p-4">
        <div class="row justify-content-center mt-3 mb-3">
            <div class="col-lg-4">
                 <h2>Have Any Questions?</h2>
                 <p>Contact us by filling out the information below</p>

                <form>
                    <div class="form-group text-left">
                        <input type="email"
                            class="orm-control"
                            placeholder="Enter Your Email"
                        >
                        <textarea class="form-control mt-3"
                            placeholder="Enter Your Message"
                            rows="5"
                        ></textarea>       
                    </div>
                    <button type="submit" class="btn btn-primary mt-3">Send Message</button>
                </form>
            </div>
         </div>
        </div> 
        <div id="footer" class="p-4">
            <footer class="text-light p-1">
                <a href="#" target="_blank" class="text-warning">Build This App</a>
                <a href="#" class="text-warning">Privacy Policy</a>
                <br>
                <small> &copy; 2021, TravelTreasury.app</small>
            </footer>
        </div> 
   </div>  
</template>

<script>
export default {
  data () {
      return {
          title: 'Travel Treasury',
      }
  }  
}
</script>

<style scoped>
#home-page {
    background-color: #92d2f2;
    background: url("../assets/bg-image.jpg") no-repeat center center;
    --webkit-background-size: cover;
    --moz-background-size: cover;
    --o-background-size: cover;
    background-size: cover;
}
#about{
    min-height: 40vh;
}
#iphone-img{
    max-height: 85vh;
}
#contact{
    background-color: #57aeaf;
}
.app_store_img{
    max-height: 80px;
}
#footer{
    background-color: #000;
    max-height: 20vh;
}

</style>