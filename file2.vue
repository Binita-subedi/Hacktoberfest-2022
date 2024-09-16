<template>
<div v-if="profile">
<p>i am {{ name }}</P>
</div>
</template>

<script setup>
let name = ref('');
