<script>
	import { enhance } from '$app/forms'
</script>

<h1>Just click the button and inspect the requests / responses in the web inspector</h1>
<h2>(Responds with a 200 HTTP status)</h2>
<form method="POST" use:enhance>
	<input name="email" type="email" />
	<input name="password" type="password" />
	<button>Log in</button>
</form>
