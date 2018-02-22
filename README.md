**HandyMan** is a basic plugin providing AOE repair functionality

Note that the normal repair cost is still applicable when you repair, you just don't have to repair each component individually.

Repair checks build privs in order to only allow repair where you can build. If you are in a building blocked zone, you can't repair - same as the standard repair behavior.

Repair follows the normal repair rules regarding damage - can't repair a structural component that took damage in the past x seconds. (No preventing raids by spamming repair)

## Permissions
- `handyman.use` -- required to use commands
### Example
- `perm.grant group default handyman.use` -- Gives all players access to commands

## Commands
Help text is provided for HandyMan displaying the commands available to players with the relevant options.
- **/HandyMan on/off** -- The functionality can be turned on or off by players.
- **/HandyMan** -- Players can check their HandyMan state.

## Configuration
```json
{
"Repair range for AOE: default is 50m"
"Default HandyMan state"
"Repair Cost Multipier: (default: 1.0 - normal costs)"
"Repair Deployables in addition to structures: (default: false - disabled)"
}
```
