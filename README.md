
This was my first project I made with BootStrap 5 with added CSS and JS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Portfolio Project</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <link rel= "stylesheet" href="css/project.css">
</head>
<body>
  <!--Heading and Navbar-->
  <nav class="navbar navbar-expand-lg navbar-dark py-3 fixed-top">
    <div class="container">
        <a href="#" class="navbar-brand text-dark">Watch Styling</a>
        
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navmenu">
            <span class="navbar-toggler-icon"></span>
        </button>

       <div class="collapse navbar-collapse" id="navmenu">
           <ul class="navbar-nav ms-auto">
               <li class="nav-ite">
                   <a href="#watches" class="nav-link">Watches</a>
               </li>
               <li class="nav-ite">
                <a href="#watch-questions" class="nav-link">Questions</a>
            </li>
            <li class="nav-ite">
                <a href="#Contact-Info" class="nav-link">Contact Info</a>
            </li>
           </ul>
       </div>
    </div>
    
</nav>
<!--About Page/SignUp-->
<section class="p-5 text-sm-start text-center">
    <div class=" d-sm-flex p-5">
       <div>
         <h1>About <span class="text-warning">Our</span> Company</h1>
        <p class="lead my-5">
          We strive to help you find the best watch for any occasion. Going to a formal event and dont know what to wear? We have you covered. Sign up to recieve tips and different watches or call or send us an email. We will get you sorted out!
        </p>
        <button class=" btn-md p-3" data-bs-toggle="modal" data-bs-target="#enroll">Sign Up For The Newsletter</button>
      </div>
      <div class="container p-4">
      <div class= "clock">
          <div class= "hour">
            <div class="hr" id="hr"></div>
          </div>
          <div class="min">
          <div class="mn" id="mn"></div>
        </div>
        <div class="sec">
          <div class="sc" id="sc"></div>
        </div>
        </div>
        </div>
      
      
      </div>
    </section>
<!--Watches-->
<section id="watches" class="text-center bg-dark p-5">
   <div class="container">
     <div class="text-success text-center p-5">
       <h2>Watches For Different Occasions</h2>
     </div>
     <div class=" field row">
      <div class="col-md-10 g-4 p-5">
        <h3 class="text-success p-5">Field Watches</h3>
     <img class= "img-fluid"     src="images/marathon.jpeg" alt="field watch">
     <img class="img-fluid" src="images/field-watch.jpeg" alt="field watch">
       </div>
      </div>
     <div class="button d-grid col-4 p-3 mx-auto">
      <button type="button" class=" p-3 btn-sm text-center" data-bs-toggle="modal" data-bs-target="#watches1">Field Watch Info</button>
     </div>
     <!--Dress Watches-->
     <div class="dress row">
       <div class="col-md-10 g-4 p-5">
        <h3 class="text-success p-5">Dress Watches</h3>
     <img class= "img-fluid"     src="images/rolex.jpeg" alt="watch">
     <img class="img-fluid" src="images/cartier.jpeg" alt="dress watch">
       </div>
     </div>
     <div class="mx-auto d-grid col-4 p-3">
      <button type="button" class=" p-3 btn-sm text-center" data-bs-toggle="modal" data-bs-target="#dresswatches">Dress Watch Info</button>
     </div>
     <!--Casual Watches-->
     <div class=" casual row">
       <div class="col-md-10 g-4 p-5">
        <h3 class="text-success p-5 ">Casual Watches</h3>
     <img class= "img-fluid"     src="images/timex.jpeg" alt="timex">
     <img class="img-fluid" src="images/godtier.jpeg" alt="casio watch">
     </div>
     </div>
     <div class="mx-auto d-grid col-4 p-3">
      <button type="button" class=" p-3 btn-sm text-center" data-bs-toggle="modal" data-bs-target="#casualwatches">Casual Watch Info</button>
     </div>
   </div>
</section>
<!--Questions-->
<section  id="watch-questions" class="p-5">
  <div class="container">
      <h2 class="text-center mb-4">Frequently Asked Questions</h2>
      <div class="accordian"></div>
       <div class="accordion accordion-flush">
         
           <!--Item 1-->
           <div class="accordion-item">
             <h2 class="accordion-header">
               <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#question-one" aria-expanded="false">
                 What services do you offer?
               </button>
             </h2>
             <div id="question-one" class="accordion-collapse collapse" data-bs-parent="#watch-questions">
               <div class="accordion-body">Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae, recusandae tenetur porro nam magnam asperiores ad dolorem rerum obcaecati. Reprehenderit velit officiis, deserunt explicabo maiores pariatur fugit iusto blanditiis itaque, libero eveniet dolore voluptas, odit eligendi ipsa saepe voluptatem quae quasi aut vel error sapiente officia aliquid quidem. Veritatis, quae?</div>
             </div>
           </div>
           <!--Item 2-->
           <div class="accordion-item">
               <h2 class="accordion-header">
                 <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#question-two" aria-expanded="false">
                  What watches do you offer?
                 </button>
               </h2>
               <div id="question-two" class="accordion-collapse collapse" data-bs-parent="#watch-questions">
                 <div class="accordion-body">Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae, recusandae tenetur porro nam magnam asperiores ad dolorem rerum obcaecati. Reprehenderit velit officiis, deserunt explicabo maiores pariatur fugit iusto blanditiis itaque, libero eveniet dolore voluptas, odit eligendi ipsa saepe voluptatem quae quasi aut vel error sapiente officia aliquid quidem. Veritatis, quae?</div>
               </div>
               </div>
           <!--Item 3-->
           <div class="accordion-item">
               <h2 class="accordion-header">
                 <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#question-three" aria-expanded="false">
                   What are some price ranges?
                 </button>
               </h2>
               <div id="question-three" class="accordion-collapse collapse" data-bs-parent="#watch-questions">
                 <div class="accordion-body">Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae, recusandae tenetur porro nam magnam asperiores ad dolorem rerum obcaecati. Reprehenderit velit officiis, deserunt explicabo maiores pariatur fugit iusto blanditiis itaque, libero eveniet dolore voluptas, odit eligendi ipsa saepe voluptatem quae quasi aut vel error sapiente officia aliquid quidem. Veritatis, quae?</div>
               </div>
               </div>
  </div>
  </div>
        </section>
