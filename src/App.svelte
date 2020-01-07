<script>
	let name = 'bar';
	function get_next_popes() {
		return [{
			name: "foo",
			image: "bar",
		},
		{
			name: "foo2",
			image: "bar2",
		}];
	}
	let [pope1, pope2] = get_next_popes();
</script>

<h1>{pope1.name}</h1>
<img src={pope1.image}, alt="Portrait of {pope1.name}">
<h1>{pope2.name}</h1>
<img src={pope2.image}, alt="Portrait of {pope2.name}">
<h1>Hello {name}!</h1>