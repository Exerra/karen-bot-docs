# Commands
> When in doubt, check the docs

This section provides documentation about the commands. These commands are updated every time Karen Bot starts, so they are always ✨ fresh ✨

## Regular commands
These are the commands that get executed by running "m!command"
<div id="commandsDiv">
	<table class="sortable">
		<tr>
			<th>Type</th>
			<th>Name</th>
			<th>Description</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Search'">{{command.type}}</th>
			<th v-if="command.type == 'Search'">{{command.name}}</th>
			<th v-if="command.type == 'Search'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Moderation'">{{command.type}}</th>
			<th v-if="command.type == 'Moderation'">{{command.name}}</th>
			<th v-if="command.type == 'Moderation'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Utility'">{{command.type}}</th>
			<th v-if="command.type == 'Utility'">{{command.name}}</th>
			<th v-if="command.type == 'Utility'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'User'">{{command.type}}</th>
			<th v-if="command.type == 'User'">{{command.name}}</th>
			<th v-if="command.type == 'User'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Image'">{{command.type}}</th>
			<th v-if="command.type == 'Image'">{{command.name}}</th>
			<th v-if="command.type == 'Image'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Reddit'">{{command.type}}</th>
			<th v-if="command.type == 'Reddit'">{{command.name}}</th>
			<th v-if="command.type == 'Reddit'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Settings'">{{command.type}}</th>
			<th v-if="command.type == 'Settings'">{{command.name}}</th>
			<th v-if="command.type == 'Settings'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Text'">{{command.type}}</th>
			<th v-if="command.type == 'Text'">{{command.name}}</th>
			<th v-if="command.type == 'Text'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'NSFW'">{{command.type}}</th>
			<th v-if="command.type == 'NSFW'">{{command.name}}</th>
			<th v-if="command.type == 'NSFW'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Fun'">{{command.type}}</th>
			<th v-if="command.type == 'Fun'">{{command.name}}</th>
			<th v-if="command.type == 'Fun'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Misc'">{{command.type}}</th>
			<th v-if="command.type == 'Misc'">{{command.name}}</th>
			<th v-if="command.type == 'Misc'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Currency'">{{command.type}}</th>
			<th v-if="command.type == 'Currency'">{{command.name}}</th>
			<th v-if="command.type == 'Currency'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Emoji'">{{command.type}}</th>
			<th v-if="command.type == 'Emoji'">{{command.name}}</th>
			<th v-if="command.type == 'Emoji'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Music'">{{command.type}}</th>
			<th v-if="command.type == 'Music'">{{command.name}}</th>
			<th v-if="command.type == 'Music'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Settings'">{{command.type}}</th>
			<th v-if="command.type == 'Settings'">{{command.name}}</th>
			<th v-if="command.type == 'Settings'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Under Development'">{{command.type}}</th>
			<th v-if="command.type == 'Under Development'">{{command.name}}</th>
			<th v-if="command.type == 'Under Development'">{{command.description}}</th>
		</tr>
		<tr v-for="command in commandsObj">
			<th v-if="command.type == 'Uncategorized'">{{command.type}}</th>
			<th v-if="command.type == 'Uncategorized'">{{command.name}}</th>
			<th v-if="command.type == 'Uncategorized'">{{command.description}}</th>
		</tr>
	</table>
</div>