<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="apple-touch-icon" sizes="180x180" href="Assets/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="Assets/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="Assets/favicon-16x16.png">
    <link rel="manifest" href="Assets/site.webmanifest">
    <title>Smile Sujok foundation</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://kit.fontawesome.com/168ebc7feb.js" crossorigin="anonymous"></script>
    <link
      rel="stylesheet"
      href="https://unpkg.com/flowbite@1.5.4/dist/flowbite.min.css"
    />
  </head>
  <body>
      
       <!-- Small Devices  -->
    <header
      class="h-[60vh] w-full bg-[url('Images/HeroSmall.png')] bg-no-repeat bg-cover md:hidden lg:hidden"
    >
     <!-- Navigation Bar here   -->
      <nav
        class="bg-gradient-to-r from-blue-700 to-[#ffffff00] sticky py-2 px-2 flex justify-between shadow-lg backdrop-blur-md z-50"
      >
        <div>
          <p class="font-Inter font-bold lg:text-lg text-white">SU-jok</p>
          <p class="font-Ubuntu text-xs font-semibold lg:text-sm text-slate-200">
            We Heal with care
          </p>
        </div>
        <div class="flex">
          <ul class="flex text-white font-mono gap-x-1 lg:mr-8">
            <li
              class="lg:mx-4 py-2 hover:underline transition-all ease-in hover:text-slate-200"
            >
              <a class="rounded-3xl bg-blue-500 px-2 py-1 lg:px-4 lg:py-2 text-[10px] lg:text-base" href="#about">About Us</a>
            </li>
            <li
              class="lg:mx-4 py-2 hover:underline transition-all ease-in hover:text-slate-200"
            >
              <a class="rounded-3xl bg-blue-500 px-2 py-1 lg:px-4 lg:py-2 text-[10px] lg:text-base" href="#connect with doctors">connect with doctors</a>
            </li>
            <li
              class="lg:mx-4 py-2 hover:underline transition-all ease-in hover:text-slate-200"
            >
              <a class="rounded-3xl bg-blue-500 px-2 py-1 lg:px-4 lg:py-2 text-[10px] lg:text-base" href="#age based system">age based system </a>
            </li>
            <li
              class="lg:mx-4 py-2 hover:underline transition-all ease-in hover:text-slate-200"
            >
              <a class="rounded-3xl bg-blue-500 px-2 py-1 lg:px-4 lg:py-2 text-[10px] lg:text-base" href="#sujokKit">buy sujok kit</a>
            </li>
            <li
              class="lg:mx-4 py-2 hover:underline transition-all ease-in hover:text-slate-200"
            >
              <a class="rounded-3xl bg-blue-500 px-2 py-1 lg:px-4 lg:py-2 text-[10px] lg:text-base" href="#learnWithUs">learn with us</a>
            </li>
          </ul>
        </div> 
      </nav>
       <img src="https://miro.medium.com/v2/resize:fit:1024/1*Ruim9pk0ZwNuBJYnUnmFaQ.png" alt="background" width="1920px" height="1080px";>
      <!-- Hero section  -->
      <div id="top" class="absolute top-36 lg:top-[30rem] left-16 lg:left-[29em] lg:z-10">
        <div class="flex flex-col justify-center">
          <p class="text-center text-2xl lg:text-6xl text-white font-semibold font-Baloobhai2 lg:mb-16 ">
           
          </p>
        </div>
        <div class="mt-28 ml-8">
          <a href="#"
            class="text-white m-auto bg-gradient-to-r from-blue-500 via-blue-600 to-blue-700 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-4 text-center mr-2 mb-2"
          >         
          Exercise with pose detection 
          </a>
        </div>
      </div>
    </header>
    <!-- For large devices  -->
    <header
      class="hidden md:block lg:block h-[130vh] w-full bg-[url('Images/HeroS.png')] bg-no-repeat bg-cover"
    >
     <!-- Navigation Bar here  -->
      <nav
        class="bg-gradient-to-r from-blue-700 to-[#ffffff00] fixed py-2 w-full px-24 flex justify-between shadow-lg backdrop-blur-md z-50"
      >
        <a href="">
          <p class="font-Inter font-bold text-lg text-white">Su-JOK</p>
          <p class="font-Ubuntu font-semibold text-sm text-slate-200">
           Therapy that heal
          </p>
        </a>
        <div class="flex">
          <ul class="flex text-white font-mono mr-8">
            <li
              class="mx-4 py-2 hover:underline transition-all ease-in hover:text-slate-200"
            >
              <a class="rounded-3xl bg-blue-500 px-4 py-2" href="#about">About Us</a>
            </li>
            <li
              class="mx-4 py-2 hover:underline transition-all ease-in hover:text-slate-200"
            >
              <a class="rounded-3xl bg-blue-500 px-4 py-2" href="#connect with doctors">Connect with doctors</a>
            </li>
            <li
              class="mx-4 py-2 hover:underline transition-all ease-in hover:text-slate-200"
            >
              <a class="rounded-3xl bg-blue-500 px-4 py-2" href="#ageBasedsystem">age based system</a>
            </li>
            <li
              class="mx-4 py-2 hover:underline transition-all ease-in hover:text-slate-200"
            >
              <a class="rounded-3xl bg-blue-500 px-4 py-2" href="#buySujokkit">Buy Sujok kit</a>
            </li>
            <li
              class="mx-4 py-2 hover:underline transition-all ease-in hover:text-slate-200"
            >
              <a class="rounded-3xl bg-blue-500 px-4 py-2" href="#learn">learn with us</a>
            </li>
          </ul>
          <button
            type="button"
            class="text-white bg-blue-400 hover:bg-blue-500 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
          >
          <i class="fa-solid fa-phone px-2 "></i>
            Call Me
          </button>
        </div> 
      </nav>
      <img src="https://miro.medium.com/v2/resize:fit:1024/1*Ruim9pk0ZwNuBJYnUnmFaQ.png" alt="background" width="1920px" height="1080px";>
      <!-- Hero section  -->
      <div id="home" class="absolute top-[30rem] left-[29em] z-10">
        <div class="flex flex-col justify-center">
          <p class="text-center text-6xl text-white font-semibold font-Baloobhai2 mb-16 ">
            A Better Life Starts with a <br />
            Beautiful Smile
          </p>  
          <a href="#contact"
            class="text-white flex items-center justify-center bg-gradient-to-r from-blue-500 via-blue-600 to-blue-700 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-4 text-center mr-2 mb-2"
          >
          <svg class="w-6 h-6 mx-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg> 
         Exercise 
        </a>
        </div>
      </div>
    </header>

    <main>
      <div id="about" class="about-section my-6 mx-4 lg:my-10 lg:mx-24">
        <div>
          <img src="https://static.wixstatic.com/media/da7d32_884b73b1bfcd4742ac553a2c8539cf44~mv2.png/v1/fill/w_980,h_424,al_c,q_90,enc_auto/da7d32_884b73b1bfcd4742ac553a2c8539cf44~mv2.png" alt="background" width="1920px" height="1080px";>

      
          <!-- Left Section  -->
          <div class="lg:w-[45%]">
            <h1 class="lg:text-5xl text-2xl font-bold font-serif my-2 lg:my-4">
              Welcome to Su-Jok
             hand-foot therapy
            </h1>
            <p class="text-sm lg:text-base my-3">
              Sujok Therapy is a healing methodology based on Acupressure and is a simple method that produces highly effective results. 
              In Sujok therapy, the palm and foot represent all the active points in the body corresponding to all the organs or parts of
               the human body.
            </p>
          </div>
          <div class="lg:flex lg:justify-between">
            <div class="lg:w-[40%] lg:my-12 px-5">
              <div class="flex justify-center items-start my-4 lg:my-12">
                <div class="mt-[6px] mr-4 text-[&#xEE37;] ">
                 
                  <i class="ri-hospital-line"> 

                  </i>
                </div>
                <div>
                  
                  <h5 class="text-lg lg:text-xl font-bold lg:font-semibold">Friendly Clinic Near You</h5>
                  <p class="text-sm lg:text-base">We are always here to take care of your health.
                     and to give you all support till healing
                     </p>
                </div>
              </div>
  
              <div class="flex justify-center items-start my-4 lg:my-12">
                <div class="mt-[6px] mr-4 text-[#xF1EE;]">
                  <i class="ri-team-line"></i>
                </div>
                <div>
                  <img src="https://hand-microsurgery.com/img/Hand_Therapy.jpg" alt="logo" width="100";>                
                    <h5 class="text-lg lg:text-xl font-bold lg:font-semibold">Experienced therapist</h5>
                  <p>In Global level congress in Cyprus we decide uniform education policy for Sujok therapy for whole globe.
                     We decided various levels for SuJok therapists
                                  
                  1. SuJok for beginners
                  2. SuJok for Amateurs
                  3. SuJok for Professionals
                  4. SuJok for Specialist
                  (One program being organized in Nagpur for Diabetes)
                  5. SuJok for Experts
                  6. SuJok for Masters.
                    </p>
                </div>
              </div>
              <div class="flex items-center text-[#xF1EE;] cursor-pointer text-sm ml-8">
                <i class="ri-team-line"></i>
                <a href="" class="px-2">
                  <strong>View on Google Map</strong>
                </a>
              </div>
            </div>

            <!-- Right Section  -->
            <div class="hidden md:hidden w-[50%] m-auto my-8 lg:flex lg:items-end lg:justify-end">
              <img class="lg:relative w-44 lg:w-56 lg:left-52 lg:bottom-24 lg:z-30" src="C:\Users\akshama\OneDrive\Desktop\project1\images\assets1.jpg" alt="">
              <img class="lg:w-52 h-32 lg:relative lg:bottom-7" src="C:\Users\akshama\OneDrive\Desktop\project1\images\assets1.jpg" alt="">
              <img class="relative lg:top-30 lg:right-60- w-80 lg:w-52 lg:z-20" src="C:\Users\akshama\OneDrive\Desktop\project1\images\assets1.jpg" alt="">
            </div>
            <div class="w-3/4 m-auto lg:hidden p-4">
              <img class="my-8" src="./images/assets1.jpg" width="100%" alt="">
            </div>
          </div>
    
          <!-- Our Department  -->
          <div class="flex flex-col justify-center items-center my-12">
            <h2 class="text-2xl lg:text-4xl font-bold text-center font-serif">Our Organization</h2>
            <img src="./images/assets4.jpg" alt="clinic" width="m-auto" height="m-auto";
            >
          </div>

          <!-- About The Doctor  -->
                  
            <img src=".\images\assets3.jpg" alt="";>
            <div class="flex flex-col justify-start lg:w-[40%] lg:my-12 gap-y-6 px-4">
              <h3 class="text-2xl font-bold">A Natural Therapy</h3>
              <h3 class="hidden text-4xl font-bold">A Natural <br>Therapy</h3>
              <h4 class="text-xl font-semibold text-slate-700">which includes hand-foot point therapy,
                seed therapy,needle therapy,color therapy, moxa(heat therapy) and uses different execises.
              </h4>
              <p class="w-[90%] text-slate-600 text-sm font-medium">In Sujok therapy, 4 fundamental energy systems are approached. The Meridian system, the Chakra system, the Spiral energy system and the Diamond energy system.  The system of 12 main and 8 wonderful meridians is just one of the components of an Integral Energy system of the body. In addition to it, the body has a Chakra system (internal and external chakras), a multi-layer Zonal (spiral) energy network, and a Diamond energy system. The interrelation of all energy structures among themselves is well studied.</p>
              <div class="my-8">
                <h5 class="text-lg font-semibold">International Sujok Association</h5>
                <p class="text-sm text-slate-600 italic w-[90%]">ISA(Dr. Minchul park )</p>
              </div>
            </div>
            <div class="m-auto w-52 lg:hidden">
              <img src="/Images/DRImran2_sm.png" alt="">
            </div>
          </div>
        </div>
      </div>

      <!-- Contact Section  -->
      <section id="contact">
        <div class="w-full lg:w-[85%] bg-gradient-to-r from-blue-500 to-blue-700 lg:flex lg:justify-between lg:mt-10 py-12">
          <div class="lg:ml-24 py-10 lg:py-20 w-full lg:w-[50%] flex flex-col lg:items-start items-center place-content-start">
            <h3 class="text-3xl lg:text-3xl font-serif text-white font-bold">Smile welcoming to  new members</h3>
            <p class="text-lg lg:text-xl font-semibold w-[70%] my-4 text-slate-200">Are you a new member ?  Don't worry we're here to care with lots of care and love. Fill the form that given beside or just give a call.
            </p>
            <p class="text-xl lg:text-2xl text-white font-bold mt-4 lg:mt-10">NEED ASSISTANCE?</p>
            <p class="text-sm lg:text-xl text-white font-semibold cursor-pointer hover:underline my-4">+919389676456</p>
          </div>

          <div class="lg:w-[50%] px-2 lg:py-20 lg:z-30">
            <div class="px-2 py-8 flex flex-col lg:w-1/2 justify-center items-center bg-white rounded-xl shadow-2xl lg:relative lg:left-[26rem]">
              <input class="bg-slate-200 my-2 border-none rounded-sm text-sm font-mono" type="text" placeholder="Name">
              <input class="bg-slate-200 my-2 border-none rounded-sm text-sm font-mono" type="email" name="" id="" placeholder=" Email">
              <input class="bg-slate-200 my-2 border-none rounded-sm text-sm font-mono" type="text" name="" id="" placeholder=" Phone Number">
              <button class="py-2 px-6 border border-blue-500 rounded-md text-sm text-blue-500 font-semibold my-3 hover:bg-blue-500 hover:text-white hover:border-none">Submit</button>
            </div>
          </div>
          <img class="hidden lg:block absolute right-12" src="Images/dotsx2.png" alt=""> 
        </div>
      </section>
      
      <!-- Featured Section  -->
      <section class="bg-blue-100 py-12 px-24">
        <h2 class="text-2xl lg:text-4xl font-bold text-center my-2 lg:my-3">Complete Care on Your Schedule</h2>
        <h4 class="text-lg lg:text-xl font-semibold text-center my-2 lg:my-3">"Su" "Jok"</h4>
        <!-- Featured Card  -->
        <div class="flex flex-col md:flex-row lg:flex-row justify-center gap-y-6 lg:gap-x-10 my-14">
          <div>
            <div class="w-52 lg:w-60 h-56 lg:h-72 bg-white py-4 lg:py-6 px-3 lg:px-6 flex flex-col items-center rounded-lg">
              <span class="text-blue-600"><i class="fa-solid fa-user-doctor fa-2xl lg:fa-3x"></i></span>
              <h6 class="text-base lg:text-lg font-semibold text-center my-3">Experienced therapist​</h6>
              <p class="text-sm lg:text-base text-center">We have treated more than 3000+ patients and better their situation.</p>
            </div>
          </div>
  
          <div>
            <div class="w-52 lg:w-60 h-56 lg:h-72 bg-white py-4 lg:py-6 px-3 lg:px-6 flex flex-col items-center rounded-lg">
              <span class="text-blue-600"><i class="fa-solid fa-smile fa-2xl lg:fa-3x"></i></span>
              <h6 class="text-base lg:text-lg font-semibold text-center my-3">Using natural tools​​</h6>
              <p class="text-sm lg:text-base text-center">We treat you painlessly & providing a smile .</p>
            </div>
          </div>

          <div>
            <div class="w-52 lg:w-60 h-56 lg:h-72 bg-white py-4 lg:py-6 px-3 lg:px-6 flex flex-col items-center rounded-lg">
              <span class="text-blue-600"><i class="fa-solid fa-handshake fa-2xl lg:fa-3x"></i></span>
              <h6 class="text-base lg:text-lg font-semibold text-center my-3">Guaranteed Results​​</h6>
              <p class="text-sm lg:text-base text-center">We provide 100% guaranteed result with friendly service, minimal charge & comfortable surrounding, every time.</p>
            </div>
          </div>
          
          <div>
            <div class="w-52 lg:w-60 h-56 lg:h-72 bg-white py-4 lg:py-6 px-3 lg:px-6 flex flex-col items-center rounded-lg">
              <span class="text-blue-600"><i class="fa-solid fa-microscope fa-2xl lg:fa-3x"></i></span>
              <h6 class="text-base lg:text-lg font-semibold text-center my-3">Modern Equipment​</h6>
              <p class="text-sm lg:text-base text-center">We used modern equipments & facilities like AHCS sujok tool kit, pain reliver electrical equipment, needles different from accupressure.</p>
            </div>
          </div>
        </div>
      </section>

      <!-- Images Row  -->
      <!-- For Small Devices -->
      <section id="service" class=" mx-4 pt-8 flex flex-col justify-center items-center m-auto md:hidden lg:hidden">
          
          <div class="flex flex-col px-4 my-3">
            <h2 class="text-xl font-bold my-1">Various Services That We Offered</h2>
            <p class="text-slate-500 font-semibold">
              We are providing 100% healing and assuring that to relieve your disease completetly           </p>
          </div>
          
          <div class="flex m-auto">
            <div class="">
              <div class="text-black px-3 py-4 w-48 h-[15rem] bg-[url('Images/Service_1.png')] bg-no-repeat">
                <p class="text-black font-semibold">1.</p>
                <p class="text-black font-semibold">Many concepts and systems used in Sujok Therapy as will be stated here,are not part of Chinese Acupuncture. </p>
                <p class="text-slate-100 my-4 text-xs">In fact systems like Triorigin, Zone Energy Systems, Diamond Energy System, Six and Eight Energy Systems do not find and reference in the past but were all developed exclusively by Prof. Park, Jae Woo, the originator of the SUJOK Therapy. </p>
              </div>
            </div>
            
            <div>
              <div class="text-black px-3 py-4 w-48 h-[15rem] bg-[url('Images/Service_2.png')] bg-no-repeat">
                <p class="text-black font-semibold">2.</p>
                <p class="text-black font-semibold">Theoretical and philosophical basis </p>
                <p class="text-slate-100 my-4 text-xs">Chinese medicine is based on two basic concepts of Chinese philosophy: the Yin-Yang Law and the Five Elements Law (cycle of Wu-Xing: Wood, Fire, Earth, Metal and Water). These concepts and classifications are the basis of acupuncture, herbal medicine, curative gymnastics, manual techniques and other medical methods of Chinese medicine.</p>
              </div>
              </div>
        
          <div class="flex m-auto">
            <div class="">
              <div class="text-black px-3 py-4 w-48 h-[15rem] bg-[url('Images/Service_3.png')] bg-no-repeat">
                <p class="text-black font-semibold">3.</p>
                <p class="text-black font-semibold">The concept of energy system of the human body and its role in the occurrence of diseases:</p>
                <p class="text-slate-100 my-4 text-xs">In Chinese medicine, the system of energy paths (meridians) includes 12 main meridians and 8 wonderfulextraordinary meridians.</p>
              </div>
            </div>
            
            <div>
              <div class="text-black px-3 py-4 w-48 h-[15rem] bg-[url('Images/Service_4.png')] bg-no-repeat">
                <p class="text-black font-semibold">4.</p>
                <p class="text-black font-semibold">Diagnosis and treatment in the energy system:</p>
                <p class="text-slate-100 my-4 text-xs">In Chinese medicine, the effect of treatment comes from stimulation of the points of the body, located on meridian lines or out of them. The local approach to treatment and the general activation effect prevails in this system. As medical tools, they mainly use acupuncture, moxibustion and vacuum massage. </p>
              </div>
            </div>
          </div>

          <div class="flex m-auto">
            <div class="">
              <div class="text-black px-3 py-4 h-[15rem] w-48 bg-[url('Images/Service_5.png')] bg-no-repeat">
                <p class="text-black font-semibold">5.</p>
                <p class="text-black font-semibold">Magnetotherapy </p>
                <p class="text-slate-100 my-4 text-xs">Magnetotherapy is one of the most widely used treatment method in Sujok therapy. Magnets of different sizes and shapes allow a purposeful impact on energy structures, with the aim of inhibiting or toning them to establish homeostasis. The approach to treatment is purely individual.</p>
              </div>
            </div>
  
            <div>
              <div class="text-black px-3 py-6 h-[15rem] w-48 bg-[url('Images/Service_6.png')] bg-no-repeat">
                <p class="text-black font-semibold">6.</p>
                <p class="text-black font-semibold">Diet, food supplements and herbs:</p>
                <p class="text-slate-100 my-4 text-xs">In Chinese medicine, herbal medicine occupies a very important position. Selection of herbs, nutrition and food supplement is carried out according to the law of Yin-Yang and the Five Elements law.

                  In Sujok therapy recommendations for nutrition and use of herbs are based on the theory of Triorigin and 8 Energies. Given the details of these classifications, this is a very promising development with great potential
                  </p>
              </div>
            </div>
          </div>

          <div class="flex m-auto">
            <div class="">
              <div class="text-black px-3 py-4 h-[15rem] w-48 bg-[url('Images/Service_7.png')] bg-no-repeat">
                <p class="text-black font-semibold">7.</p>
                <p class="text-black font-semibold">Seed therapy ​</p>
                <p class="text-slate-100 my-4 text-xs">Seed therapy is one ofvery effective and unique curative methods in Sujok therapy. There are clearly defined criteria for selecting seeds for treatment, taking into consideration their shape, properties and characteristics of the plants growing from seeds. The application of seeds to the correspondence points concentrates seeds’ curative energy on a specific organ or body part.
                </p>
              </div>
            </div>
            
            <div>
              <div class="text-black px-3 py-6 h-[15rem] w-48 bg-[url('Images/Service_8.png')] bg-no-repeat">
                <p class="text-black font-semibold">8.</p>
                <p class="text-black font-semibold">Twist therapy​</p>
                <p class="text-slate-100 my-4 text-xs">which includes a wide variety of techniques (fixed twist, variable twist, elastic twist, twist massage, twist walking, twist of skin, respiratory twist, etc.), all of which are based on individually selected spiral movements. By itself, Twist therapy is independent and is a very effective method of treatment described in many books.

                  .</p>
              </div>
            </div>
          </div>

          <div class="px-6 py-8 bg-blue-500 w-full flex flex-col justify-center my-6">
            <p class="text-slate-100 text-sm font-bold">
              FOR ANY QUERY
            </p>
            <h2 class="text-lg font-bold text-white">Call us :- 9389676456</h2>
          </div>

      </section>

      <!-- For Large devices  -->
      <section id="services" class="hidden md:flex py-12 px-24 lg:flex  flex-col justify-center items-center w-[80%] m-auto ">
        <!-- Images Row 1  -->
        <div class="flex m-auto">
          <div class="w-[50%] flex flex-col px-8 content-end">
            <h2 class="text-3xl font-bold my-4 ">Various Services That We Offered</h2>
            <p class="text-slate-500 text-lg font-bold">
              We are providing 100% healing and assuring that to relieve your disease completetly   
            </p>
          </div>
          
          <div class="w-1/2 flex">
            <div class=" h-[17rem] bg-[url('Images/Service_1.png')] bg-no-repeat">
              <div class="text-black px-3 py-6 w-60">
                <p class="text-black font-semibold">1.</p>
                <p class="text-black font-semibold">Many concepts and systems used in Sujok Therapy as will be stated here,are not part of Chinese Acupuncture.</p>
                <p class="text-violate-300 my-4 text-sm">In fact systems like Triorigin, Zone Energy Systems, Diamond Energy System, Six and Eight Energy Systems do not find and reference in the past but were all developed exclusively by Prof. Park, Jae Woo, the originator of the SUJOK Therapy.</p>
              </div>
            </div>
            
            <div class=" h-[17rem] bg-[url('Images/Service_2.png')] bg-no-repeat">
              <div class="text-black px-3 py-6 w-60">
                <p class="text-black font-semibold">2.</p>
                <p class="text-black font-semibold">Theoretical and philosophical basis </p>
                <p class="text-violate-300 my-4 text-sm">Chinese medicine is based on two basic concepts of Chinese philosophy: the Yin-Yang Law and the Five Elements Law (cycle of Wu-Xing: Wood, Fire, Earth, Metal and Water).
                   These concepts and classifications are the basis of acupuncture, herbal medicine, curative gymnastics, manual techniques and other medical methods of Chinese medicine</p>
              </div>
            </div>
          </div>
        </div>
        <!-- Images Row 2  -->
        <div class="flex">
          <div class=" h-[17rem] bg-[url('Images/Service_3.png')] bg-no-repeat">
            <!--<div class="text-black px-3 py-6 w-60">
              <p class="text-black font-semibold">3.</p>
              <p class="text-black font-semibold">The concept of energy system of the human body and its role in the occurrence of diseases:</p>
              <p class="text-violate-100 my-4 text-sm">In Chinese medicine, the system of energy paths (meridians) includes 12 main meridians and 8 wonderfulextraordinary meridians.</p>
            </div>-->
          </div>
          
          <div class=" h-[17rem] bg-[url('Images/Service_4.png')] bg-no-repeat">
            <div class="text-black px-3 py-6 w-60">
              <p class="text-black font-semibold">4.</p>
              <p class="text-black font-semibold">Diagnosis and treatment in the energy system:</p>
              <p class="text-violate-100 my-4 text-sm"> In Chinese medicine, the effect of treatment comes from stimulation of the points of the body, located on meridian lines or out of them. The local approach to treatment and the general activation effect prevails in this system. As medical tools, they mainly use acupuncture, moxibustion and vacuum massage</p>
            </div>
          </div>

          <div class=" h-[17rem] bg-[url('Images/Service_5.png')] bg-no-repeat">
            <div class="text-black px-3 py-6 w-60">
              <p class="text-black font-semibold">5.</p>
              <p class="text-black font-semibold">Magnetotherapy </p>
              <p class="text-violate-100 my-4 text-sm">Magnetotherapy is one of the most widely used treatment method in Sujok therapy. Magnets of different sizes and shapes allow a purposeful impact on energy structures,The approach to treatment is purely individual.</p>
            </div>
          </div>

          <div class=" h-[17rem] bg-[url('Images/Service_6.png')] bg-no-repeat">
            <div class="text-black px-3 py-6 w-60">
              <p class="text-black font-semibold">6.</p>
              <p class="text-black font-semibold">Diet, food supplements and herbs:</p>
              <p class="text-violate-800 my-4">In Chinese medicine, herbal medicine occupies a very important position. Selection of herbs, nutrition and food supplement is carried out according to the law of Yin-Yang and the Five Elements law.
                In Sujok therapy recommendations for nutrition and use of herbs are based on the theory of Triorigin and 8 Energies. Given the details of these classifications, this is a very promising development with great potential</p>
            </div>
          </div>
        </div>
          <!-- Images Row 3  -->
        <div class="flex m-auto px-7">
                  
          <div class="flex">
            <div class=" h-[17rem] bg-[url('Images/Service_7.png')] bg-no-repeat">
              <div class="text-black px-3 py-6 w-60">
                <p class="text-black font-semibold">7.</p>
                <p class="text-black font-semibold">Seed therapy​</p>
                <p class="text-violate-100 my-4 text-sm">Seed therapy is one ofvery effective and unique curative methods in Sujok therapy. There are clearly defined criteria for selecting seeds for treatment, taking into consideration their shape, properties and characteristics of the plants growing from seeds
                </p>
              </div>
            </div>
            
            <div class=" h-[17rem] bg-[url('Images/Service_8.png')] bg-no-repeat">
              <div class="text-black px-3 py-6 w-60">
                <p class="text-black font-semibold">8.</p>
                <p class="text-black font-semibold">Twist therapy​​</p>
                <p class="text-violate-100 my-4 text-sm">which includes a wide variety of techniques (fixed twist, variable twist, elastic twist, twist massage, twist walking, twist of skin, respiratory twist, etc.), all of which are based on individually selected spiral movements. 
                </p>
              </div>
            </div>
        
          <div class="w-[30rem] px-14 bg-blue-500 flex flex-col justify-center rounded-br-full">
            <p class="text-slate-100 text-sm font-bold">
              FOR ANY QUERY
            </p>
            <h2 class="text-lg font-bold text-white">Call us :- 938967##</h2>
          </div>
        </div>
        </div>
      </section>

      <!-- Testimonials Section  -->
      <!-- For Small Devices  -->
      <section id="review" class="w-full bg-blue-100 my-10 lg:hidden">
        <h3 class="text-lg lg:text-3xl font-bold text-center py-2">Result After Treatment</h3>
        <div class="w-[80%] m-auto flex items-center lg:flex-row lg:gap-x-4 lg:py-10 py-6 gap-x-4 ">
          <img class="max-w-[45%] lg:w-full" src="/Images/Testimonial_1.png" alt="">
          <img class="max-w-[45%] lg:w-full" src="/Images/Testimonial_2.png" alt="">
        </div>
        <div class="w-[80%] m-auto flex items-center lg:flex-row lg:gap-x-4 lg:py-10 py-2 gap-x-4">
          <img class="max-w-[45%] lg:w-full" src="/Images/Testimonial_3.png" alt="">
          <img class="max-w-[45%] lg:w-full" src="/Images/Testimonial_4.png" alt="">
        </div>
        <p class="text-sm lg:text-base italic text-slate-600 text-center px-8 py-10">To see more testimonial visit our facebook page 👉 <a class="underline hover:text-blue-900" href="https://www.facebook.com/SUJOKWORLD/" target="_blank">SMILE SUJOK FOUNDATION(ISA)</a></p>
      </section>

      <!-- For Large Devices  -->
      <section id="reviews" class="w-full bg-blue-100 my-10 hidden lg:block">
        <h3 class="text-3xl font-bold text-center py-2">Result After Treatment</h3>
        <div class="w-[80%] m-auto flex items-center lg:flex-row lg:gap-x-4 lg:py-10 py-6 gap-x-4 ">
          <img class="max-w-[45%] lg:w-full" src="/Images/Testimonial_1.png" alt="">
          <img class="max-w-[45%] lg:w-full" src="/Images/Testimonial_2.png" alt="">
          <img class="max-w-[45%] lg:w-full" src="/Images/Testimonial_3.png" alt="">
          <img class="max-w-[45%] lg:w-full" src="/Images/Testimonial_4.png" alt="">
        </div>
        <p class="text-sm lg:text-base italic text-slate-600 text-center px-8 py-10">To see more testimonial visit our facebook page 👉 <a class="underline hover:text-blue-900" href="https://www.facebook.com/profile.php?id=100070483394854" target="_blank">Happy Smile Dental Clinic</a></p>
      </section>

      <!-- Feedback Section  -->
      <section class="bg-white py-8">
        <!-- Feedback Boxes  -->
        <!-- Small Devices  -->
        <div class="w-[80%] m-auto p-4 lg:hidden lg:justify-evenly">
          <div class="w-60 h-60">
            <h3 class="text-2xl font-bold text-center my-3">Happy Stories</h3>
            <p class="text-sm text-center my-3">Creating completely healed world, without any disease </p>
            <img class="w-40 m-auto" src="/Images/happy.jpg" alt="">
          </div>

          <div class="flex flex-col gap-y-4">
            <div class="bg-blue-50 w-72 px-4 py-9 shadow-xl">
              <p class="text-xs italic">after connecting with sujok. I am very happy with their services. Dr. Subhash  is very humble and knowledgeable person. I personally recommend sujok therapy for any disease.</p>
              <h6 class="text-sm font-semibold mt-5 mb-2">col. juskaran singh  bajaj</h6>
            </div>
  
            <div class="bg-blue-50 w-72 px-4 py-9 shadow-xl">
              <p class="text-xs italic">The best destination for your  health. I am glad and pleased about having a such doctor's clinic near my locality. You should check it out as per your requirement.</p>
              <h6 class="text-sm font-semibold mt-5 mb-2">Kishor chaudhry</h6>
            </div>
  
            <div class="bg-blue-50 w-72 px-4 py-9 shadow-xl">
              <p class="text-xs italic">
                The best place for treatment. The doctor is very polite and has advanced knowledge. Hygiene is maintained very well. I am very happy with his treatment. Thank you happy smile.</p>
              <h6 class="text-sm font-semibold mt-5 mb-2">Unnati sharma</h6>
            </div>
  
            <div class="bg-blue-50 w-72 px-4 py-9 shadow-xl">
              <p class="text-xs italic">
                I had a great experience at the Sujok clinic . Dr. Subhash was very friendly ,professional and knowledgeable .Thank you for your great service.</p>
              <h6 class="text-sm font-semibold mt-5 mb-2">Samarth</h6>
            </div>
  
            <div class="bg-blue-50 w-72 px-4 py-9 shadow-xl">
              <p class="text-xs italic">Polite, well mannered Doctor with good clinical evaluation skills. Shows a lot of patience and compassion with patients of all age groups. Highly recommended from my side .
              </p>
              <h6 class="text-sm font-semibold mt-5 mb-2">Dr. jugal kishor</h6>
            </div>
          </div>
        </div>
        <!-- For large devices  -->
        <div class="hidden md:flex w-[80%] m-auto p-4 lg:flex justify-evenly">
          <div class="box-1st">
            <div class="w-60 h-60">
              <h3 class="text-2xl font-bold">Happy Stories</h3>
              <p class="text-sm">Creating completely healed world<br> , without any disease </p>
              <img class="z-10 w-40" src="/Images/happy.jpg" alt="">
            </div>
            <div class="bg-blue-50 w-72 px-4 py-12 shadow-xl z-20">
              <p class="text-xs italic">after connecting with sujok. I am very happy with their services. Dr. Subhash  is very humble and knowledgeable person. I personally recommend sujok therapy for any disease.</p>
              <h6 class="text-sm font-semibold mt-5 mb-2">col. juskaran singh  bajaj</h6>
            </div>
          </div>

          <div class="box-2nd flex flex-col justify-between">
            <div class="bg-blue-50 w-72 px-4 py-12 shadow-xl z-20">
              <p class="text-xs italic">The best destination for your  health. I am glad and pleased about having a such doctor's clinic near my locality. You should check it out as per your requirement.</p>
              <h6 class="text-sm font-semibold mt-5 mb-2">Kishor chaudhry</h6>
            </div>

            <div class="bg-blue-50 w-72 px-4 py-12 shadow-xl z-20 ">
              <p class="text-xs italic">
                The best place for treatment. The doctor is very polite and has advanced knowledge. Hygiene is maintained very well. I am very happy with his treatment. Thank you happy smile</p>
              <h6 class="text-sm font-semibold mt-5 mb-2">Unnati sharma</h6>
            </div>
          </div>

          <div class="box-3rd flex flex-col justify-between">
            <div class="bg-blue-50 w-72 px-4 py-12 shadow-xl z-20">
              <p class="text-xs italic">
                I had a great experience at the Sujok clinic . Dr. Subhash was very friendly ,professional and knowledgeable .Thank you for your great service.</p>
              <h6 class="text-sm font-semibold mt-5 mb-2">Samarth</h6>
            </div>

            <div class="bg-blue-50 w-72 px-4 py-12 shadow-xl z-20">
              <p class="text-xs italic">Polite, well mannered Doctor with good clinical evaluation skills. Shows a lot of patience and compassion with patients of all age groups. Highly recommended from my side .
              </p>
              <h6 class="text-sm font-semibold mt-5 mb-2">Dr. jugal kishor</h6>
            </div>
          </div>
        </div>
      </section>

      <!-- Location  -->
      <section id="call">
        <h4 class="text-center text-xl lg:text-3xl my-4 font-bold">How To Find Us</h4>
        <div class="bg-blue-600 flex flex-col lg:flex-row justify-center items-center lg:justify-evenly py-14 my-8">
          <div class="text-white flex justify-between lg:items-center py-2 lg:py-4  ml-6">
            <span class="bg-[#d2edff2e] rounded-full w-10 h-10 flex justify-center items-center mx-3"><i class="fa-solid fa-map-location-dot"></i></span>
            <div>
              <p class="text-base lg:text-xl">Address</p>
              <p class="text-xs lg:text-sm">Smile sujok clinic Deheradun,uttrakhand,India <br>
                Uttrakhand, India 248001</p> 
            </div>
          </div>
          
          <div class="text-white flex justify-between lg:items-center py-4 ml-[13px]">
            <span class="bg-[#d2edff2e] rounded-full w-10 h-10 flex justify-center items-center mx-2"><i class="fa-solid fa-mobile-screen-button"></i></span>
            <div>
              <p class="text-base lg:text-xl">Phone</p>
              <p class="text-xs lg:text-sm">+916297524875 /
                +918768610974</p> 
            </div>
          </div>

          <div class="text-white flex justify-between lg:items-center py-4">
            <span class="bg-[#d2edff2e] rounded-full w-10 h-10 flex justify-center items-center mx-3"><i class="fa-solid fa-envelope"></i></span>
            <div>
              <p class="text-base lg:text-xl">Email</p>
              <p class="text-xs lg:text-sm">smilesujokindia@gmail.com</p> 
            </div>
          </div>
        </div>
        <div class="m-auto flex justify-center items-center my-6">
          <button onclick="openMap()" class=" relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium text-gray-900 rounded-lg group bg-gradient-to-br from-cyan-500 to-blue-500 group-hover:from-cyan-500 group-hover:to-blue-500 hover:text-white dark:text-white focus:ring-4 focus:outline-none focus:ring-cyan-200 dark:focus:ring-cyan-800">
            <span class="flex items-center gap-x-2 relative px-5 py-2.5 transition-all ease-in duration-75 bg-white dark:bg-gray-900 rounded-md group-hover:bg-opacity-0">
                <span><i class="fa-solid fa-location-dot"></i></span>
                <p>View On Google Map</p>
            </span>
          </button>
        </div>
        <div class="my-4">
          <img src="/Images/gmap." alt="HappySmilemap">
        </div>
      </section>
    </main>

    <footer class="w-full px-12 py-10 bg-[#1D3157] text-white">
      <div class="text-slate-300 underline text-sm text-right animate-bounce my-2"><a href="#home" >Back To Top </a></div>
      <section class="w-full lg:m-auto flex flex-col lg:flex-row lg:justify-between ">
        <p class="sm:text-center">Copyright © 2023 SmileSu-jok | Powered by <a class="text-yellow-300 hover:underline hover:text-yellow-600" href="https://skriponux.com" target="_blank">AKSHAMA</a> </p>
        <div class="flex items-center justify-center lg:gap-x-7 lg:content-end lg:ml-96 mt-5 gap-x-4">
          
          <a href="https://www.linkedin.com/in/sk-ripon-a82a7b222/" target="_blank" class="hover:text-blue-400"><i class="fa-brands fa-linkedin-in fa-xl"></i></span>
          <a href="https://mail.google.com/mail/u/0/#inbox?compose=new" target="_blank" class="hover:text-fuchsia-300"><i class="fa-regular fa-envelope fa-xl"></i></span>
          <a href="https://twitter.com/myself_ripon/" target="_blank" class="hover:text-sky-400"><i class="fa-brands fa-twitter fa-xl"></i></span>
        </div>
      </section>
    </footer>

    <script src="index.js"></script>
    <script src="https://unpkg.com/flowbite@1.5.4/dist/flowbite.js"></script>
  </body>
</html>
