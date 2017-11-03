<html>
    <head>
        <title>BloxVerify: Roblox Verification Discord Bot</title>
        <link rel="stylesheet" href="/BloxVerify/css/style.css">
        <link href="https://fonts.googleapis.com/css?family=Raleway:300,400,600" rel="stylesheet">
        <script src="https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
    </head>
    <body>
        <header>
            <img src="/RoVer/images/logo.png" alt="RoVer" />
            <br><br><br><br>
            <a target="_blank" href="https://discordapp.com/oauth2/authorize?client_id=298796807323123712&scope=bot&permissions=402656264" class="button">Add to your server</a>
            <a target="_blank" href="https://github.com/evaera/RoVer" class="button">View Source on GitHub</a>
            <br><br>
            <h2><span id="count">50,000+</span> Robloxians verified</h2> 
            <br>
            <small>Like BloxVerify? Please <a href="https://www.patreon.com/erynlynn" target="_blank">support me on Patreon</a> if you can spare some dollars! :)</small>
        </header>
        <section>
            <div class="inner">
                <h1>Key Features</h1>
                <div class="split">
                    <div>
                        <p>Verified users can be nicknamed to their Roblox name and given a specific role upon verification.</p>
                        <p>Other features like a customizable nickname format, removing a certain role upon verification, or toggling off certain features altogether.</p>
                        <p>Nicknames are checked on a regular basis to ensure users don't change them.</p>
                        <p>Completely open source and self-hostable.</p>
                    </div>
                    <div>
                        <p><strong>Group integration</strong> &mdash; Full support for giving roles to group members at, above, or below a certain rank.</p>
                        <p>Support for other role integrations, such as user owning an asset (like a gamepass or badge) or DevForum membership.</p>
                        <p>With tens of thousands of users verified already, Roblox Discord veterans won't have to verify again to join your community.</p>
                        <p>Actively maintained and updated.</p>
                    </div>
                    <div class="clear"></div>
                </div>
            </div>
        </section>
        <section>
            <div class="inner">
                <h1>Getting Set Up</h1>
                <p>After you've <a target="_blank" href="https://discordapp.com/oauth2/authorize?client_id=375818631826767872&scope=bot&permissions=402656264">added the bot to your server</a>, the default behavior will be to nickname anyone who verifies to their Roblox username. Users can verify themselves manually by running <code>!verify</code>, but most times the process will be automatic if you use the official hosted version.</p>
                <p>To enable the "Verified" role, run the command <code>!VerifiedRole "Role Name Here"</code>. Note that if the role has spaces, you must encapsulate the name with double quoation marks.</p>
                <p>A full list of commands can be found <a href="https://github.com/evaera/RoVer#getting-started-with-rover" target="_blank">here</a>, or by running <code>!RoVer</code> in your server. Anyone with the "Manage Server" permission in your server will be able to change RoVer settings.</p>
                <p>Finally, you should probably make a read-only informational channel telling your users to visit <code>https://verify.eryn.io</code> in order to verify themselves. You can then deny "Read Messages" from users with the verified role on this channel. Note that if you intend to allow users to run <code>!verify</code>, you will need to allow them a place to do so.</p>
                <p>To learn how to use the group integration feature, please see <a href="https://github.com/evaera/RoVer#setting-up-roles-for-roblox-group-members-and-group-ranks" target="_blank">this section</a>. Remember to encapsulate role names with spaces in double quotations, otherwise you will configure the integrations incorrectly.</p>
            </div>
        </section>
        <section>
            <div class="inner">
                <h1>Frequently Asked Questions and Common Issues</h1>
                <h2>User Verification Issues</h2>
                <p>Somtimes a user will report that they are having issues verifying themselves. This is nearly always caused by a small user error, so please ask them to:</p>
                <ul>
                    <li>Ensure that they are logged in to the correct Discord account in their <strong>browser</strong>.</li>
                    <li>If they are using the <em>profile code</em> verification method, ensure the code isn't being filtered by Roblox's chat filter. If it is, try using the in-game verification method instead. If it isn't, make sure they went back to the website and clicked "Done".</li>
                </ul>

                <h2>Verification</h2>
                <ul>
                    <li>There is not currently a way to un-verify a Discord account.</li>
                    <li>You can change your verified account (or update your username) at any time, just follow the verification process again.</li>
                </ul>

                <h2>Miscellaneous</h2>
                <ul>
                    <li><strong>The bot is constantly adding and taking away roles from users!</strong> &mdash; Most likely cause is that you've bound the verification role to a group as well. Bind the group rank to a different Discord role.</li>
                    <li><strong>How do I turn off the announcement channel?</strong> &mdash; Run the AnnounceChannel command without any arguments.</li>
                    <li><strong>Can I change role names after they are set up in Rover?</strong> &mdash; Yes, roles are saved by id, not name.</li>
                    <li><strong>Is it possible to get a specific Roblox user's Discord name?</strong> &mdash; No, you can only get Roblox name from Discord user, not the other way around.</li>
                    <li><strong>Can I be verified as different users in different servers?</strong> &mdash; No, verifications are global across all servers, even if they are self-hosted.</li>
                </ul>
            </div>
        </section>
        <section>
            <div class="inner center">
                ❤️
            </div>
        </section>
        <script src="/RoVer/js/site.js"></script>
    </body>
</html>
