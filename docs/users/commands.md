# Commands
> When in doubt, check the docs 📄

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
			<th>{{command.type}}</th>
			<th>{{command.name}}</th>
			<th>{{command.description}}</th>
		</tr>
	</table>
</div>

## Slash commands
These commands can be used by pressing `/` and typing the commands out or clicking on them

<div id="slashCommandsDiv">
	<table class="sortable">
		<tr>
			<th>Name</th>
			<th>Description</th>
		</tr>
		<tr v-for="slashCommand in slashCommandsObj">
			<th>{{slashCommand.name}}</th>
			<th>{{slashCommand.description}}</th>
		</tr>
	</table>
</div>