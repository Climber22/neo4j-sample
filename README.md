# neo4j-sample

## How to run

```sh
$ docker-compose up

Creating network "neo4j-sample_default" with the default driver
Pulling neo4j (neo4j:latest)...
latest: Pulling from library/neo4j
8559a31e96f4: Pull complete
65306eca6b8e: Pull complete
ddbf88050b6e: Pull complete
68e07c1589b8: Pull complete
6438c4691e1f: Pull complete
5671df92870a: Pull complete
8f0598830b28: Pull complete
47c0eac39945: Pull complete
Digest: sha256:31ab962174fed902ca87c33786a294797ee7a197828ed920a7a2bfd74720f864
Status: Downloaded newer image for neo4j:latest
Creating neo4j-sample_neo4j_1 ... done
Attaching to neo4j-sample_neo4j_1
neo4j_1  | Warning: Folder mounted to "/logs" is not writable from inside container. Changing folder owner to neo4j.
neo4j_1  | Warning: Folder mounted to "/data" is not writable from inside container. Changing folder owner to neo4j.
neo4j_1  | Directories in use:
neo4j_1  |   home:         /var/lib/neo4j
neo4j_1  |   config:       /var/lib/neo4j/conf
neo4j_1  |   logs:         /logs
neo4j_1  |   plugins:      /var/lib/neo4j/plugins
neo4j_1  |   import:       /var/lib/neo4j/import
neo4j_1  |   data:         /var/lib/neo4j/data
neo4j_1  |   certificates: /var/lib/neo4j/certificates
neo4j_1  |   run:          /var/lib/neo4j/run
neo4j_1  | Starting Neo4j.
neo4j_1  | 2020-06-15 12:30:57.286+0000 INFO  ======== Neo4j 4.0.5 ========
neo4j_1  | 2020-06-15 12:30:57.294+0000 INFO  Starting...
neo4j_1  | 2020-06-15 12:31:49.484+0000 INFO  Bolt enabled on 0.0.0.0:7687.
neo4j_1  | 2020-06-15 12:31:49.487+0000 INFO  Started.
neo4j_1  | 2020-06-15 12:31:50.873+0000 INFO  Remote interface available at http://localhost:7474/
```

Then visit http:localhost:7474 on your browser.

At first, you will be asked username/password.  
You can pass by entering neo4j for username, password.

After that, you have to reset password.


Finally, you can play with neo4j!

[![Image from Gyazo](https://i.gyazo.com/eb95914f40510d71f74254c1dafeabc4.png)](https://gyazo.com/eb95914f40510d71f74254c1dafeabc4)


