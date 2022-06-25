<template>
    <nav>
    	<div class="max-w mx-auto px">
    		<div class="flex justify-between">
    			<div class="flex">
    				<div class="flex items-center">
    					<a href="http://help-desk.test/dashboard">
    						<svg viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
    							<path d="M11.395 44.428C4.557 40.198 0 32.632 0 24 0 10.745 10.745 0 24 0a23.891 23.891 0 0113.997 4.502c-.2 17.907-11.097 33.245-26.602 39.926z" fill="#6875F5"></path>
    							<path d="M14.134 45.885A23.914 23.914 0 0024 48c13.255 0 24-10.745 24-24 0-3.516-.756-6.856-2.115-9.866-4.659 15.143-16.608 27.092-31.75 31.751z" fill="#6875F5"></path>
    						</svg>
    					</a>
    				</div>
					<nav-link href="/" label="Home" />
    			</div>
				<div class="hidden sm:flex sm:items-center sm:ml-6">
					<div class="ml-3 relative"><!----></div>
					<!--
    					<div class="ml-3 relative">
    						<div class="relative">
    							<div>
	    							<span class="inline-flex rounded-md">
	    								<button type="button" class="inline-flex items-center px-3 py-2 border border-transparent text-sm leading-4 font-medium rounded-md text-gray-300 bg-transparent hover:text-zinc-100 focus:outline-none transition">Gustavo <svg class="ml-2 -mr-0.5 h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor"><path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
	    								</button>
	    							</span>
	    						</div>
	    						<div class="fixed inset-0 z-40" style="display: none;"></div>
	    						<div class="absolute z-50 mt-2 rounded-md shadow-lg w-48 origin-top-right right-0" style="display: none;">
	    							<div class="rounded-md ring-1 ring-black ring-opacity-5 py-1 bg-white"><div class="block px-4 py-2 text-xs text-gray-400"> Gerenciar conta </div>
		    							<div>
		    								<a class="block px-4 py-2 text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100 transition" href="http://help-desk.test/user/profile"> Profile </a>
		    							</div>
		    							<form>
		    								<div><button type="submit" class="block w-full px-4 py-2 text-sm leading-5 text-gray-700 text-left hover:bg-gray-100 focus:outline-none focus:bg-gray-100 transition"> Log Out </button>
		    								</div>
		    							</form>
		    						</div>
		    					</div>
		    				</div>
		    			</div>
		    		-->
	    		</div>
	    	</div>
    	</div>
    </nav>
</template>

<script>
	import NavLink from './Link';

	export default {
		name: 'NavBar',
		components: {
			NavLink
		},
		data() {
            return {}
		},
	}
</script>

<style lang="scss" src="./style.scss" scoped />