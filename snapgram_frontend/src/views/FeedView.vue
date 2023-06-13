<template>
  <div class="max-w-7xl mx-auto grid grid-cols-4 gap-4">
      <div class="main-left col-span-1">
          <div class="p-4 bg-white border border-gray-200 text-center rounded-lg">
              <img src="https://i.pravatar.cc/40?img=70" class="mb-6 rounded-full">

              <p><strong>Johnson Kaberere</strong></p>

              <div class="mt-6 flex space-x-8 justify-around">
                  <p class="text-xs text-gray-500">200 friends</p>
                  <p class="text-xs text-gray-500">20 posts</p>
              </div>
          </div>
      </div>

      <div class="main-center col-span-2 space-y-4">
           <div class="bg-white border border-gray-200 rounded-lg">
               <div class="p-4">
                   <textarea class="p-4 w-full bg-gray-100 rounded-lg" placeholder="What are you thinking about?"></textarea>
               </div>

               <div class="p-4 border-t border-gray-100 flex justify-between">
                   <a href="#" class="inline-block py-4 px-6 bg-gray-600 text-white rounded-lg">Attach image</a>
                   <a href="#" class="inline-block py-4 px-6 bg-purple-600 text-white rounded-lg">Post</a>
               </div>
           </div>

      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>