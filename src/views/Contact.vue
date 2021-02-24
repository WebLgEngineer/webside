<template>
  <section class="contact mt-59 mt-md-88 mt-lg-97">
    <div class="container py-3 py-md-5">
      <div class="row justify-content-between align-items-center">
        <div class="col-md-5">
          <div class="row justify-content-center align-items-center">
            <div class="col-3 col-md-12">
              <img class="w-100 mw-200 mx-auto my-0 d-block" src="../assets/peiLogo.png" alt="">
            </div>
            <div class="col-9 col-md-12 mt-md-3 text-md-center">
              <p class="mb-2 mb-md-3"><i class="fas fa-envelope"></i> WebLgEngineer@gmail.com</p>
              <p class="mb-0"><i class="fas fa-phone"></i> 0987-056-509</p>
            </div>
          </div>
        </div>
        <div class="col-md-6 mt-3 mt-md-0">
          <form class="">
            <div class="form-group">
              <label for="staticEmail" class="">Email:</label>
              <input type="email" class="form-control" id="staticEmail" placeholder="email@example.com">
            </div>
            <div class="form-group">
              <label for="subject" class="">主旨:</label>
              <input type="text" class="form-control" id="subject">
            </div>
              <div class="form-group">
                <label for="exampleFormControlTextarea1">內容:</label>
                <textarea class="form-control" id="exampleFormControlTextarea1" rows="5"></textarea>
              </div>
            <div class="text-right">
              <span class="text-danger mr-3">目前未串接</span>
              <button type="submit" class="btn btn-primary">送出</button>
            </div>  
          </form>
        </div>
      </div>
    </div>
  </section>
</template>