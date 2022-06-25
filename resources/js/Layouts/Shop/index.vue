<template>
	<div>
	    <div class="min-h-screen bg">
	        <NavBar />
	        <!-- Page Content -->
	        {{teste}}
	        <main>
	            <slot></slot>
	        </main>
	    </div>
	</div>
</template>

<script>
    // import { reactive, toRefs, computed, ref } from 'vue'
    // import { usePage } from '@inertiajs/inertia-vue3'
    import NavBar from '@/components/Shop/Layouts/NavBar';

	export default {
		components: {
			NavBar
		},
		data() {
            return {
            	teste: 11
            }
		},
	}
</script>

<style lang="scss" src="./style.scss" scoped />