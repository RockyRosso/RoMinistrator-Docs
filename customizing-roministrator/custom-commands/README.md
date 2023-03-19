# Custom Commands

If you are willing to extend what RoMinistrator can do by creating custom commands, you can do so with RoMinistrator's custom made command handler.



To set up a command, create a new `.js` file within a sub folder inside the commands folder, and type the following code:

```javascript
//-- Variables

const { CommandBuilder } = require('../commandHandler');

//--

//-- Event

class Command extends CommandBuilder {
	constructor() {
		super();

		this.data = {
			name: 'template',
			description: 'Command template',
			type: this.cmd_types.chat_input,

			run: async (interaction, client) => {
				this.interaction = interaction;
				this.client = client;

				this.execute();
			},
		};
	}

	//-- Command Code --//

	async execute() {
		// Code for the command goes here
	}
}

//--

module.exports = Command;
```

You can also use the `cmd_template.js` file if you'd like.
