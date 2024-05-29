<script setup>
    import Header from '../Components/Client/Common/Layouts/Header.vue';
    import Footer from '../Components/Client/Common/Layouts/Footer.vue';
</script>
<template>
    <Header />
	<div class="content-wrapper">
		<div class="content-header"></div>
		<div class="content">
			<div class="container-fluid">
				<slot />
			</div>
		</div>
	</div>
	<Footer />
</template>