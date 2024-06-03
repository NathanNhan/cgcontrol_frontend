<script>
    import TagNavigation from "$lib/bongda/TagNavigation.svelte";
    import SettingScore from "$lib/bongda/settingScore.svelte";
    import StatisticGoal from "$lib/match/statistic_goal.svelte";
    import StatisticMatch from "$lib/match/statistic_match.svelte";

    const socket = new WebSocket("ws://localhost:8088");

    // Connection opened
    socket.addEventListener("open", () => {
        socket.send("Hello Server!");
    });

    // Listen for messages
    socket.addEventListener("message", (event) => {
        console.log(JSON.parse(event.data));
    });
</script>


<TagNavigation />

<StatisticGoal />

<SettingScore />

<StatisticMatch />
