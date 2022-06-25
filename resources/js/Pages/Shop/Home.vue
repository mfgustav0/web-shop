<template>
	<layout-shop>
		<h1>{{ interator }} - Logged With {{ user?.name }}</h1>
		<div>
			<button @click="addInt">Adicionar</button>
		</div>
	</layout-shop>
</template>

<script>
    import { reactive, toRefs, computed, ref } from 'vue'
    import { usePage } from '@inertiajs/inertia-vue3'
    import LayoutShop from '@/Layouts/Shop';

	export default {
		name: 'Home',
		components: {
			LayoutShop
		},
		setup() {
		    const user = computed(() => usePage().props.value.auth.user)

            const interator = ref(2);

            const methods = reactive({
                addInt() {
                    interator.value++;
                },
            })

            return {
                interator,
                user,
                ...toRefs(methods)
            }
		},
	}
</script>

<style type="scss">
	h1 {
		color: #4B5563;
		background: #fdfdfd;
	}
</style>