<template>
  <div
    class="fixed top-0 z-50 w-full bg-sky-800 border-gray-200 dark:bg-gray-800 dark:border-gray-700"
  >
    <div class="px-3 py-4 lg:px-5 lg:pl-3">
      <div class="flex items-center justify-between">
        <div class="flex items-center justify-start rtl:justify-end">
          <h1
            class="text-center text-3xl font-bold sm:text-3xl whitespace-nowrap text-white dark:text-white"
          >
            Carder Management System
          </h1>
        </div>
      </div>
    </div>
  </div>
  <aside
    id="logo-sidebar"
    class="fixed top-0 left-0 z-20 w-80 h-screen pt-20 transition-transform -translate-x-full bg-white sm:translate-x-0 dark:bg-gray-800 dark:border-gray-700"
    aria-label="Sidebar"
  >
    <div class="h-full px-3 pb-4 overflow-y-auto bg-white dark:bg-gray-800">
      <ul class="space-y-2 text-lg font-semibold">
        <li>
          <a
            href="#"
            class="flex items-center p-2 h-20 bg-sky-900 text-white dark:text-white hover:bg-sky-700 dark:hover:bg-gray-700 group"
          >
            <span class="ms-3">User Management</span>
          </a>
        </li>

        <li>
          <a
            href="#"
            class="flex items-center p-2 h-20 bg-sky-900 text-white dark:text-white hover:bg-sky-700 dark:hover:bg-gray-700 group"
          >
            <span class="flex-1 ms-3 whitespace-nowrap">View Carder</span>
          </a>
        </li>
        <li>
          <a
            href="#"
            class="flex items-center p-2 h-20 bg-sky-900 text-white dark:text-white hover:bg-sky-700 dark:hover:bg-gray-700 group"
          >
            <span class="flex-1 ms-3 whitespace-nowrap">Update Carder</span>
          </a>
        </li>
        <li>
          <a
            href="#"
            class="flex items-center p-2 h-20 bg-sky-900 text-white dark:text-white hover:bg-sky-700 dark:hover:bg-gray-700 group"
          >
            <span class="flex-1 ms-3 whitespace-nowrap">Users</span>
          </a>
        </li>
        <li>
          <a
            href="#"
            class="flex items-center p-2 h-20 text-white bg-sky-900 dark:text-white hover:bg-sky-700 dark:hover:bg-gray-700 group"
          >
            <span class="flex-1 ms-3 whitespace-nowrap">Report Generator</span>
          </a>
        </li>
      </ul>
    </div>
  </aside>
  <br />
  <br />
  <br />
  <br />

  <div class=" flex flex-row">
    <br />
    <br />
    <div class="basis-1/4">01</div>
    <div class="basis-1/4">
      <form class="max-w-sm mx-auto">
        <div class="mb-5">
          <h1><center>Basic Information</center></h1>
          <label
            for="email"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >NIC</label
          >
          <input
            type="email"
            id="email"
            class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light"
            required
          />
        </div>

        <div class="mb-5">
          <label
            for="password"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Username</label
          >
          <input
            type="password"
            id="password"
            class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light"
            required
          />
        </div>

        <div class="mb-5">
          <label
            for="large-input"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Full Name</label
          >
          <input
            type="text"
            id="large-input"
            class="block w-full p-6 text-gray-900 border border-gray-300 rounded-lg bg-gray-50 sm:text-md focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
          />
        </div>

        <div class="mb-5">
          <label
            for="password"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Name with Initials</label
          >
          <input
            type="password"
            id="password"
            class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light"
            required
          />
        </div>

        <div class="mb-5">
          <label
            for="repeat-password"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Designation</label
          >
          <input
            type="password"
            id="repeat-password"
            class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light"
            required
          />
        </div>

        <div class="mb-5">
          <label
            for="password"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Institute</label
          >
          <input
            type="password"
            id="password"
            class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light"
            required
          />
        </div>

        <div class="mb-5">
          <label
            for="password"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Email</label
          >
          <input
            type="password"
            id="password"
            class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light"
            required
          />
        </div>

        <div class="mb-5">
          <label
            for="password"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Land Line</label
          >
          <input
            type="password"
            id="password"
            class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light"
            required
          />
        </div>

        <div class="mb-5">
          <label
            for="password"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Mobile No</label
          >
          <input
            type="password"
            id="password"
            class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500 dark:shadow-sm-light"
            required
          />
        </div>
        <div class="flex flex-row">
          <div class="basis-1/2">
            <button
              type="submit"
              class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
            >
              Approve
            </button>
          </div>
          <div class="basis-1/2">
            <button
              type="submit"
              class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
            >
              Reject
            </button>
          </div>
        </div>
      </form>
    </div>
    <br />
    
    <div class="basis-1/2">
















        



        









































      <!-- <div class="flex items-center mb-5"><center>cctfyfyfhchfc</center></div> -->
      <h1><center>View Document</center></h1>
      <br />
      <form>
          <div>
            <form class="max-w-sm mx-auto">
              <div class="border-4 border-indigo-600 flex flex-row">
                <div class="basis-1/2">
                  <div class="flex items-center mb-6">
                    <center>
                     Office ID/NIC Copy 
                     <button type="button" class="py-2.5 px-5 me-2 mb-2 text-sm font-medium text-gray-900 focus:outline-none bg-white rounded-lg border border-gray-200 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700">Alternative</button>
                    </center>
                  </div>
                  <div class="flex items-center mb-5">
                    <center>
                     Request Letter <button type="button" class="py-2.5 px-5 me-2 mb-2 text-sm font-medium text-gray-900 focus:outline-none bg-white rounded-lg border border-gray-200 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700">Alternative</button>
                    </center>
                  </div>
                  
                  
                  
                  
                </div>
              </div>
            </form>
          </div>
        </form>





      <center>
        <!-- Office ID/NIC Copy
        <button
          type="button"
          class="py-2.5 px-5 me-2 mb-2 text-sm font-medium text-gray-900 focus:outline-none bg-white rounded-lg border border-gray-200 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700"
        >
          View
        </button>
        <br />
        <br />Request Letter
        <button
          type="button"
          class="py-2.5 px-5 me-2 mb-2 text-sm font-medium text-gray-900 focus:outline-none bg-white rounded-lg border border-gray-200 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700"
        >
          View</button
        ><br /><br /><br /><br /><br /><br />Roles -->

        <br /><br /><br /><br />

        <form>
          <div>
            <form class="max-w-sm mx-auto">
              <div class="border-4 border-indigo-600 flex flex-row">
                <div class="basis-1/2">
                  <div class="flex items-center mb-5">
                    <input
                      checked
                      id="checkbox-1"
                      type="checkbox"
                      value=""
                      class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                    />
                    <label
                      for="checkbox-1"
                      class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                      >Role 1</label
                    >
                  </div>
                  <div class="basis-1/2">
                    <div class="flex items-center mb-5">
                      <input
                        checked
                        id="checkbox-1"
                        type="checkbox"
                        value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                      />
                      <label
                        for="checkbox-1"
                        class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                        >Role 2</label
                      >
                    </div>
                  </div>
                  <div class="basis-1/2">
                    <div class="flex items-center mb-5">
                      <input
                        checked
                        id="checkbox-1"
                        type="checkbox"
                        value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                      />
                      <label
                        for="checkbox-1"
                        class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                        >Role 3</label
                      >
                    </div>
                  </div>
                  <div class="basis-1/2">
                    <div class="flex items-center mb-5">
                      <input
                        checked
                        id="checkbox-1"
                        type="checkbox"
                        value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                      />
                      <label
                        for="checkbox-1"
                        class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                        >Role 4</label
                      >
                    </div>
                  </div>
                  <div class="basis-1/2">
                    <div class="flex items-center mb-5">
                      <input
                        checked
                        id="checkbox-1"
                        type="checkbox"
                        value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                      />
                      <label
                        for="checkbox-1"
                        class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                        >Role 5</label
                      >
                    </div>
                  </div>
                </div>
                <div class="basis-1/2">
                  <div class="flex items-center mb-5">
                    <input
                      checked
                      id="checkbox-1"
                      type="checkbox"
                      value=""
                      class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                    />
                    <label
                      for="checkbox-1"
                      class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                      >Role 6</label
                    >
                  </div>
                  <div class="basis-1/2">
                    <div class="flex items-center mb-5">
                      <input
                        checked
                        id="checkbox-1"
                        type="checkbox"
                        value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                      />
                      <label
                        for="checkbox-1"
                        class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                        >Role 7</label
                      >
                    </div>
                  </div>
                  <div class="basis-1/2">
                    <div class="flex items-center mb-5">
                      <input
                        checked
                        id="checkbox-1"
                        type="checkbox"
                        value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                      />
                      <label
                        for="checkbox-1"
                        class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                        >Role 8</label
                      >
                    </div>
                  </div>
                  <div class="basis-1/2">
                    <div class="flex items-center mb-5">
                      <input
                        checked
                        id="checkbox-1"
                        type="checkbox"
                        value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                      />
                      <label
                        for="checkbox-1"
                        class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                        >Role 9</label
                      >
                    </div>
                  </div>
                  <div class="basis-1/2">
                    <div class="flex items-center mb-5">
                      <input
                        checked
                        id="checkbox-1"
                        type="checkbox"
                        value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
                      />
                      <label
                        for="checkbox-1"
                        class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                        >Role 10</label
                      >
                    </div>
                  </div>
                </div>
              </div>
            </form>
          </div>
        </form>
      </center>
    </div>
  </div>
</template>
