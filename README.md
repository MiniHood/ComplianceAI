# ComplianceAI
ComplianceAI is a Lua addon for FiveM that uses advanced artificial intelligence to automatically detect and prevent rule-breaking behavior in the game. Whether it's cheating, exploiting, or other types of misconduct, ComplianceAI is always watching and ready to take action to maintain a fair and enjoyable gaming experience for everyone.

## Features
> Behaviour Analysis

> Built in report system

> Third party report support

## How does this work?
While not all technicalities are fully thought of and made, as of this time here's the idea and the concept I'm working on.

# Behaviour Analysis
1. Data will be collected with multiple factors, possibly hundreds.
2. Data will be parsed and sent to chat gpt
3. Repeat step 1 and 2 for about 30 - 40 minutes of their gameplay
4. Send all the summarised info to ChatGPT API
5. ChatGPT API will return a 'Trust Score'
6. This trust score can be used by developers, owners to assign permissions or whatever they want to do.

# Reports
Reports will be handled as such;
`User refers to the person who has submitted the report`
`Attacker refers to the 'reported' user.`

1. User's past behaviour will be packed
2. User's past 10 minute behaviour will be packed
3. Attacker's past behaviour will be packed
4. Attacker's past 10 minute behaviour will be pack
5. Sent off to ChatGPT with as much info such as location, speed, vehicle, weapon, who damaged who first, chat history, past warnings, past reports etc
6. ChatGPT will assign a percentage.

## Can I configure this?
Yes, you will be able to configure every aspect of this.
