# 100 Days Of Code - Log

### Day 1: 29 December 2016

**Today's Progress**: Forked 100 Days of Code and updated outdated WooCommerce files on thecleft.org

**Thoughts:** Pretty boring work. I'm fairly confident that I have more files than needed duplicated, but they are all updated

**Link to work:** [Cleft Repository](https://github.com/DustinHartzler/TheCLEFT/commit/2733f569770d2cf39a49ac5677095e0b818585ff)

### Day 2: 30 December 2016

**Today's Progress**: Started working on As Heard On plugin and I fixed the bug that the data wasn't be deleted from the database.

**Thoughts**: Looking at the code, I'm impressed I was able to modify a Testimonial plugin to get it to work like it has. There's a lot to refactor and make the code simpler.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/3ae18b85dd2208a690456a1135633c7323017627)

### Day 3: 31 December 2016

**Today's Progress**: Added new if statement to check if 'ppg_version' option is set to 0.5. The if statement will look for all the previous options and move them into an array (hopefully tomorrow!)

**Thoughts**: Spent time thinking / planning on how to save current options to a new serialized array. No reason that a small plugin like AHO, should be adding more than 2 or 3 rows to the table. Currently there's more than 20!

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/fc5d79d15804e5eec18ae811496422141f820566)

### Day 4: 01 January 2017

**Today's Progress**: Created `legacy.php` to add all the code to remove old options from WordPress database

**Thoughts**: Really important to set a plugin up initially correctly. I'm finding it's very tedious to remove options, but save the settings in the database.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/b5514b245aee953ea78651ea72074c86b771157c)

### Day 5: 02 January 2017

**Today's Progress**: Removed a nevercalled function that was supposed to remove settings from the database. Also, moved the location of the 'help' menu so it was visible on all pages and made the footer less bulky

**Thoughts**: Worked solidly for an hour and didn't accomplish much. Starting to see why software development takes so long! Need to work on calling data from new serialized arrays tomorrow.

**Links to work**: [#](https://github.com/DustinHartzler/As-Heard-On/commit/2dbbd5b9c7e513930e9a57927105c7d5c89fe265), [#](https://github.com/DustinHartzler/As-Heard-On/commit/8a0e92a16b32d4e9dc23a3e7681f68505db585c2), [#](https://github.com/DustinHartzler/As-Heard-On/commit/54b90a1da2a637f0ace338c18ff13f21561e49a1)

### Day 6: 03 January 2017

**Today's Progress**: Have one option running on serialized data.

**Thoughts**: Slow moving today. Started to move variables to serialized array. Much harder than expected.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/7f2b3f02dd98ddb5b8f6b574aed6ee19726d569d)

### Day 7: 04 January 2017

**Today's Progress**: Added 3 new variables to the array and tested to make sure the options were working correctly. `showlink`, `image_width`, and `image_height` are now working as well as `linktext` from late last night's bonus session

**Thoughts**: Made much more progress today versus yesterday, yay! Still have a lot more to do to simplify the code and get all the pieces working efficiently. Perhaps by the end of the month I'll be able to start adding new features :)

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/041a1be329512826ce36681ab9ab84f73bb1d81d)

### Day 8: 05 January 2017

**Today's Progress**: Made more progress moving data to the serialized array. Only a handful more and this task will be complete!

**Thoughts**: I thought I'd get everything finished today, yet, when I went to start working on the page settings, I realized all of the widget settings were being erased. Two steps forward and one back. Both panels are working now.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/1cf1a50d65f0c69b271cf35ed35aaf06a174ff15)

### Day 9: 06 January 2017

**Today's Progress**: Finished moving all variables to serialized array.

**Thoughts**: Again, it was a bit tricker than I thought it would be and now I know why it's so important to set things up properly the first time :) Tomorrow I'll do a bit of testing and see how well things work when I update the plugin to the new version.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/b34215944f1d2b42f492aef36a5df6cd94ecdd5e)

### Day 10: 07 January 2017

**Today's Progress**: Tested the upgrade routine and if the variables would be mapped correctly when activating 2.0

**Thoughts**: I had changed a few variables, so all of the settings didn't map correctly to the serialized array. After a few tweaks everything looks good now.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/79e35380d1ca9d7d8797d6d1e06aa8fcff7eb2a1)

### Day 11: 08 January 2017

**Today's Progress**: Fixed imgdisplay values not transferring over on upgrade

**Thoughts**: Still testing old plugin versus new to make sure all values are being transferred over so the settings don't need to be configured again. Slow process, but still enjoyable :)

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/132c9c53e7d3f330c18fdf31537865e8ed6f9ac5)

### Day 12: 09 January 2017

**Today's Progress**: Fixed deldata variable and changed code to delete data when the plugin is uninstalled. It was set to delete on deactivation.

**Thoughts**: Another slowish day. Changed two things at once and it made things go all goofy. Remember, work on one thing at a time ;)

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/c2720ade1113724352943af3f6b298c244046feb)

### Day 13: 10 January 2017

**Today's Progress**: Worked on adding default settings for the plugin. Nothing worked.

**Thoughts**: Will attempt to make progress tomorrow.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/a13c34d977d60bdd7602c03d816d5e3595c2c765)

