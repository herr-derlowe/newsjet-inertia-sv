<script>
    let name = $state("World");
    const NAMES = ["World", "James", "Igor", "Philemon", "Cornelius"];
    function changeName() {
        name = NAMES[Math.floor(Math.random() * NAMES.length)];
    }
</script>

<h1 class="text-primary">Hello {name}!</h1>
<button onclick={changeName}>Change name</button>