<script>
import { page } from "$app/stores";

</script>
<div class="flex">
      <div class=" w-72 bg-gray-700">
          <div class="h-16 text-4xl bg-gray-900 pt-2 pl-10 cursor-pointer font-extrabold  ">
            <span class="text-white">Work</span><span class="text-blue-400">cation</span>
          </div>

          <div class="flex pt-5 pl-3 font-bold text-gray-400">
            <p class="pr-1">Bedrooms</p>
            <p class="pl-14">Bathrooms</p>
          </div>
          <div class="flex mt-1 space-x-5 pl-2 text-white">
            <button class="rounded-xl h-11 w-28 bg-gray-400 hover:bg-black hover:text-white hover:font-semibold">4</button>
            <button class=" rounded-xl h-11 w-28 bg-gray-400 hover:bg-black hover:text-white hover:font-semibold">4</button>
          </div>

          <div class="flex pt-3 pl-3 font-bold text-gray-400">
            <p class="pr-1">Price Range</p>
          </div>
          <div class="flex mt-1 space-x-5 pl-2 text-white">
            <button class=" rounded-xl h-11 w-64 bg-gray-400 hover:bg-black hover:text-white hover:font-semibold">Up to $2,000/wk</button>
          </div>

               <hr class="w-96 mt-8 ">

          <div class="pt-5 pl-3 font-bold text-gray-400">
            <p class="pr-1">Property Type</p>
          </div>
        <div class="text-white">
          <div>
            <label class="inherit items-center pl-3">
            <input type="radio" class="text-black" name="Property Type" value="personal">
                House
            </label>
          </div>
          <div>
            <label class="inherit items-center pl-3">
            <input type="radio" class="form-radio" name="Property Type" value="busines">
                Appartment
            </label>
          </div>
          <div>
            <label class="inline items-center pl-3">
            <input type="radio" class="form-radio" name="Property Type" value="busines">
                Loft
            </label>
          </div>
          <div>
            <label class="inline items-center pl-3">
            <input type="radio" class="form-radio" name="Property Type" value="busines">
                Townhouse
            </label>
          </div> 
          </div>    
              <hr class="w-96 mt-8 ">
      <div class="pt-5 pl-3 font-bold text-gray-400">
        <p class="pr-1">Amenities</p>
      </div>
          <div class="text-white">
            <div class="block">
              <label class="inline-flex items-center pl-3">
              <input type="checkbox" class="form-checkbox" checked>
                  <span class="ml-2">Balcony</span>
              </label>
            </div>
            <div>
              <label class="inline-flex items-center pl-3">
              <input type="checkbox" class="form-checkbox">
                  <span class="ml-2">Air-conditioner</span>
              </label>
            </div>
            <div>
              <label class="inline-flex items-center pl-3">
              <input type="checkbox" class="form-checkbox">
                  <span class="ml-2">Pool</span>
              </label>
            </div>
            <div>
              <label class="inline-flex items-center pl-3">
              <input type="checkbox" class="form-checkbox">
                  <span class="ml-2">beach</span>
              </label>
            </div>
            <div>
              <label class="inline-flex items-center pl-3">
              <input type="checkbox" class="form-checkbox">
                  <span class="ml-2">Parking</span>
              </label>
            </div>
            <div>
              <label class="inline-flex items-center pl-3">
              <input type="checkbox" class="form-checkbox">
                  <span class="ml-2">Kit friendly</span>
              </label>
            </div>
            <div>
              <label class="inline-flex items-center pl-3">
              <input type="checkbox" class="form-checkbox">
                  <span class="ml-2">Pet friendly</span>
              </label>
            </div>
          </div>

            <div class="h-20 text-xl bg-gray-900 pt-4 pl-3 cursor-pointer">
                 <button class=" rounded-lg  font-bold h-11 w-64 bg-blue-400 hover:bg-black hover:text-blue-400 hover:font-semibold">Update Results</button>
            </div>
      </div>
      <div>
        <div class="">
            <div class="pl-8 pt-4 flex ">
              <input type="text" class=" rounded-lg bg-gray-300 px-4 w-72 h-10" placeholder="Search">

              <ul class=" pl-36 flex space-x-12 text-xl font-bold justify-items-end">
            
              <li class="cursor-pointer pl-48 hover:text-black">Property</li>
  
              <li class="cursor-pointer hover:text-black">Trips</li>
  
              <li class="cursor-pointer hover:text-black">Messages</li>
      
              <li class="cursor-pointer hover:text-black">Support</li>
              
                <img src="girl1.png" class=" cursor-pointer pr-4 h-12 w-12 pb-3" alt="">
              
              </ul>
            </div>
            
            
      </div>
            
        <div class="bg-gray-200">
            <p class="pl-8 font-semibold pt-1 text-xl">Los Angeles</p>
            <p class="pl-8 text-gray-500">Live like the stars in these luxirious Southern California estates</p>
          <div class="flex cursor-pointer">
            <div class="pl-8 pt-3">
              <img src="modern home.jpg" class="rounded-lg h-64 w-64" alt="">
            </div>
            <div class="pl-8 pt-3">
              <img src="isolated house.jpg" class="rounded-lg h-64 w-64" alt="">
            </div>
            <div class="pl-8 pt-3">
              <img src="dream home.jpg" class="rounded-lg h-64 w-64" alt="">
            </div>
            <div class="pl-8 pt-3">
              <img src="large house.jpg" class="rounded-lg h-64 w-64" alt="">
            </div>
            
        </div>

        <div class="bg-gray-200">
          <p class="pl-8 font-semibold pt-6 text-xl">Phoenix</p>
          <p class="pl-8 text-gray-500">Escape the cold and enjoy great weather without breaking the bank</p>
        <div class="flex cursor-pointer">
          <div class="pl-8 pt-3">
            <img src="modern home.jpg" class="rounded-lg h-64 w-64" alt="">
          </div>
          <div class="pl-8 pt-3">
            <img src="isolated house.jpg" class="rounded-lg h-64 w-64" alt="">
          </div>
          <div class="pl-8 pt-3">
            <img src="dream home.jpg" class="rounded-lg h-64 w-64" alt="">
          </div>
          <div class="pl-8 pt-3">
            <img src="large house.jpg" class="rounded-lg h-64 w-64" alt="">
          </div>
          </div>
      </div>

        
      </div>
      </div>
</div>