### Day 14: 11 January 2017

**Today's Progress**: Fixed a bug if no host, other details wouldn't show.

**Thoughts**: Spent a majority of the day figuring out how to change a column name in the database. `testid` didn't make sense, so I changed it to `aho_id` will finish the code tomorrow.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/1681e602ebefa6a5c1b2f98a5acaafa0824d6c22)

### Day 15: 12 January 2017

**Today's Progress**: Finished changing all the `testid` to `aho_id` in the plugin.

**Thoughts**: Also started exploring CodeKit and eventually figured out how to compile my Sass and JS files. I'll explore this a bit more later.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/4abb3f1c588507ae35c686582f5456bb67d639a0)

### Day 16: 13 January 2017

**Today's Progress**: Fixed some small visuals and added some Javascript

**Thoughts**: I can now rearrange the podcasts by clicking and dragging, but the new values aren't updated in the database. That's next :)

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/6653e4367908662f03d45ba56a1d89828515b6b8)

### Day 17: 15 January 2017

**Today's Progress**: Bit different challenge today. Wrote some SQL commands to change copy on YourWebsiteEngineer.com

**Thoughts**: Changed some outdated text and switched to WP SEO from Yoast. Had to write SQL to change meta data from one plugin to another.

**Link to work**: [Your Website Engineer](https://github.com/DustinHartzler/ywe/commit/b9fce5bc935c2af48614e9431d3e3042d5ae1d22)

### Day 18: 15 January 2017

**Today's Progress**: Little different today. Spent time checking connections to VaultPress.

**Thoughts**: Boring but necessary work.

### Day 19: 16 January 2017

**Today's Progress**: Started making adjustments to my theme to make it better.

**Thoughts**: I haven't worked on my site for a really long time. This ends now. Started to dedicate a few hours per week for modifications and customizations.

**Link to work**: [Your Website Engineer](https://github.com/DustinHartzler/ywe/commit/26397fc282454c6a119c82e7a89865645fdfb1d6)

### Day 20: 17 January 2017

**Today's Progress**: Got the footer optin almost complete. Need some responsive testing and to pretty up the button a bit.

**Thoughts**: This is fun. I miss tweaking and building websites.

### Day 21: 18 January 2017

**Today's Progress**: Fixed 404 page. It's been broken since my LeadPages account expired.

**Thoughts**: Again, more fun. The time went really quickly!

**Link to work**: [Your Website Engineer](https://github.com/DustinHartzler/ywe/commit/9be4259f8f930052c8946494774523b7af1fa4aa)

### Day 22: 20 January 2017

**Today's Progress**: Spent time making lightbox appear when clicking on the subscribe link, a custom lightbox, not the standard one that comes with ConvertKit

**Thoughts**: Once I get this all figured out, I'll be implementing this box everywhere because it's much nicer than the standard ConvertKit one.

**Link to work**: [Your Website Engineer](https://github.com/DustinHartzler/ywe/commit/fcf43554f0195803c98e5a9e9b7f9850145d20ff)

### Day 23: 20 January 2017

**Today's Progress**: Spent nearly the whole time figuring out how to remove the placeholder text.

**Thoughts**: I still am very weak in how to incorporate Javascript correctly into a WordPress site.

**Link to work**: [Your Website Engineer](https://github.com/DustinHartzler/ywe/commit/b7279b45dd2b2bcfb581914bc89247b67820a18f)

### Day 24: 22 January 2017

**Today's Progress**: Added Affiliate link to popup box. Moved code for popup to own file to make it easier to use on other pages.

**Thoughts**: Since everything is working as I'd like, now I've moved the code into it's own file so I can use it more easily.

**Link to work**: [Your Website Engineer](https://github.com/DustinHartzler/ywe/commit/89a1f96cb1c9d469f3d69cf7e8967fc068d4cf69)

### Day 25: 22 January 2017

**Today's Progress**: Added code to call the popup from the sidebar and reworked sidebar widget to display this form instead. Tweaked CSS to move the popup module beneath the sticky menu.

**Thoughts**: Took a little while to figure out how to get the popup to be shown in the right spot, it was initially showing at the way bottom of the screen. I'm really happy with the way it looks. Much better than the standard ConvertKit optin.

**Link to work**: [Your Website Engineer](https://github.com/DustinHartzler/ywe/commit/1fe800c32baa9a944a3a4ae2d2cb13b58a33ada8)

### Day 26: 23 January 2017

**Today's Progress**: Fixed a couple simple bugs for the WooCommerce USPS shipping extension.

**Thoughts**: Today was a wonky day with half a day training, so I gave up trying to work on tickets. So I worked on a few outstanding issues that I could find. My goal is 4 pull requests per month and I've got 2 in so far.

**Link to work**: Redacted (private repository)

### Day 27: 24 January 2017

**Today's Progress**: More work today on the settings layout for WooCommerce USPS extension

**Thoughts**: It's fun to work on projects that I use daily for work. I think I'll keep up working on WooCommerce extensions Monday-Friday and my projects on the weekends for a few weeks.

**Link to work**: Redacted (private repository)
