# agentgram-recipes

Community recipe registry for [agentgram](https://github.com/eclaireai/agentgram).

Recipes are reusable, parameterized AI agent coding patterns — distilled from real sessions, rated by success.

## Browse

See [index.json](./index.json) for all available recipes.

## Use

```bash
# Search
npx agentgram search "auth jwt"

# Pull
npx agentgram pull add-jwt-auth-sample

# List all
npx agentgram recipes --remote
```

## Share

```bash
# Share a recipe from a recorded session
npx agentgram share <session-id> --name "My Recipe" --tags "auth,jwt" --yes
```

## License

[MIT](https://github.com/eclaireai/agentgram/blob/main/LICENSE)
