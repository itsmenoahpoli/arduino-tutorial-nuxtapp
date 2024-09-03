<script lang="ts" setup>
useSeoMeta({
  title: "Admin - Videos",
});

definePageMeta({
  layout: "admin",
});
</script>

<template>
  <div class="w-full border">
    <div class="relative overflow-x-auto w-full">
      <table class="w-full text-sm text-left rtl:text-right text-white">
        <thead class="text-xs text-white uppercase bg-pink-700">
          <tr>
            <th scope="col" class="px-6 py-3">Videos</th>
            <th scope="col" class="px-6 py-3">Name</th>
            <th scope="col" class="px-6 py-3">Edit</th>
            <th scope="col" class="px-6 py-3">Remove</th>
          </tr>
        </thead>
        <tbody>
          <tr class="bg-white border-b border-gray-200">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-1.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #1)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white border-b border-gray-200">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-2.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #2)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
          <tr class="bg-white">
            <td scope="row" class="px-6 py-4 font-medium bg-pink-100">
              <img src="assets/tutorial-3.jpg" alt="tutorial-img" class="w-[200px] h-[200px]" />
            </td>
            <td class="px-6 py-4 bg-pink-100 text-gray-900">How to: setup arduino (Tutorial #3)</td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:edit" size="24" /> Edit
              </button>
            </td>
            <td class="px-6 py-4">
              <button class="text-black text-sm font-bold uppercase flex flex-row items-center gap-x-2">
                <Icon name="uil:trash-alt" size="24" /> Delete
              </button>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
