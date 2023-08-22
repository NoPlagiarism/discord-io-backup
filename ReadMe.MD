# [Discord.io](https://discord.io) data public backup

> On the night of the 14th of August, [Discord.io](https://discord.io) suffered a major 
> databreach, resulting in content from our database being leaked to 
> unknown actors.
> 
> We were made aware of the breach later on in the day, and after 
> confirming the content of the breach, we decided to shut down all 
> services and operations.
> 
> [Discord.io](https://discord.io) 

## data.json & data-min.json

### Structure

```json
{
    "key": "url"
}
```

Url can be `discord.gg` to server or bot invite link.

### Fast access through GitHub raw file

Urls:

data.json with indent (≈18.6 MB)

```
https://raw.githubusercontent.com/NoPlagiarism/discord-io-backup/master/data.json
```

data.json minified (≈16 MB)

```
https://raw.githubusercontent.com/NoPlagiarism/discord-io-backup/master/data-min.json
```

### Source

Discord.io is now using this file to handle short links that still being opened. `https://discord.io/output.json`

## servers_list.txt (≈9.2 MB)

### Stucture

```textile
short_name → id of invite (discord.gg/{insert this id}
```

### Source

As Parapluie (one of the administrators and co-founder of **Discord.io**) [said](https://discord.com/channels/232335047170981890/1140683689471266958/1140685457336848384), it's public server invites list

### servers_list.json (≈11.3 MB)

## Structure

```json
{
    "key": "id of invite (discord.gg/{insert this id}"
}
```

### Source

Tried to organize servers_list.txt to machine-readable .json
