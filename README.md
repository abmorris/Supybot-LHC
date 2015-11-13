# Supybot-LHC
Put the folder LHC/ inside Supybot's plugins/ directory.
e.g.
`$ git clone git@github.com:Supybot/Supybot.git`
`$ git clone git@github.com:abmorris/Supybot-LHC.git Supybot/plugins/LHC`

The commands are:

- `lhc announce add [<channel>]` -- Adds the feed. \<channel\> is only necessary if the message isn't sent in the channel itself.
- `lhc announce list [<channel>]` -- Returns the list of feeds announced in \<channel\>. \<channel\> is only necessary if the message isn't sent in the channel itself.
- `lhc announce remove [<channel>]` -- Removes the feed. \<channel\> is only necessary if the message isn't sent in the channel itself.
- `lhc last` -- Gets the last comment or machine status
