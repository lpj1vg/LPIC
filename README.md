# REGEX


| Character |                          Legend                          |   Example    |  Sample Match  |      |      |
|-----------|----------------------------------------------------------|--------------|----------------|------|------|
| .         | Any character except line break                          | a.c          | abc            |      |      |
| .         | Any character except line break                          | .*           | whatever, man. |      |      |
| \.        | A period (special character: needs to be escaped by a \) | a\.c         | a.c            |      |      |
| \         | Escapes a special character                              | \.\*\+\?     | \$\^\/\\       | .*+? | $^/\ |
| \         | Escapes a special character                              | \[\{\(\)\}\] | [{()}]         |      |      |
