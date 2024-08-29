<script lang="ts" setup>
import { useForm } from "vue-hooks-form";

useHead({
  title: "Admin - Login",
});

definePageMeta({
  layout: "auth",
});

const { useField, handleSubmit } = useForm();
const fields = {
  email: useField("email", { rule: { required: true } }),
  password: useField("password", { rule: { required: true } }),
};

const onSubmit = handleSubmit((formData) => {
  console.log(formData);
});
</script>

<template>
  <div class="min-h-screen w-full flex justify-center items-center bg-slate-950">
    <div class="w-[500px] bg-white rounded-md p-10">
      <h1 class="text-center text-xl font-bold">ADMIN LOGIN</h1>

      <form class="flex flex-col gap-y-3 mt-8" @submit="onSubmit">
        <div class="flex flex-col gap-y-2">
          <p>Email</p>
          <input type="email" class="w-full h-[40px] text-xs border border-gray-400 rounded-md px-3" required />
        </div>

        <div class="flex flex-col gap-y-2">
          <p>Password</p>
          <input type="password" class="w-full h-[40px] text-xs border border-gray-400 rounded-md px-3" required />
        </div>

        <button type="submit" class="w-full h-[40px] text-white bg-green-700 rounded-md">Login</button>
      </form>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
