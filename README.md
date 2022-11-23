(Partly) Implementation of the system described in "Stance Classification of Context-Dependent Claims" from Bar-Haim et al.

Takes three arguments when run:
1. Path to the claim dataset
2. Mode (0: training the target identifier, 1: testing, 2: testing (& caching))
3. Path to a word2Vec Model (ie. Model trained on Google News: https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit)


| id            | user_name   |   id_prop | alignment   | comment                                                                                                                                                                                                                                                                                                                           |   depth | thread_id     | last_comment_in_thread   |   upvote |   downvote | Topic        | lan   | time                      |
|:--------------|:------------|----------:|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------:|:--------------|:-------------------------|---------:|-----------:|:-------------|:------|:--------------------------|
| comment_90817 | user_5      |     89992 | Against     | Europäische Waffenexporte leisten einen großen Beitrag zum Elend in der Welt. Darum müssen sie gestoppt werden, nicht nur in Europa, sondern weltweit. Mit Waffen kann man Konflikte nicht dauerhaft lösen.                                                                                                                       |       0 | comment_90817 | True                     |        0 |          0 | EUInTheWorld | de    | 2021-09-14T10:28:46+02:00 |
| comment_1330  | user_60     |       417 | Against     | Je ne comprend pas très bien ce que l'on reproche a l'UE (vous devriez pouvoir m'éclairer). La France a certes perdu en souveraineté, mais elle ces citoyens ont gagné un poids considérable à travers l'Union. Nous pourrions recouvrer notre entière autonomie sur les choix à faire, mais alors quels seraient leurs impact ?  |       0 | comment_1330  | True                     |        3 |          0 | ValuesRights | fr    | 2021-04-22T18:55:25+02:00 |
|               |             |           |             |                                                                                                                                                                                                                                                                                                                                   |         |               |                          |          |            |              |       |                           |
|               |             |           |             | De plus, il est bien que l'Europe ait des fonctionnaires pour fonctionner. Refuser l'administration est anarchiste.                                                                                                                                                                                                               |         |               |                          |          |            |              |       |                           |                           |
