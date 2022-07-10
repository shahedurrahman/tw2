<template>
    <h2 class="mb-4 text-3xl">Welcome back!</h2>
    <div class="grid gap-y-4">
        <Input type="text" name="username" id="username" placeholder="Username"></Input>
        <Input type="password" name="password" id="password" placeholder="Password"></Input>
        <a href="" class="-mt-3 justify-self-end">Forgot password?</a>
        <Button text="Sign In"></Button>
        <div class="flex items-center mt-6">
            <div class="flex-grow border-t border-gray-300"></div>
            <div class="flex-shrink mx-4">or continue with</div>
            <div class="flex-grow border-t border-gray-300"></div>
        </div>
        <div class="flex justify-between">
            <a href="" class="border-solid border p-2 rounded-xl border-gray-200">
                <svg xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 48 48" width="48px" height="48px"><path fill="#FFC107" d="M43.611,20.083H42V20H24v8h11.303c-1.649,4.657-6.08,8-11.303,8c-6.627,0-12-5.373-12-12c0-6.627,5.373-12,12-12c3.059,0,5.842,1.154,7.961,3.039l5.657-5.657C34.046,6.053,29.268,4,24,4C12.955,4,4,12.955,4,24c0,11.045,8.955,20,20,20c11.045,0,20-8.955,20-20C44,22.659,43.862,21.35,43.611,20.083z"/><path fill="#FF3D00" d="M6.306,14.691l6.571,4.819C14.655,15.108,18.961,12,24,12c3.059,0,5.842,1.154,7.961,3.039l5.657-5.657C34.046,6.053,29.268,4,24,4C16.318,4,9.656,8.337,6.306,14.691z"/><path fill="#4CAF50" d="M24,44c5.166,0,9.86-1.977,13.409-5.192l-6.19-5.238C29.211,35.091,26.715,36,24,36c-5.202,0-9.619-3.317-11.283-7.946l-6.522,5.025C9.505,39.556,16.227,44,24,44z"/><path fill="#1976D2" d="M43.611,20.083H42V20H24v8h11.303c-0.792,2.237-2.231,4.166-4.087,5.571c0.001-0.001,0.002-0.001,0.003-0.002l6.19,5.238C36.971,39.205,44,34,44,24C44,22.659,43.862,21.35,43.611,20.083z"/></svg>    
            </a>
            <a href="" class="border-solid border p-2 rounded-xl border-gray-200">
                <svg xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 48 48" width="48px" height="48px"><linearGradient id="Ld6sqrtcxMyckEl6xeDdMa" x1="9.993" x2="40.615" y1="9.993" y2="40.615" gradientUnits="userSpaceOnUse"><stop offset="0" stop-color="#2aa4f4"/><stop offset="1" stop-color="#007ad9"/></linearGradient><path fill="url(#Ld6sqrtcxMyckEl6xeDdMa)" d="M24,4C12.954,4,4,12.954,4,24s8.954,20,20,20s20-8.954,20-20S35.046,4,24,4z"/><path fill="#fff" d="M26.707,29.301h5.176l0.813-5.258h-5.989v-2.874c0-2.184,0.714-4.121,2.757-4.121h3.283V12.46 c-0.577-0.078-1.797-0.248-4.102-0.248c-4.814,0-7.636,2.542-7.636,8.334v3.498H16.06v5.258h4.948v14.452 C21.988,43.9,22.981,44,24,44c0.921,0,1.82-0.084,2.707-0.204V29.301z"/></svg>
            </a>
            <a href="" class="border-solid border p-2 rounded-xl border-gray-200">
                <svg xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 48 48" width="48px" height="48px"><path fill="#42A5F5" d="M40.084,32.613c-0.848,1.835-1.254,2.655-2.342,4.274c-1.521,2.264-3.67,5.089-6.326,5.109c-2.361,0.018-2.971-1.507-6.176-1.482c-3.204,0.016-3.872,1.51-6.237,1.484c-2.654-0.022-4.688-2.568-6.21-4.826c-4.259-6.34-4.707-13.768-2.076-17.721c1.861-2.803,4.807-4.449,7.572-4.449c2.817,0,4.588,1.514,6.916,1.514c2.262,0,3.638-1.517,6.896-1.517c2.464,0,5.07,1.313,6.931,3.575C32.942,21.836,33.931,30.337,40.084,32.613z"/><path fill="#42A5F5" d="M30.046,12.072c1.269-1.577,2.232-3.804,1.882-6.072c-2.069,0.138-4.491,1.418-5.905,3.075c-1.282,1.51-2.345,3.752-1.931,5.922C26.351,15.066,28.689,13.764,30.046,12.072z"/><path fill="#1E88E5" d="M36.736,20.421C28,30.001,20,21.001,9.228,27.842c0.375,3.027,1.53,6.303,3.565,9.331c1.521,2.258,3.556,4.804,6.21,4.826c2.365,0.025,3.033-1.469,6.237-1.484c3.205-0.024,3.814,1.5,6.176,1.482c2.656-0.021,4.805-2.846,6.326-5.109c1.088-1.619,1.494-2.439,2.342-4.274C34.878,30.688,33.389,24.314,36.736,20.421z"/></svg>
            </a>
        </div>
        <div class="justify-self-center mt-4">
            Not a member? <a href="">Register now</a>
        </div>
    </div>
</template>
<script>
import Input from './Input.vue'
import Button from './Button.vue'
export default {
    components: {
        Input,
        Button
    }
};
</script>