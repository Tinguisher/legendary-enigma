<script setup>
import { ref } from 'vue'

defineProps({
    msg: String,
})
const Submitting = (ev) => {
    ev.preventDefault();
    console.log("clicked");
    // axiosClient.post(`/fire`, distress)
    //     .then(({ data }) => {
    //         navigate("/SOS");
    //     })
    //     .catch(() => {

    //     })
}

const count = ref(0)

</script>

<template>
    <p>email</p>
    <input type="text">
    <p>password</p>
    <input type="text">
    <br>
    <button>Submit</button>

    <!-- <h1>{{ msg }}</h1>

    <div class="card">
        <button type="button" @click="Submitting">count is {{ count }}</button>
        <p>
            Edit
            <code>components/HelloWorld.vue</code> to test HMR
        </p>
    </div>

    <p>
        Check out
        <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank">create-vue</a>, the official Vue + Vite
        starter
    </p>
    <p>
        Install
        <a href="https://github.com/vuejs/language-tools" target="_blank">Volar</a>
        in your IDE for a better DX
    </p>
    <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p> -->
</template>

<style scoped>
.read-the-docs {
    color: #888;
}
</style>
