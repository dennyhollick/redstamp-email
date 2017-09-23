## Redstamp FE Test

To view the work, simply download the repository and open index-inlined.html

- [x] Cross Browser Tested
- [x] Cross Platform Tested
- [x] Responsive
- [] Includes SVG

For this I tried to ensure maximum compatibility across all email clients. To do that I used a well developed/supported boilerplate and modified it to work for the email.

I used Litmus/Mailchimp to test across the most common clients (Top 10). It worked nearly perfectly in all clients, but for some reason my litmus tests were coming back empty for Outlook, and I don't have a PC/Outlook to test on so had to move forward. Without those tools I didn't want to over-invest. I could be due to some conditionals I've set.

I worked a bunch on the SVG referencing this: https://css-tricks.com/a-guide-on-svg-support-in-email/ as well as several other articles.

Unfortunately, no matter what methodology I used for SVG (I used all of them listed here), there was always a client that came back with visual bugs, and so I abandoned using SVG. I couldn't really find anyone saying using SVG in email was a good idea, but perhaps I didn't dig deep enough.

I can say that it works in the majority of clients quite well though, pending some testing on MSO. :)

## Things to still do/improve

*Perfection is the enemy of good*

- [ ] Test MSO
- [ ] Find SVG fix? Practical?
- [ ] Add links 
- [ ] Fix some of the styling to be a bit closer to spec

