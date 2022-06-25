<template>
	<div>
	    <Link :href="href" :class="classes">{{ label }}</Link>
	</div>
</template>

<script>
    import { Link } from '@inertiajs/inertia-vue3'

	export default {
		components: {
			Link
		},
        props: ['href', 'active', 'label'],
        computed: {
            classes() {
                return !this.active
                    ? 'padding border transition active'
                    : 'padding border transition'
            }
        }
	}
</script>

<style lang="scss" src="./style.scss" scoped />