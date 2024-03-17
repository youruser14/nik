<script>
    import Users from './components/UserList/Users/Users.svelte';
	import Clients from './components/UserList/Clients/Clients.svelte';
	import Tasks from './components/UserList/Tasks/Tasks.svelte';
	import Dashboards from './components/UserList/Dashboards/Dashboards.svelte';
</script>

	<main>
	<div class="nav__bar">
		<h1 class="nav__bar-title">Nav Bar</h1>
		<ul class="nav__bar-items">
			<li class="nav__bar-item"><button class="nav__bar-link"><Users /></button></li>
			<li class="nav__bar-item"><button class="nav__bar-link"><Clients /></button></li>
			<li class="nav__bar-item"><button class="nav__bar-link"><Tasks /></button></li>
			<hr>
			<li class="nav__bar-item"><button class="nav__bar-link"><Dashboards /></button></li>
		</ul>
	</div>
</main>
	<style>

	button {
	padding: 0;
	border: none;
	font: inherit;
	color: inherit;
	background-color: transparent;
	cursor: pointer;
}
	
 ul {
	list-style: none;
}

.nav__bar {
	margin: 0;
	padding: 0;
	display: flex;
	flex-direction: column;
	justify-content: start;
	width: 150px;
	border-right: 1px solid black;
	height: 100vh;
	align-items: center;
}

.nav__bar-title {
	margin-bottom: 50px;
	margin-top: 15px;
}

h1 {
	color: black;
	font-size: 26px;
	font-weight: bold;
}

.nav__bar-item {
	
	margin-bottom: 15px;
	font-size: 20px;
	font-weight: 500;
}
	</style>