# HEllo world docker action
This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## INputs

## 'who-to-greet'
**Required** The name of the person to greet. Default '"World"'.

## Outputs
## 'time'
The time we greeted you.
## Example usage

uses:actions/GA-customsocker@v2
with:
 who-to-greet: 'Mona the Octocat'
