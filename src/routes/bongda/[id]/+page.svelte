<script>
  import TagNavigation from "$lib/TagNavigation.svelte";
  import Card from "$lib/card.svelte";
  import CoachPlayer from "$lib/coachPlayer.svelte";
  import ListPlayers from "$lib/listPlayers.svelte";
  import SettingScore from "$lib/settingScore.svelte";
  import SwitchPlayer from "$lib/switchPlayer.svelte";
  import TeamLineUp from "$lib/teamLineUp.svelte";
</script>

<TagNavigation/>

<ListPlayers />

<SettingScore />

<TeamLineUp />

<CoachPlayer />

<Card />

<SwitchPlayer/>
