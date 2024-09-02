<script lang="ts">
    const currentTime = new Date();
    const currentHour = currentTime.getHours();

    let greeting = "Good Morning";
    if (currentHour >= 12 && currentHour < 18) {
        greeting = "Good Afternoon";
    } else if (currentHour >= 18) {
        greeting = "Good Evening";
    }
</script>

<h1 class="text-3xl font-bold">
    {greeting}, welcome to Spotify Clone!
</h1>