<!--Contact info-->
<section id= "Contact-Info" class="p-5">
  <div class="container p-5">
      <div class="row g-4">
          <div class="col-md">
              <h2 class="text-center mb-4">Contact Info</h2>
              <ul class="list-group list-group-flush lead">
                  <li class="list-group-item">
                      <span class="fw-bold">Main Location:</span> 50 Main St Blv. Denver CO
                  </li>
                  <li class="list-group-item">
                   <span class="fw-bold"> Company Phone:</span> (333)-333-333
               </li>
               <li class="list-group-item">
                   <span class="fw-bold">Contact Email:</span> watch@frontend.com
               </li>
               <li class="list-group-item">
                   <span class="fw-bold">Other Email:</span> other@frontend.com
               </li>
              </ul>
          </div>
         
         </div> 
      </div>
  </section>
  <!-- Footer/button -->
  <footer class=" p-5 bg-dark text-white text-center postition-relative">
    <div class="container">
        <p class="lead">Copyright &copy; 2021 Watch Styling</p>
        <a href="#" class="position-absolute bottom-0 end-0 p-5">
            <i class="bi bi-arrow-up-circle h1"></i>
        </a>
    </div>
    <button type="button" class="btn btn-danger btn-floating btn-lg" id="btn-back-to-top">
      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-up-circle-fill" viewBox="0 0 16 16">
        <path d="M16 8A8 8 0 1 0 0 8a8 8 0 0 0 16 0zm-7.5 3.5a.5.5 0 0 1-1 0V5.707L5.354 7.854a.5.5 0 1 1-.708-.708l3-3a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708L8.5 5.707V11.5z"/>
      </svg>
    </button>
</footer>
        <!-- Modal -->
<div class="modal fade" id="watches1" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="watches1" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">For the Outdoors</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit, saepe ipsum! Neque quisquam omnis sapiente! Ipsum reiciendis suscipit perferendis, modi, vero ipsam officiis quas, nihil possimus autem voluptatibus harum!
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
<div class="modal fade" id="dresswatches" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="dresswatches" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">For Formal Events</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit, saepe ipsum! Neque quisquam omnis sapiente! Ipsum reiciendis suscipit perferendis, modi, vero ipsam officiis quas, nihil possimus autem voluptatibus harum!
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
<div class="modal fade" id="casualwatches" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="casualwatches" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">For Everyday Wear</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit, saepe ipsum! Neque quisquam omnis sapiente! Ipsum reiciendis suscipit perferendis, modi, vero ipsam officiis quas, nihil possimus autem voluptatibus harum!
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
<div class="modal fade" id="enroll" tabindex="-1" aria-labelledby="enroll" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Enter Email Here</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <p class="lead">Fill out this form and we will get back to you.</p>
        <form>
            <div class="mb-3">
                <label for="first-name" class="col-form-label">
                    First Name
                </label>
                <input type="text" class="form-control">
            </div>
            <div class="mb-3">
              <label for="first-name" class="col-form-label">
                  Last Name
              </label>
              <input type="text" class="form-control">
          </div>
          <div class="mb-3">
              <label for="first-name" class="col-form-label">
                  Email
              </label>
              <input type="text" class="form-control" id="first-name">
          </div>
          <div class="mb-3">
              <label for="first-name" class="col-form-label">
                  Phone
              </label>
              <input type="text" class="form-control">
          </div>
        </form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Submit</button>
      </div>
    </div>
  </div>
</div>





<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
<script>
  const deg = 6;
  const hr = document.querySelector("#hr");
  const mn = document.querySelector("#mn");
  const sc = document.querySelector("#sc");
  setInterval(() => {
    let day = new Date();
    let hh = day.getHours() * 30;
    let mm = day.getMinutes() * deg;
    let ss = day.getSeconds() * deg;
    hr.style.transform = `rotateZ(${hh+(mm/12)}deg)`;
    mn.style.transform = `rotateZ(${mm}deg)`;
    sc.style.transform = `rotateZ(${ss}deg)`;
  })
</script> 
<script>
  let mybutton = document.getElementById("btn-back-to-top");
  
  window.onscroll = function () {
    scrollFunction();
  };
  
  function scrollFunction() {
    if (
      document.body.scrollTop > 20 ||
      document.documentElement.scrollTop > 20
    ) {
      mybutton.style.display = "block";
    } else {
      mybutton.style.display = "none";
    }
  }
  mybutton.addEventListener("click", backToTop);
  
  function backToTop() {
    document.body.scrollTop = 0;
    document.documentElement.scrollTop = 0;
  }
  </script>
    
</body>

</html>
