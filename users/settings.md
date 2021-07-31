# Settings

> Heh, settings :gear:

So this section will lay out the settings for Karen Bot. Settings can be changed by running `m!settings set [setting]`.

!> All of them are disabled by default and they don't get deleted when the bot is removed from the server

<table id="settingsTable">
	<tr>
		<th>Name</th>
		<th>Description</th>
	</tr>
	<tr v-for="settings in settingsArr">
		<th>{{settings.name}}</th>
		<th>{{settings.description}}</th>
	</tr>
</table>