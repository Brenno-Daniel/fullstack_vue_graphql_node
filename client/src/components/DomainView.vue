<template>
    <div class="container">
        <div>
            <div class="text-left">
                <router-link to="/domains">Voltar</router-link>
                <br>
                <br>
                <h2>{{ domain }}</h2>
            </div>
        </div>
    </div>
</template>

<script>
export default {
	props: ["domain"],
	data() {
		return {};
	},
};
</script>
