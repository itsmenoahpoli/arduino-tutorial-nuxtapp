<script lang="ts" setup>
import { useForm } from "vue-hooks-form";

interface Credentials {
  email: string;
  password: string;
}

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
  const { email, password } = formData as Credentials;

  if (email === "admin@domain.com" && password === "password") {
    window.location.href = "/admin/home";

    return;
  }

  alert("Incorrect/invalid account credentials provided");
});
</script>

<template>
  <div class="min-h-screen w-full flex justify-center items-center bg-blue-900">
    <div class="w-[500px] bg-white rounded-md p-10">
      <h1 class="text-center text-xl font-bold">ADMIN LOGIN</h1>

      <form class="flex flex-col gap-y-3 mt-8" @submit="onSubmit">
        <div class="flex flex-col gap-y-2">
          <p>Email</p>
          <input
            type="email"
            v-model="fields.email.value"
            :ref="fields.email.ref"
            class="w-full h-[40px] text-xs border border-gray-400 rounded-md px-3"
            required
          />
        </div>

        <div class="flex flex-col gap-y-2">
          <p>Password</p>
          <input
            type="password"
            v-model="fields.password.value"
            :ref="fields.password.ref"
            class="w-full h-[40px] text-xs border border-gray-400 rounded-md px-3"
            required
          />
        </div>

        <button type="submit" class="w-full h-[40px] text-white bg-green-700 rounded-md">Login</button>
      </form>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
