# bugbounty
[This](chaos-bugbounty-list.json) JSON file controls the public bug bounty programs listed on [threatcode.github.io](https://threatcode.github.io/bugbounty). Please create a pull-request with the programs for which you'd like to see recon data. 

We are currently accepting entries in JSON format. See an example below:

```json
{
   "name":"HackerOne",
   "url":"https://hackerone.com/security",
   "bounty": true,
   "swag": true,
   "domains":[
      "hackerone.com",
      "hackerone.net",
      "hacker101.com",
      "hackerone-ext-content.com"
   ]
}
```


💬 Discussions
-----

If you have any questions/doubts/ideas to discuss, please create a "Discussion" using the [GitHub Discussions](https://github.com/threatcode/bugbounty/discussions) board.

👨‍💻 Community
-----
You can also contact us at [alerts@log4j.codes](mailto:alerts@log4j.codes).

📋 Notes
-----
- Only domain name values are accepted in the `domains` field.
- We do not support wildcard input like `*.tld` or `*.tld.*`.
- **domains** field includes TLD names associated with the target program, not based on scope of the program.
- Subdomains are populated using **Passive API** (chaos dataset).

Thank you for your contribution and for keeping the community vibrant. :heart:
