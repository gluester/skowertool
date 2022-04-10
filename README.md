
<h1>messy powertool skript that allows effect command power tools</h1>

<h2>usage</h2>

Step 1: enable effect commands in Skript config

<code>/skowertool make player say "hi"</code>
will output "<Username> hi"
<code>/superpowertool nick Player1 Placeholder||nick Player2 OtherPlaceholder||nick Player1 Player2||nickPlayer2 Player1</code>
switches the names of Player 1 and Player 2, || will make another command to run
the commands are ran one after the other. there's a few other commands, for example /execskript (player) (effect). player is who will execute the skript, effect is the skript to run. mostly used for impersonation or command blocks

<h2>functions</h2>
<code>loop("broadcast ""Hi""", player, 10")</code> will make the player run !broadcast "Hi" 10 times
