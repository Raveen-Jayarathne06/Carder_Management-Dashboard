<template>
<section class="bg-gray-50 dark:bg-gray-900">
  <div class="flex flex-col items-center justify-center px-6 py-8 mx-auto md:h-screen lg:py-0">
    <img id="profile-img" src="src\assets\images.png" class="profile-img" />
             
      
    <div class="w-full bg-white rounded-lg shadow dark:border md:mt-0 sm:max-w-md xl:p-0 dark:bg-gray-800 dark:border-gray-700">
    <div class="p-6 space-y-4 md:space-y-6 sm:p-8">
        <h1 class="text-xl text-center font-bold leading-tight tracking-tight text-gray-900 md:text-2xl dark:text-white">
            Login to Carder Management System
        </h1>
        <form class="space-y-4 md:space-y-6" action="#">
            <div class="relative">
                <label for="username" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">
                    <input type="text" name="username" id="username" placeholder="UserName" class="bg-gray-50 border text-center border-gray-300 text-black sm:text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 pr-8 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-900 dark:text-white dark:focus:ring-sky-800 dark:focus:border-sky-800 hover:bg-gray-300" required="true">
                    <img src="../assets/download.png" alt="Username Icon" class="absolute left-2 top-1/2 transform -translate-y-1/2 h-4 w-4">
                </label>
                     
                  </div>

                  <div class="relative">
                <label for="password" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">
                    <input type="text" name="password" id="password" placeholder="Password" class="bg-gray-50 border text-center border-gray-300 text-black sm:text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 pr-8 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-sky-800 dark:focus:border-sky-800 hover:bg-gray-300" required="true">
                    <img src="../assets/imgp2.png" alt="Username Icon" class="absolute left-2 top-1/2 transform -translate-y-1/2 h-4 w-4">
                </label>
             </div>
             <div class="text-right text-gray-600 hover:text-sky-800">
                <a href="">Forget Password?</a>
             </div>
                 
                  
                  <button type="submit" class="w-full text-black bg-sky-600 hover:bg-sky-700 focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800">Login</button>
                  
                
              </form>
          </div>
      </div>
  </div> 
</section>
</template>